# Go: A Revolução da Concorrência

Um site desenvolvido para apresentar e defender a linguagem Go como a melhor solução para programação multithreading e concorrência.

## Objetivo

Este projeto demonstra por que Go revolucionou a programação concorrente, contrastando os problemas das abordagens tradicionais (threads pesadas, deadlocks, race conditions) com as soluções elegantes oferecidas por goroutines, channels e o modelo de concorrência do Go.

## Características

- Comparação visual entre código C++ complexo e Go simplificado
- Benchmarks de performance: goroutines vs threads tradicionais
- Casos reais de empresas como Docker, Kubernetes, Uber e Twitch
- Interface responsiva com animações modernas
- Explicações técnicas de goroutines, channels, select e context

## Tecnologias

- HTML5, CSS3, JavaScript
- Tailwind CSS para estilização
- Google Fonts (Inter)

## Como Executar

1. Clone o repositório
2. Abra o arquivo `index.html` em qualquer navegador

Ou use um servidor local:
```bash
python -m http.server 8000
```

## Principais Estatísticas contidas no nosso site

- Goroutines são 1000x mais leves que threads tradicionais
- Stack inicial de apenas 2KB vs 2-8MB de threads OS
- Suporte a milhões de goroutines simultâneas
- Tempo de criação: ~200ns vs 1-2ms de threads Java

## Contexto

Desenvolvido como projeto da disciplina Conceitos de Linguagens de Programação, com objetivo de apresentar uma linguagem de forma persuasiva e técnica, destacando suas vantagens para multithreading.

