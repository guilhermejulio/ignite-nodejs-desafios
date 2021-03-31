<h1 align="center">
    <img alt="Ignite" src="../.github/Ignite_background.png" />
</h1>

<h3 align="center">
  Desafio 3 - Corrigindo Código
</h3>

<p align="center">Código do terceiro desafio Capitulo I do <a href="https://rocketseat.com.br/bootcamp">Bootcamp Ignite</a> 🎓</p>

<p align="center">
  <a href="#rocket-sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#space_invader-conceitos-aplicados">Conceitos aplicados</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>

  <p align="center">Desafio solucionado! 27/03/2021 🚀 Done :heavy_check_mark:</p>	
	
</p>

<br/>

## :rocket: Sobre o desafio


<br>
<p>

Nesse desafio, temos uma aplicação Node.js que está em processo de desenvolvimento mas que já possui os testes necessários para fazer toda a validação dos requisitos (você não deve mexer nos testes).
Após algumas alterações no código da aplicação, parte dos testes deixaram de passar e agora só você pode resolver esse problema. Bora lá? 🚀

Essa aplicação realiza o CRUD (**C**reate, **R**ead, **U**pdate, **D**elete) de repositórios de projetos. Além disso, é possível dar likes em repositórios cadastrados, aumentando a quantidade de likes em 1 a cada vez que a rota é chamada.

A estrutura de um repositório ao ser criado é a seguinte: 

```json
{
  id: uuid(),
  title,
  url,
  techs,
  likes: 0
}
```

Descrição de cada propriedade:

- **id** deve ser um uuid válido;
- **title** é o título do repositório (por exemplo "unform");
- **url** é a URL que aponta para o repositório (por exemplo "[https://github.com/unform/unform](https://github.com/unform/unform)");
- **techs** é um array onde cada elemento deve ser uma string com o nome de uma tecnologia relacionada ao repositório (por exemplo: ["react", "react-native", "form"]);
- **likes** é a quantidade de likes que o repositório recebeu (e que vai ser incrementada de 1 em 1 a cada chamada na rota de likes).

Note que a quantidade de likes deve sempre ser zero no momento de criação.

<br>

O enunciado completo do desafio pode ser acessado no [Notion atráves deste Link.](https://www.notion.so/igniteguilhermejulio/Desafio-3-9e7f8d4f5d3345cdb1bd2dd8b92d8937)

</p>

<br>

## :space_invader: Conceitos Aplicados

- [X] Análise de código
- [X] Procura por Bugs
- [X] Middlewares
- [X] Correção de código para o funcionamento correto
- [X] Usado a função `hasOwnProperty` para verificar se um objeto contém uma propriedade

  
<br>

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

Imagens usadas provenientes da Rocketseat.


---


Feito com 💜 por Guilherme Julio

