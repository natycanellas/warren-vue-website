<template>
    <div id="section-two" :style="image">
        <h2>Investir é sobre você</h2>
        <button>Abra já sua conta</button>
    </div>
</template>

<script>
export default {
    name:"SectionTwo",
    data() {
        return {
            image: {
                backgroundImage: 'url(/img/imageTwo.png)'
            }
        }
    }
}
</script>

<style scoped>

    #section-two {
        height: 350px;
        display: flex;
        justify-content: space-between;
        color: #fff;
        padding: 140px 140px;
        align-items: center ;
        background-position: 0 -250px;
        background-size: cover;
    }

    h2 {
        color: #fff;
        font-size: 50px;
    }

    button {
    padding: 10px 15px;
    border-radius: 16px;
    width: 170px;
    border: none;
    background-color: #FFF;
    color: #222;
    cursor: pointer;
    font-size: 15px;
    font-weight: 500;
    }

    button:hover{
    background-color: rgb(199, 19, 73);
    color: #FFF;
    }

</style>