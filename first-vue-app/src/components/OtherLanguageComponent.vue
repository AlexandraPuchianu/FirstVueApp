<template>
    <div class="otherLanguage">
        <p>Google oferit în: 
            <a href="https://www.google.com/setprefs?sig=0_9RzuavNzVCjYRMlgzdaQhXKMZs8%3D&hl=hu&source=homepage&sa=X&ved=0ahUKEwiDtZKY5ZPwAhUiyYUKHXrOA-kQ2ZgBCA0">Magyar</a>
            <a href="https://www.google.com/setprefs?sig=0_9RzuavNzVCjYRMlgzdaQhXKMZs8%3D&hl=de&source=homepage&sa=X&ved=0ahUKEwiDtZKY5ZPwAhUiyYUKHXrOA-kQ2ZgBCA4">Deutsch</a>
            <a href="https://www.google.com/setprefs?sig=0_YEfyuLzJtrXlIMMoc-5fsK1jz6k%3D&hl=en&source=homepage&sa=X&ved=0ahUKEwiQoc3M5ZPwAhVRUhoKHTlABNIQ2ZgBCBA">English</a>
        </p>
    </div>
</template>

<script>
    export default {
        name: 'OtherLanguageComponent'
    }
</script>

<style>
.otherLanguage{
    font-size: 14px;
    font-family: arial,sans-serif;
    display: inline-flex;
    width: 100%;
    justify-content: center;
    margin-top: 1rem;
}

.otherLanguage a{
    text-decoration: none;
    margin-left: 0.4rem;
}
</style>