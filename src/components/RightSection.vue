<template>
    <div class="right">
        <div class="images">
            <img src="../assets/backgroundsoft.png" alt="background" class="brush">
            <img src="../assets/fotodind.png" alt="Dinda" class="me">
        </div>
    </div>
    
</template>

<style>
.right {
  margin-top: 20px; /* Atur jarak antara konten "RightSection" dengan konten "About" */
}

.images{
    width: 45%;
    height: 80%;
    position: absolute;
    bottom: 0;
    right: 70px;

}

.images img{
    height: 100%;
    position: absolute;
    left: 50%;
    bottom: 0;
    transform: translateX(-50%);
    transition: bottom 1s, left 1s;

}

.images:hover .brush{
    bottom: 40px;
}

.images:hover .me{
    left: 45%;
}
</style>