<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span> Laboratório Análise de Sentimentos e Opiniões com Language Studio </span>
</h1>

Repositório desenvolvido para mostrar a experiência com a análise de sentimentos do Language Studio.

## Objetivo
Demonstrar a experiência com o serviço

---
## Descrição das etapas e comentários
Foram criadas 4 frases e analisadas afim de idenfificar o nível de confiança do serviço para cada uma delas e entender o processo de análise:


## Sentiment and opinion mining tryout
01 ![alt text](https://github.com/CrisMach/analisesentimentos/blob/main/inputs/LS-01.png?raw=true)

Observação: Em uma frase simples como esta o serviço avaliou com 100% de confiança que o sentimento é positivo, sem demonstrar a segmentação das palavras chave

02 ![alt text](https://github.com/CrisMach/analisesentimentos/blob/main/inputs/LS-02.png?raw=true)

Observação: Neste exemplo temos a palavra odeio como Assessment e abacaxi comotarget, onde não ficoou totalmente claro o motivo pelo qual o "Document Sentiment" apresenta 1% positivo 1% Neutro e 99% Negativo, entendo que a soma apresentada deveria totalizar 100% (farei um post na comunidade).

03 ![alt text](https://github.com/CrisMach/analisesentimentos/blob/main/inputs/LS-03.png?raw=true)

Observação: Neste exemplo o PC como target e a palavra Caro como assessment deram 99% de confiança sobre a negatividade da opinião, e 75% sobre o sentimento negativo para o documento.
