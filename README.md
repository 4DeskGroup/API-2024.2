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

#### RF1:

•	O chatbot deve responder perguntas sobre especificações de produtos que tiveram reviews e informações de compradores anteriores, que permitam o usuário saber a qualidade do produto de acordo com os consumidores.</br>
• Os usuários podem obter informações detalhadas e diretas sobre produtos, ajudando na tomada de decisão para comprar itens com melhor custo-benefício para a empresa.</br>

#### RF2:

•	O chatbot deve fornecer respostas bem direcionadas e em linguagem natural com detalhes específicos e claros sobre informações de categorias de produtos mencionadas pelo usuário. Assim, o usuário pode pedir sugestões de produtos para o chat de acordo com as avaliações dos consumidores de forma concisa.</br>
•	Permite acesso à informações precisas e relevantes, facilitando a comparação e escolha de produtos para o setor de compras de empresas, garantindo informações confiáveis e embasadas.</br>
•	Melhoria das respostas para perguntas sobre compras de produtos para que forneça respostas mais ricas, confiáveis e informativas sobre os produtos mencionados pelo usuário.</br>

#### RF3:

•	O sistema deve identificar e classificar o sentimento das análises (positivo, neutro, negativo) de acordo com a dúvida do usuário do setor de compras da empresa, como:
  •	Descrição de sentimentos e opiniões agrupados por produto.
  •	Visualização clara das tendências de opinião.
  •	Comparação entre dois ou mais produtos com o mesmo propósito, mostrando os prós e contras de cada um e qual pode ser melhor para uma circunstância específica.
•	Respostas que ajudam a entender a percepção geral dos consumidores, influenciando decisões de compra.
•	O sistema deve gerar recomendações baseadas em análises positivas de produtos para facilitar a escolha de produtos de alta qualidade, baseando-se na opinião dos consumidores.</br>
•	O sistema deve fornecer respostas como opções de produtos recomendados com base em reviews permitindo visualizar e entender detalhes dos produtos recomendados.</br>

#### RF4:

•	Sistema fornece respostas que permite o usuário visualizar produtos por categoria de avaliação quando o usuário pedir sugestão de produtos sem especificar marcas.</br>

#### RF5:

•	O sistema utiliza o histórico de interações anteriores para responder às novas perguntas do usuário de forma a manter a coerência com as informações fornecidas previamente e seguir uma linha de raciocínio estabelecida. Isso ajuda a garantir respostas mais precisas e personalizadas, levando em consideração as preferências e os contextos já mencionados pelo usuário.

#### RF6:

•	A interface deve ser fácil de navegar e interagir, proporcionando uma experiência agradável, facilitando a interação com o chatbot.</br>
•	Design intuitivo com botões de navegação.</br>
•	Layout limpo e organizado.</br>
•	Elementos visuais que guiam o usuário durante a navegação.


 # :bulb: Backlog

| Rank | Prioridade | User Story                                                                                                                                                      | Estimativa | Sprint | Requisito do Parceiro |
|:----:|:----------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----------:|:------:|:---------------------:|
| 1    | Alta       | Criação da Interface de Chatbot para reviews - Implementação do RAG/FAISS<br>Como um usuário final, eu quero interagir com uma interface (prompt) de chatbot, para que eu possa fazer perguntas e receber respostas sobre as análises de produtos em linguagem natural com dados crus. | 21         | 1      | RNF2, RF1              |
| 2    | Alta       | Criação da Interface de Chatbot para reviews - Base de dados refinada<br>Como um usuário final, eu quero interagir com uma interface (prompt) de chatbot, para que eu possa fazer perguntas e receber respostas bem direcionadas sobre as análises de produtos em linguagem natural com dados refinados. | 25         | 1      | RNF1, RNF2, RF3                   |
| 3    | Média      | Análise de Sentimento para Comparação de Produtos<br>Como um funcionário do departamento de compras, com base nas reviews e notas fornecidas pelos consumidores, eu quero que a IA identifique o sentimento nas reviews, para que eu possa entender a opinião geral dos consumidores sobre um produto e assim priorizar as melhores opções de compra. | 13         | 2      | RNF1, RNF2, RF3                 |
| 4    | Média      | Recomendações de Produtos<br>Como um funcionário do departamento de compras, eu quero receber recomendações de produtos com base na análise de sentimentos e comparações dos produtos com melhores reviews, para que eu possa tomar decisões embasadas sobre quais produtos adquirir. | 13         | 2      | RNF1, RNF4               |
| 5    | Média      | Histórico de Conversa<br>Como um funcionário do departamento de compras, eu quero interagir com um chatbot que responda minhas dúvidas sobre produtos com base no banco de dados de reviews e notas (B2W) e com o auxílio do histórico das perguntas feitas por mim e respostas fornecidas pelo chat anteriormente. | 13         | 2      |               RF5              |
| 6    | Média      | Implementação da interface front-end<br>Como um funcionário do departamento de compras, quero visualizar uma interface de navegação para que eu tenha maior facilidade de interagir com o chat bot. | 21         | 2      | RNF3, RF6            |
| 7    | Baixa      | Refinamento da interface front-end<br>Como um usuário final, quero visualizar uma interface de fácil e intuitiva navegação para que eu tenha uma experiência agradável.                                                                                                                            | 20         | 3      | RNF3, RF6            |
| 8    | Baixa      | Tutorial em Vídeo<br>Como um usuário final não técnico, eu quero acessar um vídeo tutorial, para que eu possa entender como usar a plataforma de maneira eficiente. | 2          | 3      | RNF4                  |



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
| 01   | Alta       | Como um usuário final, eu quero interagir com uma interface (prompt) de chatbot, para que eu possa fazer perguntas sobre assuntos gerais e receber respostas básicas para minhas perguntas. | 21         | 01     | RF-2      |
| 02   | Alta       | Como um usuário final, eu quero interagir com uma interface (prompt) de chatbot, para que eu possa fazer perguntas e receber respostas sobre as análises de produtos em linguagem natural com dados crus. | 21         | 01     | RF-2      |
| 03   | Alta       | Como um usuário final, eu quero interagir com uma interface (prompt) de chatbot, para que eu possa fazer perguntas e receber respostas bem direcionadas sobre as análises de produtos em linguagem natural com dados refinados.| 25         | 01     | RF-1 e RF-2      |
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















