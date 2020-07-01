# Desafio Front-end do Agenda Edu


## Introdução

Estamos muito felizes que você tenha chegado nessa etapa do nosso processo seletivo! Para essa fase desejamos que você resolva um desafio básico.


## Desafio

Nosso líder técnico Renan Gurgel deseja usar uma aplicação que liste os filmes mais populares do momento, para isso você deverá consumir a **API** do [TheMovieDB][tmdb-api-url], para essa aplicação será necessário na tela inicial mostrar uma listagem dos filmes mais populares, os mais populares sendo exibidos no topo da lista, utilizar o mecanismo de paginação fornecido pela **API**.

Cada item da lista deve levar para uma página de detalhes do filme, aonde deve ser mostrado todos os atributos importantes do filme, como por exemplo: `title`, `description`, `rating`, `etc`.

Deve ser possível realizar pesquisa por filmes em qualquer tela, a request de pesquisa deve ser disparada utilizando o processo de controle de fluxo **Debounce​** com um limite de tempo de **500ms**, esse controle deve ser feito devido ao limite de requests por segundo que a **API** impõe.

Sobre a limitação de requests por segundo da **API** do [TheMovieDB][tmdb-api-url], esse limite deve ser tratado e deve ser exibido um feedback visual não invasivo para o usuário indicando que não foi possível realizar a operação devido a limitação da **API** e solicite que ele tente novamente em alguns segundos.


## Requisitos

- Use React
- Necessário o uso de rotas


## Requisitos bônus

**Esses requisitos não são obrigatórios, mas serão levados em consideração como pontos extras no momento da avaliação.**

- Boa qualidade de UI/UX
- Usar Redux.
- Baixo tempo de renderização
- Renderização de listas on-demand, e.g: Dado que a lista tem 100 items, não renderizar a lista completa, renderizar apenas os items visíveis na tela e alguns extras para evitar engasgos de scroll.
- Testes unitários e.g: [Jest][jest-url]


## Critérios de avaliação

- Organização do projeto: Avalia a estrutura do projeto, documentação e uso de controle de versão;
- Inovação tecnológica: Avalia o uso de tecnologias mais recentes, desde que estáveis;
- Coerência: Avalia se os requisitos foram atendidos;
- Boas práticas: Avalia se o projeto segue boas práticas de desenvolvimento, incluindo segurança e otimização;
- Controle de Qualidade: Avalia se o projeto possui qualidade assegurada por testes (por exemplo [Jest][jest-url]).


## Processo de submissão

O desafio deve ser entregue pelo [GitHub][github-url].

Qualquer dúvida em relação ao desafio, responderemos por e-mail.

Bom trabalho!

[tmdb-api-url]: https://www.themoviedb.org/documentation/api
[reactjs-url]: https://reactjs.org/
[jest-url]: https://facebook.github.io/jest/
[github-url]: https://github.com