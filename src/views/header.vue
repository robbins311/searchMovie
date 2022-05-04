<template>
    <div class="container">
        <div class="header-wrap">
            <div class="logo-wrap">
                <h1>logo</h1>
            </div>
            <div class="navbar-wrap">
                <nav class="gnb">
                    <ul>
                        <li>
                            <router-link to="/">홈</router-link>
                        </li>
                        <li>
                            <router-link to="/">카테고리</router-link>
                        </li>
                        <li>
                            <router-link to="/">Live</router-link>
                        </li>
                        <li>
                            <router-link to="/">My</router-link>
                        </li>
                    </ul>
                </nav>
            </div>
            <div class="search-input">
                <input type="text" placeholder="search">
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
*, body, html { word-break: break-all; word-wrap: break-word; margin: 0; padding: 0; box-sizing: border-box; }
li { list-style: none; }
a { text-decoration:none; }

.container {
    position: fixed; top: 0; left: -20px;
    z-index: 1750;
    width: 100%;
    min-width: 1240px;
    background-color: #1b1b1b;
}
.header-wrap {
    display: flex; justify-content: space-evenly; align-items: center;
    position: relative;
    width: 1240px; height: 97px;
    margin: 0 auto;
}
.logo-wrap {
    position: relative; left: -80px;
}
.logo-wrap h1 {
    color: #fff;
}
.navbar-wrap {

}
.gnb {
    position: relative; left: -120px;
}
.gnb ul {
    display: flex; align-items: center;
}
.gnb ul li {
    margin: 0 20px; padding: 0 10px;
    font-size: 20px;
    line-height: 74px;
}
.gnb ul li a {
    color: #a5a5a5;
}
.search-input {

}
.search-input input {
    width: 164px; height: 40px;
    background: url(../assets/images/dot.png) no-repeat 0;
    font-size: 20px;
    color: #a5a5a5;
    border-radius: 0; border: none; border-bottom: 2px solid #2f2f2f;
    padding-left: 40px;
    outline: 0;
}

</style>