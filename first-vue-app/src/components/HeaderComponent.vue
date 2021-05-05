<template>
    <div class="header">
        <div class="links">
            <a id="gmailLink" href="https://www.google.com/intl/ro/gmail/about/#" target="_top">Gmail</a>
            <a id="imaginiLink" href="https://www.google.ro/imghp?hl=ro&ogbl" target="_top">Imagini</a>
        </div>
        <div class="menu">
            <a id="menuButton" role="button"><menu-icon/></a>
        </div>
        <div class="connectButton">
            <a href="https://accounts.google.com/signin/v2/identifier?hl=ro&passive=true&continue=https%3A%2F%2Fwww.google.com%2F&ec=GAZAmgQ&flowName=GlifWebSignIn&flowEntry=ServiceLogin"><button class="button">Conectați-vă</button></a>
        </div>
    </div>
</template>

<script>
    import MenuIcon from 'vue-material-design-icons/Menu.vue'
 
    export default {
        name: 'HeaderComponent',
        components: {
            MenuIcon
        }
    }
</script>

<style>
.header{
    height: 2rem;
    width: 100%;
    position: relative;
    float: right;
    display: inline-flex;
    align-items: baseline;
    justify-content: flex-end;
    padding: 0.3rem;
    padding-right: 0.5rem;
}
.header a{
    text-decoration: none;
    margin-left: 0.8rem;
    font-family: arial,sans-serif;
    color: black;
    font-size: 13px;
}

.links a :hover{
    border-bottom: 1px solid black;
}

.menu a{
    border-radius: 50%;
    margin-left: 2rem;
}

.button {
    background-color: #1a73e8;
    border: none;
    color: white;
    margin-left: 0.7rem;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 14px;
    cursor: pointer;
    height: 2.3rem;
    padding-left: 1.5rem;
    padding-right: 1.5rem;
    border-radius: 4px;
}
</style>