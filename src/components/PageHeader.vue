<template>
    <header>
        <div class="container">

            <div class="logo">
                <img src="../assets/dc-logo.png" alt="DC logo">
            </div>

            <ul class="menu">

                <li v-for="link, index in menuLinks" :key="index" 
                    :class="{ 'current': link.current }">

                    <a :href="link.url">{{ link.text }}</a>
                    
                </li>
            </ul>

        </div>
    </header>
</template>

<script>
export default {
  name: '<PageHeader/>',
  data() {
        return {
            menuLinks: [
                {
                    text: 'CHARACTERS',
                    url: '#',
                    current: false
                },
                {
                    text: 'COMICS',
                    url: '#',
                    current: true
                },
                {
                    text: 'MOVIES',
                    url: '#',
                    current: false
                },
                {
                    text: 'TV',
                    url: '#',
                    current: false
                },
                {
                    text: 'GAMES',
                    url: '#',
                    current: false
                },
                {
                    text: 'COLLECTIBLES',
                    url: '#',
                    current: false
                },
                {
                    text: 'VIDEOS',
                    url: '#',
                    current: false
                },
                {
                    text: 'FANS',
                    url: '#',
                    current: false
                },
                {
                    text: 'NEWS',
                    url: '#',
                    current: false
                },
                {
                    text: 'SHOP',
                    url: '#',
                    current: false
                }
            ],
        };
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    header{

        .container{
        background-color: white;
        margin: 0 auto;
        width: 70%;
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-content: center;
        // padding: 15px 0;
        }

        .logo img{
            width: 55px;
            padding: 15px 0;
        }

        .menu {
            width: 60%;
            display: flex;
            justify-content: space-evenly;
            align-items: center;

            li{
            // padding: 0 10px;
            height: 100%;
            display: flex;
            align-items: center;

                a{
                font-size: 10px;
                font-weight: 600;
                }

                &.current{
                    box-shadow: 0 -5px #0084f9 inset;
                    color: #0084f9;
                }

            }
        }

        
    }
</style>
