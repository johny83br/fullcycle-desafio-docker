# Desafio Full Cycle com Go e Docker

O desafio consiste em criar uma aplicação simples em Go (Golang) que, ao ser executada dentro de um container Docker, exiba a mensagem:
`Full Cycle Rocks!!`

Após desenvolver o código, o participante deve:

- Gerar uma imagem Docker contendo o programa Go.

- Publicar a imagem no Docker Hub.

- Garantir que, ao executar o comando `docker run johny83br/fullcycle`, o resultado exibido seja exatamente a mensagem esperada.

- Manter a imagem com menos de 2MB, o que exige o uso de estratégias de otimização — como multi-stage builds e imagens base minimalistas (ex: scratch).

- Subir o código em um repositório Git remoto e compartilhar o link junto com o endereço da imagem no Docker Hub.

- O desafio tem como objetivo exercitar conhecimentos em Go, Docker, e otimização de imagens, incentivando a prática com containers leves e eficientes.

## Imagem do Docker
[https://hub.docker.com/r/johny83br/fullcycle](https://hub.docker.com/r/johny83br/fullcycle)