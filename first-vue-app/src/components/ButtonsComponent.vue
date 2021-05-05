<template>
    <div class="buttons">
    <button type="submit" class="searchButton">Căutare Google</button>
    <button type="submit" class="feelLuckyButton">Mă simt norocos</button>
 </div>
</template>

<script> 
    export default {
        name: 'ButtonsComponent'
    }
</script>

<style>
.buttons{
    display: inline-flex;
    width: 100%;
    justify-content: center;
    margin-top: 1.6rem;
}
  
.buttons button{
    border: none;
    height: 2.3rem;
    width: 8.2rem;
    margin-inline: 0.5rem;
    font-family: arial,sans-serif;
    font-size: 14px;
    color: #3c4043;
    background-color: #f8f9fa;
    border: 1px solid #f8f9fa;
}
</style>