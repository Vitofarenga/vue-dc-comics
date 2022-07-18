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
        <img src="../assets/dc-logo-bg.png" alt="">
        </section>
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
img{
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


</style>
