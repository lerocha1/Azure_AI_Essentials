<h1>
    <a href='https://www.dio.me'>
    <img align="center" width="60px" src="https://hermes.dio.me/lab_projects/badges/619af8f8-d138-4e40-9d48-fec7b318e44d.png"> </a>
    <span>
Azure_AI_Essentials
</h1>

Este laboratório é utlizando o [AI Search](https://azure.com/).

O desafio pede que seja criada uma pesquisa que funcione juntamente com um serviço de inteligência artificial para identificar palavras chave, sentimentos, utilizando também o serviço de armazenamento do azure.


## Como chegar lá?

Esteja com sua conta logada!

## Passo 1: Criando recurso do Asure AI Search.

Esse passo fizemos em todos os projetos anteriores!

## Passo 2: Criando recurso do Azure AI services.

Ver documentação [oficial](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html)

## Passo 3: Criando o storage: 

Retorne à página inicial do portal do Azure e selecione o botão + Criar um recurso .

Procure conta de armazenamento e crie um recurso de conta de armazenamento com as seguintes configurações:

Assinatura : sua assinatura do Azure.

Grupo de recursos : O mesmo grupo de recursos que os recursos do Azure AI Search e dos serviços Azure AI.

Nome da conta de armazenamento : um nome exclusivo .

Localização : Escolha qualquer localização disponível .

Padrão de desempenho

Redundância : armazenamento localmente redundante (LRS)

Clique em Revisar e em Criar . Aguarde a conclusão da implantação e vá para o recurso implantado.

Na conta de Armazenamento do Azure que você criou, no painel de menu esquerdo, selecione Configuração (em Configurações ).

Altere a configuração de Permitir acesso anônimo de Blob para Habilitado e selecione Salvar .

## Passo 4: Permitindo acesso anônimo ao Blob.

Como nosso laboratório é apenas didático,para aprender os princípios da inteligência artificial com o Azure, precisamos permitir o acesso anônimo ao blob para simplificar e facilitar nossas implementações, Após criar o seu Storage, entre no mesmo e navegue até a guia SETTINGS > CONFIGURATION  e desabilite o BLOB.

## Passo 5: Criando o Container.

Vá até a guia DATA STORAGE > CONTAINERS, e crie um contanier dentro do storage e adicionar as pesquisas que seram analisadas pelo AI SERVICE.

## Passo 6: Importação e indexação dados para o AI SEARCH.    

Neste ponto você precisa conectar os dados que você inseriu e configurou no seu STORAGE, volte para o AI SEARCH e finalize a importaçãp/indexaçãoo.

A [Documentação](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html) ajudará você a chegar em INDEX DOCUMETS.

## Passo 7: Cnsultando o índice.   

Feitas todas as configurações vamos voltar ao AZURE AI SERVICES, entrar no nosso serviço e através do SEARCH EXPLORER testar se tudo foi indexado e se a consulta esta funcionando, utilizando os comandos:

## Insights 

As ferramentas do portal Azure, em especial as de Inteligencia artificial, possibilitam a digitalização de processos fisicos e possibilita a busca do conteudo destas digitalizações. Isto possibilita a criaçcão de um buscador que leia os documentos e mostre o caminho, poupando muito tempo em consultas a arquivos antigos!


## Referência

 - [Documentação Oficial](https://learn.microsoft.com/en-us/training/paths/document-intelligence-knowledge-mining/)
 - [Documentação AZure AI Serach](https://aka.ms/ai900-ai-search)
 - [Portal Azure](https://portal.azure.com)
 
## 😊Autores

- [@lerocha1](https://www.github.com/lerocha1)


## 🚀 Sobre mim
Pai, ciclista e apaixonado por Tecnologia, atuo como Gerente multidisciplinar em uma empresa de engenharia e que nas horas vagas "gasto" meu tempo com programação e desafios na internet.

Programando marjoritariamente em Python, também especialista em banco de Dados, Analise de dados/Big Data e programador FullStack.