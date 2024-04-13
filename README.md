# AI Search
O Azure AI Search oferece uma busca avançada e personalizada, utilizando inteligência artificial para encontrar resultados relevantes em diversas fontes de dados, como documentos e imagens, melhorando a experiência do usuário e facilitando a descoberta de informações.

- Primeiro crie um recuso de AI Search
<img width="928" alt="image" src="https://github.com/SuellenlLima/DP04---AI-Search/assets/125047720/db957d99-6901-4142-8f60-f9b08995b146">

- Agora crie um recurso de IA
<img width="734" alt="image" src="https://github.com/SuellenlLima/DP04---AI-Search/assets/125047720/83402cfc-237f-47d8-8527-d68d7eee473a">

- E por fim crie uma conta de armazenamento
<img width="705" alt="image" src="https://github.com/SuellenlLima/DP04---AI-Search/assets/125047720/c3a1683f-1d1c-443e-9d94-2003faa4379b">

## Criação de um container
- Após criar uma conta de armazenamento, vá até containers e clique em criar
![Imagem criação container](https://github.com/SuellenlLima/DP04---AI-Search/assets/125047720/f2fdd998-48b6-4161-9f6b-ed5d495b8323)

- Cosultando o índice
Feitas todas as configurações vamos voltar ao AZURE AI SERVICES, entrar no nosso serviço e através do SEARCH EXPLORER testar se tudo foi indexado e se a consulta esta funcionando, utilizando os comandos:
<img width="599" alt="image" src="https://github.com/SuellenlLima/DP04---AI-Search/assets/125047720/affa59a1-dcaf-4a9b-95af-3319da6d1ff3">

search=*&$count=true    (  verifica se a indexação esta funcionando e mostra os documentos )

<img width="514" alt="image" src="https://github.com/SuellenlLima/DP04---AI-Search/assets/125047720/7e8e6b14-01d0-4b02-a3b1-05e9be18e106">

search=locations:'Chicago' ( Consulta as ocorrencias acontecidas em Chicado )

<img width="529" alt="image" src="https://github.com/SuellenlLima/DP04---AI-Search/assets/125047720/97efa15a-e087-4860-80c1-d059eaccd19d">

search=sentiment:'negative' ( Consulta as ocorrencias com sentimento negativo )

<img width="532" alt="image" src="https://github.com/SuellenlLima/DP04---AI-Search/assets/125047720/8683df23-2874-4a47-98ed-d92681602d70">






