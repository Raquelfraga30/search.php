<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pesquisa produtos</title>
</head>
<body>
    <form action="#" method="get">
        <input type="search" name="search" placeholder="Pesquisar produto...">
        <input type="submit" value="Pesquisar">
    </form>
    <br>
    <?php
        //testando se a variável $search é null
        echo ($search != null) ? searchProduct($search) : "Digite um termo para pesquisa";
    ?>
</body>
</html>
