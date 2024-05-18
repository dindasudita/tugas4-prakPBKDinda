<template>
    <div class="navi">
        <nav>
        <img src="../assets/logoBag.png" class="logodi">
        <ul>
            <li><a href="#Main">HOME</a></li>
            <li><a href="#Features">FEATURES</a></li>
            <li><a href="#Types">TYPES</a></li>
        </ul>
        </nav> 
    </div>
</template>

<style>
.navi{
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background: #f4c9b4;
    z-index: 1000;
}

nav{
    display: flex;
    width: 100%;
    padding: 20px 0;
    align-items: center;
    justify-content: space-between;
    margin: 0;
}

nav ul li{
    display: inline-block;
    list-style: none;
    margin: 10px 20px;
}

nav ul li a{
    text-decoration: none;
    color: #df5430;
    font-weight: bold;
}

nav ul li a:hover{
    color: #df5430;
}

.logodi{
    max-width: 250px;
    max-height: 50px;
}
</style>
