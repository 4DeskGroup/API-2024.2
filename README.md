<div name="topo"></div>

<div align="center">
  <h1>API-2024.2</h1>
</div>


<div align="center">
  <h2>Projeto de IA Generativa</h2>
</div>


##### <p align="center"> Projeto Integrador</p>
<div align = "center">
 <img src="https://user-images.githubusercontent.com/90328117/161355339-d016f60b-e185-49da-a5de-6c21f1965449.png" style="width:80px;height:40px;">
</div>



##### <p align="center">  Empresa parceira - Dom Rock </p>

<div align="center">
 
 [Informações e Proposta do projeto](https://github.com/4DeskGroup/API-2024.2#proposta) • [Backlog](https://github.com/4DeskGroup/API-2024.2#backlog) • [Entregas](https://github.com/4DeskGroup/API-2024.2#entregas) • [Tecnologias](https://github.com/4DeskGroup/API-2024.2#tecnologias) • [Equipe](https://github.com/4DeskGroup/API-2024.2#equipe)
</div>

<div name="proposta"></div>

# :dart: Informações e Proposta do projeto

<p align="left"> Desenvolver uma IA capaz de analisar e gerar insights a partir de reviews de produtos de e-commerce, ajudando o departamento de compras corporativas a tomar decisões mais informadas na seleção e aquisição de produtos. A IA deve otimizar o processo de escolha de fornecedores e produtos, levando em consideração feedbacks de consumidores para área de compras de uma empresa. A utilização do usuário com a IA será voltado para avaliar a qualidade e aceitação de produtos com base em reviews, identificar tendências e preferências dos consumidores, comparar fornecedores com base em feedback de clientes.</p>
</br>

As branches e commits deste projeto aderem ao padrão definido pelo [Conventional Commits](https://conventionalcommits.org) e exemplos de uso estão disponíveis [neste repositório](https://github.com/iuricode/padroes-de-commits).
</br>
</br>
<div name="backlog"></div> 

 # 📑 Requisitos Funcionais
 
**RF1 - Especificações de Produtos a partir de Reviews:** </br>
• O sistema deve extrair informações detalhadas de avaliações e comentários feitos por consumidores, destacando aspectos importantes, como qualidade, desempenho e características do produto especificado pelo usuário. Essas informações ajudarão a entender a experiência de outros compradores e a tomar decisões informadas.
 
**RF2 - Sugestões de Produtos, por categoria inclusive:** </br>
• O sistema deve ser capaz de sugerir produtos dentro de categorias especificadas pelo usuário. Isso permite que o usuário receba recomendações personalizadas, mesmo sem especificar um produto ou marca exata.
 
**RF3 - Comparações de Produtos, levando em conta custo-benefício:** </br>
• O sistema deve comparar produtos com base em critérios como desempenho, qualidade, preço e feedback dos consumidores. Ele fornecerá um resumo das vantagens e desvantagens de cada produto, ajudando o usuário a escolher a melhor opção de acordo com o orçamento e a necessidade.
 
**RF4 - Análise de Sentimento a partir de Reviews:** </br>
• O sistema deve analisar as avaliações dos consumidores e identificar o sentimento predominante (positivo, negativo ou neutro) em relação a um produto., auxiliando na percepção da qualidade do mesmo.
 
**RF5 - Análise de Tendências de Opinião:** </br>
• O sistema identifica tendências e similaridades de padrões nas opiniões dos consumidores sobre produtos, oferecendo insights para decisões de compra.
</br>
</br>
 
 # 💻 Requisitos Não Funcionais
 
**RNF1 - BD Vetorial ChromaDB, FAISS ou outro:** </br>
• O sistema deve utilizar um banco de dados vetorial, como ChromaDB ou FAISS, para consultas eficientes.
 
**RNF2 - Datasets de uso público do Huggingface:** </br>
• O sistema deve usar modelos de dataset disponíveis publicamente no Huggingface para busca do dataset.
 
**RNF3 - Framework Langchain:** </br>
• O sistema deve ser desenvolvido usando o framework Langchain para integração com modelos e bases de dados.
 
**RNF4 - Vídeo-tutorial:** </br>
• O sistema deve incluir um vídeo-tutorial para facilitar a compreensão de seu uso e funcionalidades.
</br>
</br>

 # :bulb: Backlog

| Rank | Prioridade | User Story                                                                                                                                                      | Estimativa | Sprint | Requisito do Parceiro |
|:----:|:----------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----------:|:------:|:---------------------:|
| 1    | Alta       | **Criação da Interface de Chatbot para reviews - Implementação do RAG/FAISS**</br><br>Como um usuário final, eu quero interagir com uma interface (prompt) de chatbot, para que eu possa fazer perguntas e receber respostas sobre as reviews de produtos em linguagem natural com dados crus. <br> | 21         | 1      | RF1              |
| 2    | Alta       | **Criação da Interface de Chatbot para reviews - Base de dados refinada**</br><br>Como um usuário final, eu quero interagir com uma interface (prompt) de chatbot, para que eu possa fazer perguntas e receber respostas bem direcionadas sobre as reviews de produtos em linguagem natural com dados refinados. <br>| 25         | 1      | RF1                  |
| 3    | Média      | **Análise de Sentimento para Comparação de Produtos**<br><br>Como um funcionário do departamento de compras, com base nas reviews e notas fornecidas pelos consumidores, eu quero que a IA identifique o sentimento nas reviews, como comentários positivos, negativos ou neutros, para que eu possa entender a opinião geral dos consumidores sobre um ou mais produtos e a diferença entre eles, para assim priorizar as melhores opções de compra.<br> | 13         | 2      | RF3, RF4                 |
| 4    | Média      | **Recomendações de Produtos**<br><br>Como um funcionário do departamento de compras, ao especificar uma categoria de produtos, eu quero receber recomendações de produtos dessa categoria com base na análise de sentimentos e comparações dos produtos com melhores reviews, para que eu possa tomar decisões embasadas sobre quais produtos adquirir.<br> | 13         | 2      | RF2, RF4               |
| 5    | Média      | **Histórico de Conversa**<br><br>Como um funcionário do departamento de compras, eu quero interagir com um chatbot que responda minhas dúvidas sobre produtos com base no banco de dados de reviews e notas (B2W) e com o auxílio do histórico das perguntas feitas por mim e respostas fornecidas pelo chat anteriormente. <br>| 13         | 2      |               RF1, RF4              |
| 6    | Média      | **Implementação da interface front-end**<br><br>Como um funcionário do departamento de compras, quero visualizar uma interface simples de navegação para que eu tenha maior facilidade de interagir com o chat bot. <br>| 31         | 2      | RF1, RF2    |
| 7    | Baixa      | **Refinamento da interface front-end**<br><br>Como um usuário final, quero visualizar uma interface com identidade visual definida de fácil e intuitiva navegação para que eu tenha uma experiência agradável. <br>                                                                                                                           | 20         | 3      | RF1, RF2          |
| 8    | Baixa      | **Tutorial em Vídeo**<br><br>Como um usuário final não técnico, eu quero acessar um vídeo tutorial, para que eu possa entender como usar a interface do chatbot de maneira eficiente. <br>| 2          | 3      | RNF4                  |



</br>

<div name="tecnologias"></div> 

# 🛠️ Tecnologias

As seguintes ferramentas, linguagens e tecnologias foram utilizadas na execução do projeto:
<div style="display: inline_block">
 <img align="center" alt="Vue.js" src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D">
 <img align="center" alt="python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
 <img align="center" alt="ts" src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white">
 <img align="center" alt="ts" src="https://img.shields.io/badge/langchain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white">
 <img align="center" alt="ts" src="https://img.shields.io/badge/Google%20Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white">
 

  
</div>

</br>


<div name="entregas"></div> 

# 📌 Entregas

<details>
<summary> <strong>Sprint 1</strong> </summary>
  

## 🎯 MVP

O MVP da primeira entrega foi o desenvolvimento da IA capaz de receber inputs de perguntas e responder perguntas básicas sobre recomendações de produtos, com tratamento de dados para evitar respostas e informações errôneas.
  
## 📃 Backlog da Sprint
 
| Rank | Prioridade | User Story | Estimativa | Sprint | Requisito |
|------|------------|------------|------------|--------|-----------|
| 01   | Alta       | Como um usuário final, eu quero interagir com uma interface (prompt) de chatbot, para que eu possa fazer perguntas e receber respostas sobre as reviews e notas de produtos em linguagem natural com dados crus. | 21         | 01     | RF1     |
| 02   | Alta       | Como um usuário final, eu quero interagir com uma interface (prompt) de chatbot, para que eu possa fazer perguntas e receber respostas bem direcionadas sobre as análises de produtos em linguagem natural com dados refinados.| 25         | 01     | RF1      |
## 📌 DOR
 
### 📄 User Stories e Critérios de Aceitação
 
**US #1:**  Como um usuário final, eu quero interagir com uma interface (prompt) de chatbot, para que eu possa fazer perguntas sobre assuntos gerais e receber respostas básicas para minhas perguntas.
 
**Critérios de aceitação:**
 
- AC1. Interface de chatbot permite perguntas.
- AC2. Responde perguntas gerais com respostas básicas.
- AC3. Interface simples e acessível.
- AC4. Respostas fluídas e rápidas.

 
**US #2:** Como um usuário final, eu quero interagir com uma interface (prompt) de chatbot, para que eu possa fazer perguntas e receber respostas sobre as análises de produtos em linguagem natural com dados crus.
 
**Critérios de aceitação:**

- AC1. Interface permite perguntas sobre produtos.
- AC2. Respostas baseadas em reviews de produtos.
- AC3. Respostas em linguagem natural.
- AC4. Informações como sentimento e resumo dos comentários incluídos nas respostas.
- AC5. Capacidade de lidar com perguntas específicas sobre reviews de produtos.



**US #3:** Como um usuário final, eu quero interagir com uma interface (prompt) de chatbot, para que eu possa fazer perguntas e receber respostas bem direcionadas sobre as análises de produtos em linguagem natural com dados refinados.
 
**Critérios de aceitação:**

- AC1. Interface permite perguntas sobre produtos.
- AC2. Respostas baseadas em reviews de produtos sem dados repetidos e poluídos.
- AC3. Respostas em linguagem natural.
- AC4. Informações como sentimento e resumo dos comentários incluídos nas respostas.
- AC5. Capacidade de lidar com perguntas específicas sobre reviews de produtos.

 
</br>
 
## 💾 Dados para IA

Para essa entrega, os dados utilizados para construção do chat bot com IA foram a partir do repositório https://huggingface.co/datasets/ruanchaves/b2w-reviews01

</br>

## 🖥️ Entrega
 
![Meu GIF](https://github.com/4DeskGroup/API-2024.2/blob/main/docs%20sprints/sprint-1.gif)

### Link do vídeo no youtube
[Assista ao vídeo da entrega no YouTube](https://youtu.be/MjZo2yKE-Xw)
 
</br>

</details>



<details>
<summary> <strong>Sprint 2</strong> </summary>
  

## 🎯 MVP

O MVP da segunda entrega foi o desenvolvimento da IA capaz de analisar e identificar o sentimento nas reviews de produtos, proporcionando ao funcionário do departamento de compras uma compreensão clara da opinião geral dos consumidores. Além disso, a IA deve oferecer recomendações de produtos baseadas nessa análise, possibilitando decisões de compra mais embasadas. A interação com um chatbot, que utiliza um banco de dados de reviews e um histórico de perguntas e respostas, facilitará a obtenção de informações específicas. Por fim, a interface de navegação será intuitiva, garantindo uma experiência de uso eficiente e acessível.
  
## 📃 Backlog da Sprint
 
| Rank | Prioridade | User Story | Estimativa | Sprint | Requisito |
|------|:----------:|------------|:----------:|:------:|-----------|
| 03   | Média      | Como um funcionário do departamento de compras, com base nas reviews e notas fornecidas pelos consumidores, eu quero que a IA identifique o sentimento nas reviews, para que eu possa entender a opinião geral dos consumidores sobre um produto e assim priorizar as melhores opções de compra. | 13         | 02     | RF3, RF4      |
| 04   | Média      | Como um funcionário do departamento de compras, eu quero receber recomendações de produtos com base na análise de sentimentos e comparações dos produtos com melhores reviews, para que eu possa tomar decisões embasadas sobre quais produtos adquirir. | 13         | 02     | RF2, RF4      |
| 05   | Média      | Como um funcionário do departamento de compras, eu quero interagir com um chatbot que responda minhas dúvidas sobre produtos com base no banco de dados de reviews e notas (B2W) e com o auxílio do histórico das perguntas feitas por mim e respostas fornecidas pelo chat anteriormente. | 13         | 02     | RF1, RF4      |
| 06   | Média      | Como um funcionário do departamento de compras, quero visualizar uma interface de navegação para que eu tenha maior facilidade de interagir com o chatbot. | 21         | 02     | RF1, RF2      |

</br>

## 📌 DOR
 
### 📄 User Stories e Critérios de Aceitação
 
**US #1:**  Como um funcionário do departamento de compras, com base nas reviews e notas fornecidas pelos consumidores, eu quero que a IA identifique o sentimento nas reviews, para que eu possa entender a opinião geral dos consumidores sobre um produto e assim priorizar as melhores opções de compra.
 
**Critérios de aceitação:**
 
- AC1. Classificação dos reviews em positivo, neutro ou negativo. Exemplo: Pergunta: "O Notebook da marca X e modelo Y é bom?" Resposta: "Ele possuí a maioria das avaliações positivas, com destaque em X,Y,Z"
- AC2. Resposta clara e intuitiva.
- AC3. Funciona para diferentes categorias de produtos.
- AC4. Pelo menos 3 produtos de marcas distintas recomendados por consulta. Exemplo: Pergunta: "Me recomende um notebook para jogos" Resposta: "Notebook X, Notebook Y, Notebook Z"
- AC5. Recomendações personalizadas com base em popularidade e nota.
</br>

**US #2:** Como um funcionário do departamento de compras, eu quero receber recomendações de produtos com base na análise de sentimentos e comparações dos produtos com melhores reviews, para que eu possa tomar decisões embasadas sobre quais produtos adquirir.
 
**Critérios de aceitação:**

- AC1. Comparação de pelo menos 3 produtos similares. Exemplo: Pergunta: "Qual notebook tem um melhor custo benefício?" Resposta: "Notebook X (tais beneficios), Notebook Y (tais beneficios), Notebook Z (tais beneficios)"
- AC2. Comparações incluem nota média, pontos fortes e fracos e preço.
- AC3. Visualização lado a lado dos produtos.
- AC4. Filtragem por categorias ou características específicas.
- AC5. Comparação feita em menos de 3 segundos.
</br>

**US #3:** Como um funcionário do departamento de compras, eu quero interagir com um chatbot que responda minhas dúvidas sobre produtos com base no banco de dados de reviews e notas (B2W) e com o auxílio do histórico das perguntas feitas por mim e respostas fornecidas pelo chat anteriormente.
 
**Critérios de aceitação:**

- AC1. Quando o usuário fizer uma pergunta no chat, sua pergunta deve ser salva no histórico da conversa
- AC2. A pergunta salva no histórico pode ser usada posteriormente como referência numa próxima pergunta para obter respostas mais precisas e dentro do contexto mencionado previamente.
- AC3. O chat deve considerar todas as perguntas feitas pelo usuário para contextualizar suas próximas respostas.

</br>

**US #4:** Como um funcionário do departamento de compras, quero visualizar uma interface de navegação para que eu tenha maior facilidade de interagir com o chatbot.
 
**Critérios de aceitação:**

- AC1. O usuário deve visualizar uma interface gráfica composta por uma unica tela 
- AC2. A interface deve ser composta por retângulos de texto ao lado direito para cada pergunta e lado esquerdo para respostas
- AC3. A interface deve conter um campo de input na parte inferior da tela para digitar perguntas
- AC4. A interface deve conter um botão para enviar a pergunta para o chat ler o que foi escrito.

 
</br>
 
## 💾 Dados para IA

Para essa entrega, os dados utilizados para construção do chat bot com IA foram a partir do repositório https://huggingface.co/datasets/ruanchaves/b2w-reviews01

</br>

## 🖥️ Entrega
 
![Meu GIF]("")

### Link do vídeo no youtube
[Assista ao vídeo da entrega no YouTube]("")
 
</br>

</details>








<div name="equipe"></div> 

# 🎓 Equipe

|        Nome         |       Função        |     GitHub                                               |    Avatar                                          |
| ------------------- | ------------------- | -------------------                                      | -------------------                                |
|  Laiza Truyts    |  Scrum Master       |<a href="https://github.com/LaizaCristina"><img src="https://user-images.githubusercontent.com/90328117/161353573-4c0e497a-b4fa-4f46-ade2-10b37360e2d2.jpg" class="media-object  img-responsive img-thumbnail"></a>                                                      |           <img src="https://avatars.githubusercontent.com/u/111503805?s=400&u=c48f83c5ed8e01db8c3579a66dd03ab74bd7beec&v=4" style="width:50px;height:50px;">                                         |
|  Stefanie Heinrich    |  Product Owner      |<a href="https://github.com/ste-fa-nie"><img src="https://user-images.githubusercontent.com/90328117/161353573-4c0e497a-b4fa-4f46-ade2-10b37360e2d2.jpg" class="media-object  img-responsive img-thumbnail"></a>                                                    |           <img src="https://user-images.githubusercontent.com/89950512/229545415-3b305cd2-15cc-4636-b43b-193a8ad727fc.jpeg" style="width:50px;height:50px;">                                                       |
|  Carlos Kauã             |  Desenvolvedor                |<a href="https://github.com/CarlosKB"><img src="https://user-images.githubusercontent.com/90328117/161353573-4c0e497a-b4fa-4f46-ade2-10b37360e2d2.jpg" class="media-object  img-responsive img-thumbnail"></a>                                                      |           <img src="https://user-images.githubusercontent.com/89950512/229543573-c3a296fa-a8ea-43a5-9f27-35fdaf5ea611.jpeg" style="width:50px;height:50px;">   |
|  Eliézer Lopes   |  Desenvolvedor       |<a href="https://github.com/EliezerLopes1"><img src="https://user-images.githubusercontent.com/90328117/161353573-4c0e497a-b4fa-4f46-ade2-10b37360e2d2.jpg" class="media-object  img-responsive img-thumbnail"></a>                                                      |           <img src="https://avatars.githubusercontent.com/u/102488914?v=4" style="width:50px;height:50px;">                                         |
|  Mariana Veloso    |  Desenvolvedora       |<a href="https://github.com/Marih2210"><img src="https://user-images.githubusercontent.com/90328117/161353573-4c0e497a-b4fa-4f46-ade2-10b37360e2d2.jpg" class="media-object  img-responsive img-thumbnail"></a>                                                      |           <img src="https://avatars.githubusercontent.com/u/100208153?v=4" style="width:50px;height:50px;">                                         |
|  Nicolas Bonifácio    |  Desenvolvedor       |<a href="https://github.com/Marih2210"><img src="https://user-images.githubusercontent.com/90328117/161353573-4c0e497a-b4fa-4f46-ade2-10b37360e2d2.jpg" class="media-object  img-responsive img-thumbnail"></a>                                                      |           <img src="https://avatars.githubusercontent.com/u/103084208?v=4" style="width:50px;height:50px;">                                         |
|   Rafaela Vieira  |  Desenvolvedora       |<a href="https://github.com/RafaelaCabral"><img src="https://user-images.githubusercontent.com/90328117/161353573-4c0e497a-b4fa-4f46-ade2-10b37360e2d2.jpg" class="media-object  img-responsive img-thumbnail"></a>                                                          |           <img src="https://avatars.githubusercontent.com/u/50456594?v=4" style="width:50px;height:50px;">  
|  Thyago Silveira       |  Desenvolvedor      | <a href="https://github.com/Thyaguixx"><img src="https://user-images.githubusercontent.com/90328117/161353573-4c0e497a-b4fa-4f46-ade2-10b37360e2d2.jpg" class="media-object  img-responsive img-thumbnail"></a>| <img src="https://avatars.githubusercontent.com/u/83200721?v=4" style="width:50px;height:50px;"> |
</br>


 → [Voltar ao topo](https://github.com/4DeskGroup/API-2024.2#topo)















