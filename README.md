# Exemplo de Requisição de Hora com WorldTimeAPI

Este projeto é uma página HTML simples que demonstra como fazer uma requisição assíncrona (AJAX) para a API `worldtimeapi.org` e exibir a hora atual de uma localização específica. O objetivo é mostrar a integração de JavaScript com uma API externa para buscar dados em tempo real.

---

## O Que a Página Faz

A página carrega e, em seguida, usa JavaScript para se conectar à API do WorldTimeAPI.org. Ela busca a hora atual da localização configurada (por padrão, **America/Sao_Paulo**) e exibe-a de forma formatada.

---

## Tecnologias Utilizadas

* **HTML:** Para a estrutura e marcação da página.
* **CSS:** Para a estilização básica da interface.
* **JavaScript:** Para fazer a requisição à API e manipular o DOM para exibir a hora.

---

## Como Acessar

Você pode visualizar a página diretamente no seu navegador. Basta abrir o arquivo `index.html`.

[**Clique aqui para abrir a página de demonstração**](https://github.com/sheysson/vscode/tree/main/doc/index.html)

**Observação:** O link acima funcionará apenas se você tiver o arquivo `index.html` na mesma pasta que este `README.md`.

---

## Como Funciona

O arquivo `script.js` contém a lógica principal:

1.  Ele utiliza a função `fetch()` do JavaScript para enviar uma requisição GET para a URL da API (`http://worldtimeapi.org/api/timezone/America/Sao_Paulo`).
2.  Após receber a resposta da API, ele converte os dados JSON.
3.  Em seguida, ele extrai a data e a hora do objeto retornado.
4.  Por fim, ele insere a hora formatada em um elemento HTML na página.

A requisição é feita toda vez que a página é carregada, garantindo que a hora exibida esteja sempre atualizada.

---

## Estrutura do Projeto