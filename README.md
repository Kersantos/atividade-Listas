# atividade-Listas
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Atividade de Listas</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Minhas listas favoritas</h1>
    <h2>Lista de bom comportamentos</h2>
    <ol type="I">
        <li>Cumprimentar a todos que conhecer</li>
        <li>Respeitar os mais velhos</li>
        <li>Não interromper diálogos</li>
        <li>Agradecer sempre que necessário</li>
        <li>Desculpar-se</li>
    </ol>
    <h2>Lista de emojis preferidos</h2>
    <ul>
        <li>&#128512</li>
        <li>&#128513</li>
        <li>&#128514</li>
        <li>&#128525</li>
        <li>&#128527</li>
    </ul>
    <h2>Lista das Placas de trânsito e Seus Significados</h2>
    <ul>
        <li><img src="imagens/placaSP.webp" alt="Placa de Sentido proibido">placa de trânsito Sentido Proibido</li> 
        <li><img src="imagens/placaL.jpg" alt="Placa de Lombada" >placa de lombada</li>
        <li><img src="imagens/placaCP.webp.crdownload" alt="Placa de circulação de pedestres">placa de circulação de pedestres</li>
        <li><img src="imagens/placaMD.webp" alt="Placa de advertência mão dupla adiante">placa de advertência mão dupla adiante</li>
    </ul>
    <h2>Lista de Livro</h2>
    <div><ul type="None" class="first">
        <li>Sumário</li>
    </ul>
    <ul type="None" class="second">
        <li>APRESENTAÇÃO................................................................................... 11</li>
        <li>PREFÁCIO............................................................................................... 13</li>
        <ol>
            <li>INTRODUÇÃO À INFORMÁTICA: HISTÓRICO E EVOLUÇÃO. 15</li>
            <ol>
                <li>1 Histórico.............................................................................. 15</li>
                <li>2 Fundamentos e Classificação.............................................. 17</li>
                <ul type="None">
                    <li>1.2.1 O que é informática?............................................ 17</li>
                    <li>1.2.2 O que é computador?.......................................... 18</li>
                    <li>1.2.3 Características fundamentais do computador.. 18</li>
                    <li>1.2.4 Vantagens do uso do computador........................ 18</li>
                    <li>1.2.5 Tipos de computadores........................................ 19</li>
                    <li>1.2.6 Classificação quanto à utilização........................ 19</li>
                </ul>
                <li>3 Gerações de Computadores................................................  10</li>
                <li>4 Aplicações de Computadores.............................................. 20</li>
                <ul type="None">
                    <li>EXERCÍCIOS DE FIXAÇÃO..................................... 21</li>
                    <li>BIBLIOTECA CONSULTADA................................... 22</li>
                </ul>
            </ol>
        </ol>
    </ul>
    </div>
</body>
</html>

body{
    background-color: rgb(241, 240, 243);
    line-height: 2;
}
img{
    height: 100px;
    width: 130px;
}
ul.first{
    color: rgb(54, 199, 25);
    font-weight: bold;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-size: 17px;
}
ul.second{
    font-weight: bold;
}
div{
    background: rgb(253, 251, 251);
    color: #0a0808;
    width: 600px;
    height: 600px;
}
