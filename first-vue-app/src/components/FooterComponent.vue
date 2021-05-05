<template>
    <div class="footer">
     <div class="country"><p>România</p></div>
     <div class="others">
         <div class="left-container">
            <a href = "https://about.google/?utm_source=google-RO&utm_medium=referral&utm_campaign=hp-footer&fg=1">Despre</a>
            <a href = "https://www.google.ro/intl/ro_ro/ads/?subid=ww-ww-et-g-awa-a-g_hpafoot1_1!o2&utm_source=google.com&utm_medium=referral&utm_campaign=google_hpafooter&fg=1">Publicitate</a>
            <a href = "https://www.google.ro/services/?subid=ww-ww-et-g-awa-a-g_hpbfoot1_1!o2&utm_source=google.com&utm_medium=referral&utm_campaign=google_hpbfooter&fg=1">Companii</a>
            <a href = "https://google.com/search/howsearchworks/?fg=1">Cum funționează Căutarea</a>
         </div>
         <div class="right-container">
             <a href = "https://policies.google.com/privacy?hl=ro&fg=1">Confidențialitate</a>
             <a href = "https://policies.google.com/terms?hl=ro&fg=1">Termeni</a>
             <a href = "">Setări</a>
        </div>
     </div>
 </div>
</template>

<script>
    export default {
        name: 'FooterComponent'
    }
</script>

<style>
.footer{
    position: absolute;
    right: 0;
    bottom: 0;
    left: 0;
}
.country{
    height: 3rem;
    width: 97.8vw;
    border-bottom: 1px solid #dadce0;
    font-size: 15px;
    padding: 0.2rem 0rem 0 2rem;
    font-family: arial,sans-serif;
    color: #6f6f6f;
    background-color: #f2f2f2;
    text-align-last: left;
}

.left-container{
    width: fit-content;
    display: inline;
    float:left
}

.others{
    height: 2rem;
    width: 98.8vw;
    border-bottom: 1px solid #dadce0;
    font-size: 15px;
    padding: 1rem 0rem 0 1rem;
    font-family: arial,sans-serif;
    color: #6f6f6f;
    background-color: #f2f2f2;
}

.others a{
    padding:15px;
    color:#6f6f6f !important;
    text-decoration: none !important;
}

.others a:hover{
    text-decoration: underline;
}

.right-container{
    float:right;
    width: fit-content;
}
</style>