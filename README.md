# Consumo-de-API-RAWG.IO
Este repositório contém códigos em linguagem html, css e javascript para o consumo de uma API de jogos chamada rawg.io

Iniciamos o consumo da API estudando sua documentação que se encontra no link: https://rawg.io/apidocs;
Após estudar a Api desenvolvi o código da página na linguaguem html para estruturar todo o conteúdo e utilizei o código de css para estilizar a página, acrescentando cores e efeitos para ficar algo sugestivo para o usuário.
Logo após desenvolver todo o esqueleto e estilização do site, iniciei o consumo da API na linguagem JavaScript criando uma função assincrona que chama o link da API e peguei o json da mesma. Dessa forma eu pude extrair os dados desejados da API como imagem, nome, e plataformas em que os jogos estão disponíveis como: playstation, xbox e pc. Com a função assincrona pronta eu desenvolvi outra função async para exibir os dados coletados da API, dessa forma alguns jogos mais populares são exibidos assim que a página é carregada.

Para a interação com o usuário utilizei a barra de pesquisa em que o usuário digita o nome do jogo de deseja e dessa forma as informações do mesmo são exibidas. Tudo isso foi possivel após novamente criar uma função async chamar o link da api e concatenar com o que o usuário digitou, extraí todas as informações como imagem, nome, plataforma disponivel e data de lançamento dos jogos. Em seguida criei uma função para exibir todas as informações obtidas anteriormente, desta vez inseri um código para limpar o html e exibir apenas os jogos com o nome cujo usuário digitou.

Esta atividade foi desenvolvida com objetivo de completar a atividade da matéria de PWFE - Programação Web Front-End com o professor Fernando Leonid que leciona atualmente no curso Técnico de Informática de Desenvolvimento de Sistemas no SENAI de Jandira

Atividade referente ao segundo semestre do curso.
