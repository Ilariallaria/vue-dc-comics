<template>
    <header>
        <div class="container">

            <div class="logo">
                <img src="../assets/dc-logo.png" alt="DC logo">
            </div>

            <ul class="menu">
>
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
        height: 80px;


        .container{
        background-color: white;
        margin: 0 auto;
        width: 70%;
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-content: center;
        padding: 15px 0;
        }

        .logo img{
            width: 55px;
        }

        .menu {
            display: flex;
            justify-content: center;
            align-items: center;

            li{
            padding: 0 10px;

                a{
                font-size: 10px;
                font-weight: 600;
                }

                &.current{
                    border-bottom: 1px solid #0084f9;
                }

            }
        }

        
    }
</style>
