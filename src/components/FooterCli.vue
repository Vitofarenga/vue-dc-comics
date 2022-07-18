<template>
    <div>
        <section id="blackmenu">
           <section id="liste">
            <ul>
                <h3>DC COMICS</h3>
                <li>Characters</li>
                <li>Mvies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Videos</li>
                <li>News</li>
                <ul id="piccolo">
                    <h3 id="titolopiccolo">SHOP</h3>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
            </ul>
            <ul>
                <h3>DC</h3>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
            </ul>
            <ul>
                <h3>SITES</h3>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
            </ul>
        </section>
        <img id="logogrande" src="../assets/dc-logo-bg.png" alt="">
        </section>
        <div id="realfooter">
            <div><button>SIGN-UP NOW</button></div>
            <ul id="footerlist">
                <li><h3 id="seguiciora">FOLLOW US</h3></li>
                <li><img src="../assets/footer-facebook.png" alt=""></li>
                <li><img src="../assets/footer-periscope.png" alt=""></li>
                <li><img src="../assets/footer-pinterest.png" alt=""></li>
                <li><img src="../assets/footer-twitter.png" alt=""></li>
                <li><img src="../assets/footer-youtube.png" alt=""></li>
            </ul>
        </div>
    </div>
</template>

<script>
export default{

}
</script>

<style scoped>
#blackmenu{
    width: 100%;
    height: 25rem;
    background-image:url(../assets/footer-bg.jpg);
    object-fit: contain;
    display: flex;
    justify-content: space-around;
}
#logogrande{
    height: 25rem;
    width: 25rem;
}
ul{
    list-style: none;
    display: flex;
    flex-direction: column;
}
ul li{
    display: flex;
    align-content: flex-start;
    color: white;
}
#liste{
    display: flex;
    margin-top:3rem;
}
h3{
    color: white;
    font-weight: bold;
}
#piccolo{
    padding-left:0;
    margin-top: 1rem;
}
#titolopiccolo{
    text-align: start;
}
#realfooter{
    background-color:rgba(48,48,48,255);
    width: 100%;
    height: 10rem;
    display: flex;
    justify-content: space-around;
    align-items: center;
}
button{
    color:white;
    font-weight: bold;
    padding: 1rem;
    border: .2rem solid rgba(2,130,249,255);
    background-color: rgba(48,48,48,255);
}
#seguiciora{
    color: rgba(2,130,249,255);
}
#footerlist{
    list-style: none;
    display: flex;
    flex-direction:row;
}
img{
    width: 2rem;
    height: 2rem;
    margin-left: 1rem;
}

</style>
