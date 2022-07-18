<template>
    <div>
        <section id="contenthere">
           
        </section>
        <section id="bluemenu">
            <ul>
                <li><img src="../assets/buy-comics-digital-comics.png" alt=""><span>DIGITL COMICS</span></li>
                <li><img src="../assets/buy-comics-merchandise.png" alt=""><span>DC MERCHANDISE</span></li>
                <li><img src="../assets/buy-comics-subscriptions.png" alt=""><span>SUBSCRIPTION</span></li>
                <li><img src="../assets/buy-comics-shop-locator.png" alt=""><span>COMIC SHOP LOCATOR</span></li>
                <li><img src="../assets/buy-dc-power-visa.svg" alt="" id="visa"><span></span>DC POWER VISA</li>
            </ul>
        </section>
    </div>
</template>

<script>
export default{

}
</script>

<style scoped>
#contenthere{
    width: 100%;
    height: 25rem;
    background-image:url(../assets/jumbotron.jpg);
    background-size:cover;
}
h3{
    color: white;
    margin-left: 16rem;
    margin-top: 3rem;
    font-weight: bold;
}
#bluemenu{
    width: 100%;
    height: 10rem;
    background-color: rgba(2,130,249,255);
}
section ul{
    list-style: none;
}
li{
    margin-left:1.5rem;
    display: inline-block;
    font-weight: bold;
    font-size: .7rem;
    color: white;
    margin-top:2.5rem;
    padding-left:1rem;
}
img{
    height: 4rem;
}
#visa{
    height: 2.5rem;
}
span{
    margin-left: 1rem;
}
</style>
