<template>
    <div id="section">
        <div id="parts">
            <img src="/img/imageOne.jpg" id="images"/>
            <div id="first-texts">
                <h2>Investir nunca foi tão fácil</h2>
                <h3>Facilitamos seu investimento, para que você possa investir em viver.</h3>
                <h3>Organize-se por objetivos: estabeleça suas metas nas carteiras 
                    personalizadas para cada momento da sua vida.</h3>
                <h3>Facilidade digital com apoio humano: acompanhe a evolução 
                    das suas carteiras no celular e fale com especialistas quando precisar.</h3>
                <button>Comece agora</button>
            </div>
        </div>
        <div id="parts">
            <div id="second-texts">
                <h2>Investir nunca foi tão fácil</h2>
                <h3>Organize-se por objetivos: estabeleça suas metas nas carteiras 
                    personalizadas para cada momento da sua vida.</h3>
                <hr class="solid" />
                <h3>Facilidade digital com apoio humano: acompanhe a evolução 
                    das suas carteiras no celular e fale com especialistas quando precisar.</h3>
                <button>Comece agora</button>
            </div>
            <img src="/img/imageThree.jpg" id="images"/>
        </div>
    </div>
</template>

<script>
export default {
    name: "SectionOne",
}
</script>

<style scoped>

    #section {
        padding: 140px 140px;
    }

    #parts {
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: space-between;
        padding: 50px 0px;
    }

    #images {
        height: 460px;
        width: 490px;
        background-size: contain;
    }     
    
    #first-texts {
        color: #222;
        text-align: justify;
        margin-left: 80px;
    }

    #second-texts {
        color: #222;
        text-align: justify;
        margin-right: 80px;
    }
    
    h2 {
        margin-bottom: 35px;
    }

    h3 {
        margin-top: 25px;
    }

    button {
        padding: 5px 15px;
        margin-top: 40px;
        border-radius: 16px;
        border: none;
        background-color: rgb(199, 19, 73);
        color: #FFF;
        cursor: pointer;
        font-weight: 500;
    }

    button:hover{
        background-color: #222;
    }

    hr.solid {
        border-top: 1.5px solid rgb(199, 19, 73);
        margin-top: 20px;
    }

</style>