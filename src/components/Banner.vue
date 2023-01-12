<template>
    <div id="main-banner" :style="image">
        <h2>Invista em viver.</h2>
        <h2>Investir toma tempo, mas não precisa ser o seu.</h2>
        <h3>Consulte nossos especialistas.</h3>
        <button>Saiba mais</button>
    </div>
</template>

<script>
export default {
    name:"Banner",
    data() {
        return {
            image: {
                backgroundImage: 'url(/img/banner.jpg)'
            }
        }
    }
}
</script>

<style scoped>

    ul {
    list-style-type: none;
    }

    #main-banner {
        height: 550px;
        display: flex;
        flex-direction: column;
        justify-content: flex-start;
        color: #fff;
        padding: 140px 140px;
        background-position: 0 -250px;
        background-size: cover;
    }

    h2 {
        font-size: 50px;
        color: #fff;
    }

    h3 {
        font-size: 20px;
        margin-top: 35px;
        margin-bottom: 35px;
    }

    button {
    padding: 10px 15px;
    border-radius: 16px;
    width: 130px;
    border: none;
    background-color: #222;
    color: white;
    cursor: pointer;
    font-size: 14px;
    font-weight: 400;
    }

    button:hover{
    background-color: white;
    color: rgb(199, 19, 73)
    }
</style>