<template>
    <nav class="d-flex">
        <img src="../assets/dc-logo.png" alt="">
        <ul>
            <li>CHARACTERS</li>
            <li>COMICS</li>
            <li>MOVIES</li>
            <li>TV</li>
            <li>GAMES</li>
            <li>COLLECTIBLES</li>
            <li>VIDEOS</li>
            <li>FANS</li>
            <li>NEWS</li>
            <li>SHOP</li>
        </ul>
    </nav>
</template>

<script>
export default{

}
</script>

<style scoped>
   img{
    width: 7rem;
    height: 7rem;
    padding: 1rem;
    margin-left: 15rem;
    margin-right: 17rem;
   };
   nav ul{
    list-style: none;
   }
   li{
    padding-top: 3rem;
    margin-left:1.5rem;
    display: inline-block;
    font-weight: bold;
    font-size: .7rem;
    padding-bottom:3rem;
    border-bottom: .3rem solid white
   }
   li:hover{
    border-bottom: .3rem solid rgba(2,130,249,255);
    color:rgba(2,130,249,255);
   }
</style>
