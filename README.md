# Lab Project 03 - Análise de sentimentos com Language Studio no Azure AI
**Sentiment and opinion mining** é uma solução da plataforma **Language Studio, da Azure**, que permite **detectar sentimentos positivos, negativos e neutros** a partir de sentenças. Esse repositório mostra alguns exemplos de testes na plataforma. Os procedimentos foram realizados como parte do **Bootcamp Microsoft Azure AI Fundamentals, da DIO**.

![Static Badge](https://img.shields.io/badge/Status_Projeto:-Em_andamento(15/Mar/2024)-orange)

![Static Badge](https://img.shields.io/badge/Inteligência_Artificial_(IA)-blue)
![Static Badge](https://img.shields.io/badge/NLP-blue)
![Static Badge](https://img.shields.io/badge/Speech_Recognition-blue)
![Static Badge](https://img.shields.io/badge/Sentiment_Mining-blue)
![Static Badge](https://img.shields.io/badge/Opinion_Mining-blue)
![Static Badge](https://img.shields.io/badge/Microsoft_Azure-blue)
![Static Badge](https://img.shields.io/badge/Azure_Language_Studio-blue)

## Procedimento
Esses experimentos foram baseados nos guias da Microsoft Learn. Para informações mais detalhadas, consulte a página [Analyze text with Language Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html).

### Criar um recurso Azure Language Service
Para ser possível usar o Language Studio, é essencial que você possua um recurso para a plataforma associado a sua conta Azure. Isso pode ser feito por meio dos seguintes passos:
1. Acessar https://portal.azure.com
2. Criar um novo recurso **Language Service** através da opção Create Resource.
3. Esperar o *deploy* do recurso terminar.

<div align="center">
    <img src="readmeFiles/16.png" alt="Create a resource" width="800"/>
</div>

### Selecioanr recurso no Language Studio
Com o recurso Language Service criado, é preciso conecta-lo ao Language Studio. Para isso, basta seguir os seguintes passos:

1. Acessar o [Language Studio](https://language.cognitive.azure.com/home).
2. Na página inicial, acessar os recursos criados através do botão "Select a resouce".

<div align="center">
    <img src="readmeFiles/17.png" alt="View all resources" width="800"/>
</div>

3. Preencha as informações e selecione o recurso recém criado.

<div align="center">
    <img src="readmeFiles/18.png" alt="Set default resource" width="800"/>
</div>

### Selecionando e testando o serviço no Language Studio
Ao retornar a página inicial após concluídos os passos anteriores, é possível ver a lista de serviços disponíveis para teste na plataforma. Nesse experimento foi usado o serviço "Analyze sentiment and mine opinions".

<div align="center">
    <img src="readmeFiles/19.png" alt="Language Studio Services" width="800"/>
</div>
