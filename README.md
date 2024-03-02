# pagina-basic

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pagina</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="margin">
        <h1>Animales</h1>
    </div>

    <p class="texto">los animales son seres vivos dotados de movimiento propio y autónomo, de un metabolismo basado en la respiración y de un sistema 
        nervioso que les permite interactuar con su entorno</p>
    <br>
    
    <h2>Tipos de Animales:</h2>
    <br>

    <h2>Leon</h2>

    <div class="contenedor">
        <p>
            es el segundo felino viviente más corpulento después del tigre. Con unas patas potentes, 
            una fuerte mandíbula y unos colmillos de ocho centímetros.
        </p>
        <a target="_blank" href="https://es.wikipedia.org/wiki/Panthera_leo">
            <img  class="imagen" src="leon.jpg" alt="">
        </a>
    </div>

        <h2>Elefante</h2>

        <div class="contenedor-2">
            <p>
                Es el mamífero más grande de la tierra puede pesar hasta ocho toneladas y mide 3 metros de alto por 7 de largo.
                Con grandes orejas en forma de abanico y una larga trompa.
            </p>
            <a target="_blank" href="https://www.worldwildlife.org/descubre-wwf/historias/elefante">
                <img class="imagen" src="Elefante.jpg" alt="">
            </a>
        </div>

        <h2>Gorila</h2>

        <div class="contenedor-3">
            <p>
                Un gorila es un animal mamífero que forma parte del grupo de los primates. Vive en el continente africano, 
                puede medir hasta dos metros de altura y se caracteriza por presentar los brazos mucho más largos que sus piernas.
            </p>
            <a target="_blank" href="https://www.worldwildlife.org/descubre-wwf/historias/gorila">
                <img class="imagen" src="gorila.jpg" alt="">
            </a>
        </div>
        <br>

    <table>
        <tr>
            <th>Animales</th>
            <th>familia</th>
        </tr>
        <tr>
            <td>Leon</td>
            <td>Felinos</td>
        </tr>
        <tr>
            <td>elefante</td>
            <td>mamíferos</td>
        </tr>
        <tr>
            <td>Gorila</td>
            <td>Homínidos</td>
        </tr>
    </table>

    
</body>
</html>





#css


body{
    background-color: rgb(201, 201, 201);
}



.margin{
    color: #eee;
    text-align: center;
    border-style: outset;
    border-radius:  20px ;
    border-color: rgb(0, 0, 0);
    border-width: 5px;
    background-color: #dd6060;
    text-shadow: 7px 4px 5px rgb(0, 0, 0)
    


}

.texto{
    text-align: left;
    color: darkslateblue;
    font-family: cursive;
    font-size: medium;

    
}


h2{
    color: blueviolet;
    font-size: medium;
    font-family: cursive;
}

.texto1{
    font-size: medium;
    font-family: cursive;
    
    
}

.contenedor {
    font-size: medium;
    font-family: cursive; 
    

}

.imagen{
    width:  200px;
    border-radius: 6px;
    border-style: groove;
    color: azure;
    


    
}

.contenedor-2{
    font-size: medium;
    font-family: cursive;

}


.contenedor-3{
    font-size: medium;
    font-family: cursive;

}




table{
    
    width: 60%;
    border-collapse: collapse;
}

th, td{
    border: solid 1px #eee;
    padding: 4px;
    padding-bottom: 3px;
    
    
    
}

th{
    background-color: rgb(243, 204, 99);
    color: rgb(255, 255, 255);
    text-align: left;
    
    

}

td{
    background-color: rgb(237, 217, 189);
    padding-left: 6px;

}

tr:nth-child(even) {
    background-color: #eee;
