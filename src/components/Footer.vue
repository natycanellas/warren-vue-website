<template>
    <footer id="footer">
        <div>
            <ul>
                <h2>Sobre</h2>
                <li><a>História da Warren</a></li>
                <li><a>Warren Brasil</a></li>
                <li><a>Warren Tech Academy</a></li>
            </ul>
        </div>
        <div>
            <ul>
                <h2>Investir</h2>
                <li><a>Investimentos</a></li>
                <li><a>Bolsa de Valores</a></li>
                <li><a>Cripto Moedas</a></li>
            </ul>
        </div>
        <div>
            <ul>
                <h2>Aprender</h2>
                <li><a>Desintoxicação</a></li>
                <li><a>Desenrola</a></li>
                <li><a>Warren Edu</a></li>
            </ul>
        </div>
        <div>
            <ul>
                <h2>Fale Conosco</h2>
                <li><a>Dúvidas</a></li>
                <li><a>Precisa de ajuda?</a></li>
                <li><a>Acesse o Chat</a></li>
            </ul>
        </div>
    </footer>
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style scoped>
    #footer {
        height: 250px;
        background-color: #222;
        border-top: 1px solid  #111;
        color: white;
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: 0 100px;
        width: 100%;
    }

    ul {
    list-style-type: none;
    }

    h2 {
    margin-bottom: 15px;
    }
</style>