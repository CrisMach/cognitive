<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span> Laboratório Buscas Cognitivas (Cognitive Search) </span>
</h1>

Repositório desenvolvido para comentar sobre a conclusão deste laboratório.

## Objetivo
Demonstrar a experiência com o serviço

---
## Descrição das etapas e comentários
De forma bastante resumida, os passos demonstrados no laboratório ![alt text](https://web.dio.me/lab/azure-cognitive-search-utilizando-ai-search-para-indexacao-e-consulta-de-dados/learning/dc177426-0df3-48d0-804d-03118ca4c541?back=/track/microsoft-fundamentos-de-ia) 


## Sentiment and opinion mining tryout
01 ![alt text](https://github.com/CrisMach/analisesentimentos/blob/main/inputs/LS-01.png?raw=true)

Observação: Em uma frase simples como esta o serviço avaliou com 100% de confiança que o sentimento é positivo, sem demonstrar a segmentação das palavras chave

02 ![alt text](https://github.com/CrisMach/analisesentimentos/blob/main/inputs/LS-02.png?raw=true)

Observação: Neste exemplo temos a palavra odeio como Assessment e abacaxi comotarget, onde não ficoou totalmente claro o motivo pelo qual o "Document Sentiment" apresenta 1% positivo 1% Neutro e 99% Negativo, entendo que a soma apresentada deveria totalizar 100% (farei um post na comunidade).

03 ![alt text](https://github.com/CrisMach/analisesentimentos/blob/main/inputs/LS-03.png?raw=true)

Observação: Neste exemplo o PC como target e a palavra Caro como assessment deram 99% de confiança sobre a negatividade da opinião, e 75% sobre o sentimento negativo para o documento.
