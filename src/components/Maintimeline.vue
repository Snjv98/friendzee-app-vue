<template>
    <Post/>
</template>
<script>
import Post from './Post.vue'
// import Post from './Post.vue'
export default {
    name: 'MainTimeline',
    components:{ Post },
    data(){
        return{
            newPost:""
        }
    },
    methods:{
        addPost(){
            if(this.newPost){
                alert(this.newPost)
                this.Post.push({
                    desc: this.newPost,
                    photo: require("@/assets/person/user2.jpg"),
                    date: "5 mins ago",
                    userId: 4,
                    like: 3,
                    love: 8,
                    comment: 9

                })
            }
        }
    }
}

// import Postdata from './Postdata.vue'
// export default{
//     name:'MainTimeline',
//     components:{Postdata}
// }
</script>