<template>
    <div class="left">
        <div class="info">
            <h1>Hai, saya Dinda</h1>
            <p>Ini adalah halaman website portfolio pribadi saya, yang berisi informasi mengenai skill dan pengalaman saya</p>
        </div>
    </div>
    
</template>

<style>
.info{
    margin-left: 8%;
    margin-top: 50%;
}
   
.info h1{
    font-size: 50px;
    color: #815854;
    margin-bottom: 20px;
}
.info p{
    color:#543c3a;
    line-height: 22px;
}   

@media screen and(max-width: 720px) {
    *{
        margin: 0;
        padding: 0;
        font-family: sans-serif;
    }

    .info{
        margin-left: 8%;
        margin-top: 13%;
    }
    
    .info h1{
        font-size: 10px;
        color: #212121;
        margin-bottom: 20px;
    }

}
</style>