<template>

                <section id="navigation-bar">
                <div className="">
                    <div className="row">
                        <nav className="navbar sticky-top navbar-dark bg-dark navbar-expand-lg p-0">
                            <div className="container">
                                <div>
                                    <a href="/">
                                        <span className="navbar-brand brand-nav" href="/">
                                            <img className="logo" src="../../assets/logo/logo.png" alt="handshake_logo" />
                                        </span>
                                    </a>
                                </div>
                                <button className="navbar-toggler" type="button" data-bs-toggle="collapse"
                                    data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
                                    aria-expanded="false" aria-label="Toggle navigation">
                                    <span className="navbar-toggler-icon"></span>
                                </button>
                                <div className="collapse navbar-collapse nav-item-container" id="navbarSupportedContent">
                                    <ul className="navbar-nav me-auto mb-2 mb-lg-0 col-lg-9 nav-ul">
                                        <li className="nav-item">
                                            <a href="/" :style="{textDecoration: 'none'}">
                                             <!-- style={{ textDecoration: "none" }} -->
                                                <span className="nav-link active nav-items" aria-current="page">Home</span>
                                            </a>
                                        </li>
                                        <li className="nav-item">
                                            <a href="/timeline" :style="{textDecoration: 'none'}">
                                             <!-- style={{ textDecoration: "none" }} -->
                                                <span className="nav-link nav-items">Timeline</span>
                                            </a>
                                        </li>
                                        <li className="nav-item dropdown">
                                            <a href="/network" :style="{textDecoration: 'none'}">
                                             <!-- style={{ textDecoration: "none" }} -->
                                                <span className="nav-link nav-items">
                                                    Network
                                                </span>
                                            </a>
                                        </li>
                                        <li className="nav-item" :style="{textDecoration: 'none'}">
                                            <a href="/" :style="{textDecoration: 'none'}">
                                            <!--  style={{ textDecoration: "none" }} -->
                                                <span className="nav-link nav-items disabled">About</span>
                                            </a>
                                        </li>
                                    </ul>
                                    <form className="d-flex" role="search">
                                        <input className="form-control search-input" type="search" placeholder="Search"
                                            aria-label="Search" />
                                         <!-- removed this className="me-2" to remove the right margin after search box  -->
                                        <button className="btn search-btn" type="submit"><font-awesome-icon icon="fa-solid fa-magnifying-glass" /></button>
                                    </form>
                                </div>
                            </div>
                        </nav>
                    </div>
                </div>
            </section>
</template>
<script>
export default {
    name:'TopNavbar'
}
</script>
