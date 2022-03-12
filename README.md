## DSMovie
![Badge Concluído](http://img.shields.io/static/v1?label=STATUS&message=CONCLUÍDO&color=GREEN&style=for-the-badge)
![Badge Java](http://img.shields.io/static/v1?label=JAVA&message=11.0.13&color=yellow&style=for-the-badge)
![Badge Spring](http://img.shields.io/static/v1?label=SPRING&message=2.6.2&color=GREEN&style=for-the-badge)
![Badge PostgreSQL](http://img.shields.io/static/v1?label=POSTGRESQL&message=13.4&color=blue&style=for-the-badge)

<p align="center">
  <img src="https://user-images.githubusercontent.com/48693812/158029327-d2ffd7b2-d913-4602-8d80-ed6637f412eb.svg" />
</p>


## Índice 

* [Índice](#índice)
* [Descrição do Projeto](#descrição-do-projeto)
* [Funcionalidades](#funcionalidades)
* [Métodos](#métodos)
* [Pessoas Desenvolvedoras do Projeto](#pessoas-desenvolvedoras)
* [Conclusão](#conclusão)

## Descrição do Projeto
DSMovie é uma API Rest para avaliação de Filmes desenvolvido na semana Spring-React elaborada pela escola <a href="https://devsuperior.com.br/">Dev Superior</a> . 

A aplicação tem backend e frontend integrados e disponíveis para uso no Netlify. Através do Link: <a href="https://yan-dsmovie.netlify.app/">https://yan-dsmovie.netlify.app/</a> 

## Funcionalidades
As funcionalidades foram divididas por [Movies](#movies) e [Score](#score).

Os Filmes disponíveis podem ser avaliados inserindo um e-mail e uma nota dentro de un formulário.

### Movies
* [/movies]
  * [Listar Filmes](#listar-filme)
  * [Detalhar Filme](#detalhar-filme)

### Score
* [/scores]
  * [Cadastrar Avaliação](#cadastrar-avaliação)

## Métodos
&emsp;&emsp; As requisições para a API devem seguir os padrões:

<center>
  
| Método   | Descrição                                             |
|:---------|-------------------------------------------------------|
| `GET`    | Retorna informações de um ou mais registros.          |
| `PUT`    | Atualiza dados de um registro ou altera sua situação. |

</center>


### Listar Filmes
* Método HTTP
  * GET
* API Endpoint
  * movies
* Response 200 (application/json)
  ```json
  [
    {
        "id": "Id do filme.",
        "title": "Título do Filme.",
        "score": "Pontuação da avaliação do filme.",
        "count": "Quantidade de avaliações.",
        "image": "Imagem do Filme."       
    },
    {
        "id": "Id do filme.",
        "title": "Título do Filme.",
        "score": "Pontuação da avaliação do filme.",
        "count": "Quantidade de avaliações.",
        "image": "Imagem do Filme."       
    }
  ]
  ```

### Detalhar Filme
* Método HTTP
  * GET
* API Endpoint
  * movies/{id}
* Response 200 (application/json)
  ```json
    {
        "id": "Id do filme.",
        "title": "Título do Filme.",
        "score": "Pontuação da avaliação do filme.",
        "count": "Quantidade de avaliações.",
        "image": "Imagem do Filme."        
    }
  ```

### Cadastrar Avaliação
* Método HTTP
  * PUT
* API Endpoint
  * scores
* Response 200 (application/json)
  ```json
    {
      "movieId": "Id do filme",
      "email": "Email do usuário",
      "score": "Pontuação da avaliação do filme."
    }
  ```

### Pessoas Desenvolvedoras

[<p align="center"><img src="https://avatars.githubusercontent.com/u/48693812?s=400&u=e3b46f180b450fc7e0bdc65bbbf68e4a77f8d121&v=4" width=115 ><br><sub>Yan Andrade de Sena</sub>](https://github.com/yandrade1305)</p>

### Conclusão

Diversas vezes, quando utilizava o YouTube aparecia a propaganda da semana Spring-React, tinha acabado de entregar outro projeto pro meu portfólio, que é o projeto <a href="https://github.com/yandrade1305/miltankbank">Miltankbank</a>, mas, apesar disso, optei por fazer essa capacitação.

E que decisão incrível que tomei! Eu me surpreendi com os conteúdos e a forma como ele foi passado, aprendi muitas coisas. Por exemplo publicar o projeto no <a href="https://dashboard.heroku.com/">Heroku</a> e no <a href="https://www.netlify.com/">Netlify</a>. 

Gostei demais dos vídeos disponibilizados, da <a href="https://github.com/devsuperior/sds-dsmovie">página de apoio no Github</a>, da organização geral do evento e o resultado foi muito satisfatório.

Agradeço imensamente a equipe do <a href="https://devsuperior.com.br/">Dev Superior</a> e especialmente ao <a href="https://www.linkedin.com/in/nelio-alves/">Nelio Alves</a>, é um ótimo professor explica super bem e nossa como fiquei com vontade de assinar o Dev Superior.
