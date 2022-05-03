<template>
    <div class="container">
        <div class="header-wrap">
            <div class="logo-wrap">
                <h1>logo</h1>
            </div>
            <div class="navbar-wrap">
                <nav class="nav">
                    <ul>
                        <li>홈</li>
                        <li>카테고리</li>
                        <li>Live</li>
                        <li>My</li>
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
    position: fixed; top: 0; left: 0;
    z-index: 1750;
    width: 100%;
    min-width: 1240px;
    background-color: #1b1b1b;
}
.header-wrap {
    display: flex; justify-content: space-around; align-items: center;
    position: relative;
    width: 1240px; height: 74px;
    margin: 0 auto;
}
.logo-wrap {
    
}
.logo-wrap h1 {
    color: #fff;
}
.navbar-wrap {

}
.nav {

}
.nav ul {
    display: flex;
}
.nav ul li {
    color: #fff;
}
.search-input {

}
.search-input input {

}

</style>