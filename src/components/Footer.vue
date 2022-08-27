<template>
                <section id="footer">
                <div class="container">
                    <div class="row">
                        <div class="col-md-3">
                            <div>
                                <img class="logo" src="../../src/assets/logo/logo.png" alt="handshake_logo" />
                                <a class="footer-brand-name" href="/">Friendzee</a>
                            </div>

                            <div class="row">
                                <Link to=""></Link>
                                <a class="social-icons" href="/">
                                    <i class="fa-brands fa-google-plus-g"></i>
                                </a>
                                <a class="social-icons" href="/">
                                    <i class="fa-brands fa-facebook-f"></i>
                                </a>
                                <a class="social-icons" href="/">
                                    <i class="fa-brands fa-twitter"></i>
                                </a>
                                <a class="social-icons" href="/">
                                    <i class="fa-brands fa-instagram"></i>
                                </a>
                                <a class="social-icons" href="/">
                                    <i class="fa-brands fa-linkedin-in"></i>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-6">
                            <h3>Contact us</h3>
                            <div>
                                <a class="contact-items" href="/"> <font-awesome-icon icon="fa-solid fa-phone" class="contact-icons"/>+91
                                    123456987</a>
                            </div>
                            <hr />
                            <div>
                                <a href="mailto: snjvkansari@hotmail.com" :style='{ textDecoration: "none" }'>
                                    <a class="contact-items" href="mailto: snjvkansari@hotmail.com"><font-awesome-icon icon="fa-solid fa-envelope" class="contact-icons"/>snjvkansari@hotmail.com</a>
                                </a>
                            </div>
                            <hr />
                            <div>
                                <a class="contact-items" href='/'>
                                <font-awesome-icon icon="fa-solid fa-location-dot" class="contact-icons"/>New rajendra
                                    nagar, Raipur</a>
                            </div>
                            <hr />
                        </div>

                        <div class="col-md-3" :style="{textAlign:'left'}">
                            <h3>About</h3>
                            <div>
                                <ul>
                                    <li class="footer-nav">
                                        <a class="footer-item" href="signup.html" target="_blank" :style='{ textDecoration: "none" }'
                                            rel="noopener noreferrer">Home</a>
                                    </li>
                                    <li class="footer-nav">
 
                                            <a class="footer-item" :style='{ textDecoration: "none" }' href="/" target="_blank" rel="noopener noreferrer">My
                                                timeline</a>
                                        
                                    </li>
                                    <li class="footer-nav">
                                            <a class="footer-item" :style='{ textDecoration: "none" }' href="/" target="_blank"
                                                rel="noopener noreferrer">My network</a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>

                    <div id="name">

                    </div>

                </div>
                <div class="last-sticky-row">

                    Web reserved @2022

                </div>
            </section>
</template>
<script>
export default {
    name:'FooTer',
}
</script>