<template>
    <div class="search">
        <span class="magnifyIcon"><magnify-icon/></span>
        <input type="text" class="searchTerm">
        <button type="submit" class="keyboardButton">
            <keyboard-icon/>
        </button>
    </div>
</template>

<script>
    import MagnifyIcon from 'vue-material-design-icons/Magnify.vue'
    import KeyboardIcon from 'vue-material-design-icons/Keyboard.vue'
    export default {
        name: 'SearchComponent',
        components: {
            MagnifyIcon,
            KeyboardIcon
        }
    }
</script>

<style>
.search {
    width: 100%;
    position: relative;
    display: flex;
    place-content: center;
    margin-top: 1.5rem;
}

.magnifyIcon{
    width: 48px;
    height: 45px;
    border: 1px solid #D3D3D3;
    background: white;
    text-align: center;
    color: #808080;
    border-radius: 22px 0 0 22px;
    cursor: pointer;
    font-size: 1.1rem;
    border-right: none;
}

.material-design-icon__svg{
    margin-top: 0.7rem;
}

.searchTerm {
    width: 30rem;
    border: 1px solid #D3D3D3;
    border-right: none;
    padding: 5px;
    height: 35px;
    outline: none;
    color: #9DBFAF;
    border-left: none;
    color: black;
    font-size: 1rem;
}

.keyboardButton {
    width: 48px;
    height: 47px;
    border: 1px solid #D3D3D3;
    background: white;
    text-align: center;
    color: #808080;
    border-radius: 0 22px 22px 0;
    cursor: pointer;
    font-size: 1.1rem;
    border-left: none;
}

.keyboardButton:focus{
    outline: none;
}
</style>