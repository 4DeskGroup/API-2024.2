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

<details>
<summary> <strong>RF1 - Especificações de Produtos a partir de Reviews:</strong> </summary>

• O sistema deve extrair informações detalhadas de avaliações e comentários feitos por consumidores, destacando aspectos importantes, como qualidade, desempenho e características do produto especificado pelo usuário. Essas informações ajudarão a entender a experiência de outros compradores e a tomar decisões informadas.  </br>

• Usabilidade:  </br>
o Pergunta: Quais características a Cadeira de Escritório Dot All Black mais se destacam nas avaliações?  </br>
o Resposta esperada:  </br>
  o Características da Cadeira de Escritório Dot All Black  </br>
    ▪ Giratória: Facilita a movimentação e o ajuste de posição.  </br>
    ▪ Rodízios: Permite fácil deslocamento no ambiente de trabalho.  </br>
    ▪ Laminada: Oferece durabilidade e resistência a riscos. </br>
    ▪ Corino preto: Confere um toque de elegância e estilo. </br>
  o Esta cadeira é recomendada para usuários que buscam: </br>
    ▪ Conforto e ajuste de posição </br>
    ▪ Facilidade de movimentação </br>
    ▪ Design moderno e elegante </br>

</details>

<details>
<summary> <strong>RF2 - Sugestões de Produtos, por categoria inclusive:</strong> </summary>
• O sistema deve ser capaz de sugerir produtos dentro de categorias especificadas pelo usuário. Isso permite que o usuário receba recomendações personalizadas, mesmo sem especificar um produto ou marca exata. </br>
• Usabilidade: </br>
o Pergunta: Qual opção de notebook é recomendada de acordo com as reviews dos usuários? </br>
o Resposta esperada: </br>
  o Recomendação: Notebook Dell Inspiron 15 3000 </br>
  o Justificativa: </br>
    o Avaliação positiva: Possui avaliação de 4, indicando que os usuários estão satisfeitos com o produto. </br>
    o Características adequadas: Conta com tela de 15,6 polegadas, processador Intel Core i5 e 8GB de RAM. </br>
    o Design moderno: O design elegante e compacto torna-o fácil de transportar e usar em qualquer lugar. </br>
    o Considerações adicionais: </br>
    o Tela: A tela de 15,6 polegadas oferece um amplo espaço de trabalho para edição de imagens e projetos gráficos. </br>
     </br>

</details>

<details>
<summary> <strong>RF3 - Comparações de Produtos, levando em conta custo-benefício:</strong> </summary>
• O sistema deve comparar produtos com base em critérios como desempenho, qualidade, preço e feedback dos consumidores. Ele fornecerá um resumo das vantagens e desvantagens de cada produto, ajudando o usuário a escolher a melhor opção de acordo com o orçamento e a necessidade. </br>
• Usabilidade:
  o Pergunta: Quais as principais diferenças entre os notebooks da marca Dell e os da marca Lenovo Ideapad em termos de desempenho e custo-benefício? </br>
  o Resposta esperada:  </br>
  **Principais Diferenças entre Notebooks Dell e Lenovo Ideapad** </br>
  **Desempenho:** </br>
    * **Dell:** Geralmente equipados com processadores Intel Core i5 ou i7, oferecendo desempenho robusto para tarefas diárias e multitarefa. </br>
    * **Lenovo Ideapad:** Conhecidos por oferecer uma ampla gama de opções de processador, incluindo Intel Core i3, i5 e i7, atendendo a diferentes necessidades de desempenho. </br>
    
  **Preço:** </br>
    * **Dell:** Notebooks Dell tendem a ter um preço mais alto em comparação com os modelos Lenovo Ideapad com especificações semelhantes. </br>
    * **Lenovo Ideapad:** Oferece uma variedade de opções de preço, com modelos econômicos e modelos de alto desempenho disponíveis. </br>
  
  **Características:** </br>
  **Dell:** </br>
    * **Tela:** Telas nítidas e vibrantes com opções de resolução Full HD e 4K. </br>
    * **Design:** Design elegante e moderno com opções de cores e acabamentos premium. </br>
    * **Durabilidade:** Construção robusta e durável, projetada para uso prolongado. </br>
    
  **Lenovo Ideapad:** </br>
    * **Tela:** Telas antirreflexo com opções de resolução HD e Full HD. </br>
    * **Design:** Design prático e funcional com opções de cores mais discretas. </br>
    * **Recursos multimídia:** Alguns modelos oferecem recursos multimídia aprimorados, como alto-falantes Harman Kardon e Dolby Atmos. </br>

</details> 

<details>
<summary> <strong>RF4 - Análise de Sentimento a partir de Reviews:</strong> </summary>
• O sistema deve analisar as avaliações dos consumidores e identificar o sentimento predominante em relação a um produto, auxiliando na percepção da qualidade do mesmo. </br>
• Usabilidade: </br>
  • Pergunta: Qual a percepção geral dos usuários sobre o Kit Teclado e Mouse Wireless KM636 Dell em termos de conforto? </br>
  • Resposta esperada: </br>
    **Percepção geral dos usuários sobre o Kit Teclado e Mouse Wireless KM636 Dell:** </br>
      As avaliações e comentários dos usuários indicam uma percepção geral positiva sobre o Kit Teclado e Mouse Wireless KM636 Dell em termos de conforto e usabilidade. </br>
    **Conforto:** </br>
      * Teclado ergonômico com teclas macias e silenciosas, proporcionando uma experiência de digitação confortável. </br>
      * Mouse óptico preciso com design ambidestro, se adaptando a diferentes tamanhos e formatos de mãos. </br>
    **Usabilidade:**    </br>
      * Conexão sem fio de 2,4 GHz oferece liberdade de movimentos e reduz a desordem de cabos. </br>
      * Alta precisão do mouse, facilitando tarefas de navegação e edição. </br>
      * Compatibilidade com vários sistemas operacionais, tornando-o versátil para uso em diferentes dispositivos. </br>
</details> 

<details>
<summary> <strong>RF5 - Análise de Tendências de Opinião:</strong> </summary>
• O sistema identifica tendências e similaridades de padrões nas opiniões sobre produtos dos consumidores de um público específico, oferecendo insights para decisões de compra que atenda o público especificado. </br>
• Usabilidade: </br>
  • Pergunta: Quais notebooks têm recebido melhores feedbacks de profissionais que trabalham em casa? </br>
  • Resposta esperada:   </br>
  **Recomendação:** Notebook Dell Inspiron 15 3000 </br>
    **Justificativa:** </br>
      * **Feedbacks positivos:** Análises de profissionais que trabalham em casa indicam alta satisfação com o desempenho e recursos do Notebook Dell Inspiron 15 3000. </br>
      * **Características adequadas:** A tela de 15,6 polegadas, o processador Intel Core i5 e os 8GB de RAM oferecem capacidade suficiente para multitarefa e aplicativos exigentes. </br>
      * **Design ergonômico:** O design leve e compacto torna o notebook fácil de transportar e usar em qualquer lugar da casa. </br>
      
  **Considerações adicionais:** </br>
    * **Tendência de consumo:** Análises anteriores indicam que profissionais que trabalham em casa valorizam notebooks com telas grandes, processadores potentes e designs ergonômicos. </br>
    * **Preferências do usuário:** A recomendação leva em consideração a necessidade de um notebook que atenda às demandas específicas de profissionais que trabalham em casa. </br>
    
  **Características principais:** </br>
    * **Tela:** Tela LED de 15,6 polegadas com resolução Full HD (1920 x 1080) </br>
    * **Processador:** Intel Core i5-1135G7 (2,4GHz até 4,2GHz) </br>
    * **Memória RAM:** 8GB DDR4 </br>
    * **Armazenamento:** 256GB SSD </br>
    * **Placa de vídeo:** Intel Iris Xe Graphics </br>
    * **Sistema operacional:** Windows 11 Home </br>
    
  **Recomenda-se este notebook para profissionais que trabalham em casa que buscam:** </br>
    * Um notebook com desempenho confiável e tela grande para multitarefa e aplicativos exigentes. </br>
    * Design ergonômico e leve para fácil portabilidade e uso em diferentes ambientes da casa. </br>
    * Recursos de segurança avançados para proteger dados e privacidade. </br>
</details> 

<details>
<summary> <strong>RF6 - Personalização de Respostas com Base no Histórico de Conversa:</strong> </summary>
• O sistema deve ser capaz de acessar e analisar o histórico de conversas do usuário para fornecer respostas mais contextualizadas e relevantes, aprimorando a experiência do usuário ao adaptar as sugestões e informações de acordo com interações anteriores. </br>
• Usabilidade: </br>
  • Histórico da conversa: Kit Teclado e Mouse Wireless KM636 Dell e o Notebook Dell Inspiron 15 3000 </br>
  • Pergunta: Compare os dois últimos produtos que você citou acima </br>
  • Resposta esperada:   </br>
  **Comparação entre o Kit Teclado e Mouse Wireless KM636 Dell e o Notebook Dell Inspiron 15 3000** </br>

  **Características:** </br>
  
  | Característica | Kit Teclado e Mouse Wireless KM636 Dell | Notebook Dell Inspiron 15 3000 |
  |---|---|---|
  | Tipo de produto | Kit teclado e mouse | Notebook |
  | Conexão | Sem fio (2,4 GHz) | Com fio |
  | Teclado | Ergonômico, teclas macias e silenciosas | Não especificado |
  | Mouse | Óptico, preciso, design ambidestro | Não aplicável |
  | Tela | Não aplicável | 15,6 polegadas, Full HD (1920 x 1080) |
  | Processador | Não aplicável | Intel Core i5-1135G7 (2,4GHz até 4,2GHz) |
  | Memória RAM | Não aplicável | 8GB DDR4 |
  | Armazenamento | Não aplicável | 256GB SSD |
  | Sistema operacional | Não aplicável | Windows 11 Home |
  
  **Recomendações:** </br>
    * **Para usuários que buscam um kit teclado e mouse confortável e confiável:** Kit Teclado e Mouse Wireless KM636 Dell </br>
    * **Para profissionais que trabalham em casa e precisam de um notebook com desempenho confiável, tela grande e design ergonômico:** Notebook Dell Inspiron 15 3000 </br>
    
</br>
</details> 

 # 💻 Requisitos Não Funcionais
 
**RNF1 - BD Vetorial FAISS:** </br>
• O sistema deve utilizar o banco de dados vetorial FAISS, para consultas eficientes.
 
**RNF2 - Datasets de uso público do Huggingface B2W:** </br>
• O sistema deve usar os modelos de dataset B2W-Reviews01 disponíveis publicamente no Huggingface para busca do dataset.
 
**RNF3 - Framework Langchain:** </br>
• O sistema deve ser desenvolvido usando o framework Langchain para integração com modelos e bases de dados.
 
**RNF4 - Vídeo-tutorial:** </br>
• O sistema deve incluir um vídeo-tutorial para facilitar a compreensão de seu uso e funcionalidades.

**RNF5 - Interface gráfica:** </br>
• O sistema deve incluir uma interface gráfica para auxiliar na intereção e praticidade da funcionalidades.
</br>
</br>

 # :bulb: Backlog

| Rank | Prioridade | User Story                                                                                                                                                      | Estimativa | Sprint | Requisito do Parceiro |
|:----:|:----------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----------:|:------:|:---------------------:|
| 1    | Alta       | **Criação da Interface de Chatbot para reviews - Implementação do RAG/FAISS**</br><br>Como um usuário final, eu quero interagir com uma interface (prompt) de chatbot, para que eu possa fazer perguntas e receber respostas sobre as reviews de produtos em linguagem natural com dados crus. <br> | 21         | 1      | RF2              |
| 2    | Alta       | **Criação da Interface de Chatbot para reviews - Base de dados refinada**</br><br>Como um usuário final, eu quero interagir com uma interface (prompt) de chatbot, para que eu possa fazer perguntas e receber respostas bem direcionadas sobre as reviews de produtos em linguagem natural com dados refinados. <br>| 25         | 1      | RF1, RF2                  |
| 3    | Média      | **Análise de Sentimento para Comparação de Produtos**<br><br>Como um funcionário do departamento de compras, com base nas reviews fornecidas pelos consumidores, eu quero que a IA identifique o sentimento nas reviews, como comentários positivos, negativos ou neutros, para que eu possa entender a opinião geral dos consumidores sobre um ou mais produtos e a diferença entre eles, para assim priorizar as melhores opções de compra.<br> | 13         | 2      | RF3, RF4                 |
| 4    | Média      | **Histórico de Conversa**<br><br>Como um funcionário do departamento de compras, eu quero interagir com um chatbot que responda minhas dúvidas sobre produtos com base no banco de dados de reviews e notas (B2W) e com o auxílio do histórico das perguntas feitas por mim e respostas fornecidas pelo chat anteriormente. <br>| 13         | 2      |               RF6              |
| 5    | Média      | **Implementação da interface front-end**<br><br>Como um funcionário do departamento de compras, quero visualizar uma interface simples de navegação para que eu tenha maior facilidade de interagir com o chat bot. <br>| 31         | 2      | RF1, RF2    |
| 6    | Média      | **Recomendações de Produtos por Segmento de Pessoas**<br><br>Como um funcionário do departamento de compras, ao especificar uma categoria de produtos para um público específico, eu quero receber recomendações de produtos dessa categoria com base na tendência de opiniões de pessoas de um mesmo segmento, para que eu possa tomar decisões embasadas sobre quais produtos adquirir para esse grupo.<br> | 13         | 3      | RF2, RF5               |
| 7    | Baixa      | **Sugestões de Pesquisa no Frontend**<br><br>Como um usuário do sistema, eu quero ter acesso a um botão que sugira perguntas mockadas, para que eu possa me basear nas informações do sistema e entender melhor como utilizar o chat para tirar dúvidas sobre produtos. <br>                                                                                                                           | 20         | 3      | RNF5          |
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

 
**US #1:** Como um usuário final, eu quero interagir com uma interface (prompt) de chatbot, para que eu possa fazer perguntas e receber respostas sobre as análises de produtos em linguagem natural com dados crus.
 
**Critérios de aceitação:**

- AC1. Interface permite perguntas sobre produtos.
- AC2. Respostas baseadas em reviews de produtos.
- AC3. Respostas em linguagem natural.
- AC4. Informações como sentimento e resumo dos comentários incluídos nas respostas.
- AC5. Capacidade de lidar com perguntas específicas sobre reviews de produtos.



**US #2:** Como um usuário final, eu quero interagir com uma interface (prompt) de chatbot, para que eu possa fazer perguntas e receber respostas bem direcionadas sobre as análises de produtos em linguagem natural com dados refinados.
 
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
| 03    | Média      | **Análise de Sentimento para Comparação de Produtos**<br><br>Como um funcionário do departamento de compras, com base nas reviews fornecidas pelos consumidores, eu quero que a IA identifique o sentimento nas reviews, como comentários positivos, negativos ou neutros, para que eu possa entender a opinião geral dos consumidores sobre um ou mais produtos e a diferença entre eles, para assim priorizar as melhores opções de compra.<br> | 13         | 2      | RF3, RF4                 |
| 04    | Média      | **Histórico de Conversa**<br><br>Como um funcionário do departamento de compras, eu quero interagir com um chatbot que responda minhas dúvidas sobre produtos com base no banco de dados de reviews e notas (B2W) e com o auxílio do histórico das perguntas feitas por mim e respostas fornecidas pelo chat anteriormente. <br>| 13         | 2      |               RF6              |
| 05    | Média      | **Implementação da interface front-end**<br><br>Como um funcionário do departamento de compras, quero visualizar uma interface simples de navegação para que eu tenha maior facilidade de interagir com o chat bot. <br>| 31         | 2      | RNF5    |

</br>

## 📌 DOR
 
### 📄 User Stories e Critérios de Aceitação
 
**US #3:**  Como um funcionário do departamento de compras, com base nas reviews fornecidas pelos consumidores, eu quero que a IA identifique o sentimento nas reviews, como comentários positivos, negativos ou neutros, para que eu possa entender a opinião geral dos consumidores sobre um ou mais produtos e a diferença entre eles, para assim priorizar as melhores opções de compra.
 
**Critérios de aceitação:**
 
- AC1. Classificação dos reviews em positivo, neutro ou negativo. Exemplo: Pergunta: "O Notebook da marca X e modelo Y é bom?" Resposta: "Ele possuí a maioria das avaliações positivas, com destaque em X,Y,Z"
- AC2. Resposta clara e intuitiva.
- AC3. Funciona para diferentes categorias de produtos.
- AC4. Pelo menos um produto recomendado por consulta. Exemplo: Pergunta: "Me recomende um notebook para jogos" Resposta: "Notebook X"
- AC5. Recomendações personalizadas com base em popularidade e nota.
- AC6. Comparação de pelo menos 2 produtos similares. Exemplo: Pergunta: "Qual notebook tem um melhor custo benefício?" Resposta: "Notebook X (tais beneficios), Notebook Y (tais beneficios)"
- AC7. Visualização lado a lado dos produtos.
- AC8. Filtragem por categorias ou características específicas.
</br>

**US #4:** Como um funcionário do departamento de compras, eu quero interagir com um chatbot que responda minhas dúvidas sobre produtos com base no banco de dados de reviews e notas (B2W) e com o auxílio do histórico das perguntas feitas por mim e respostas fornecidas pelo chat anteriormente.
 
**Critérios de aceitação:** </br>
- AC1. Quando o usuário fizer uma pergunta no chat, sua pergunta deve ser salva no histórico da conversa
- AC2. A pergunta salva no histórico pode ser usada posteriormente como referência numa próxima pergunta para obter respostas mais precisas e dentro do contexto mencionado previamente.
- AC3. O chat deve considerar todas as perguntas feitas pelo usuário para contextualizar suas próximas respostas.

</br>

**US #5:** Como um funcionário do departamento de compras, quero visualizar uma interface de navegação para que eu tenha maior facilidade de interagir com o chatbot.
 
**Critérios de aceitação:**

- AC1. O usuário deve visualizar uma interface gráfica composta por uma unica tela 
- AC2. A interface deve ser composta por retângulos de texto ao lado direito para cada pergunta e lado esquerdo para respostas
- AC3. A interface deve conter um campo de input na parte inferior da tela para digitar perguntas
- AC4. A interface deve conter um botão para enviar a pergunta para o chat ler o que foi escrito.
- AC5. A interface deve seguir o design de acordo com o Figma apresentado na história.

 
</br>

### 📄 Protótipo - Figma
<img src="https://github.com/4DeskGroup/API-2024.2/blob/main/docs%20sprints/figma.jpg?raw=true">

 
## 💾 Dados para IA

Para essa entrega, os dados utilizados para construção do chat bot com IA foram a partir do repositório https://huggingface.co/datasets/ruanchaves/b2w-reviews01

</br>

## 🖥️ Entrega
 
![Meu GIF](https://github.com/4DeskGroup/API-2024.2/blob/main/docs%20sprints/sprint2.gif)

### Link do vídeo no youtube
[Assista ao vídeo da entrega no YouTube](https://youtu.be/O2votaqPgYQ?si=yEo_fwVbvSeCX49m)
 
</br>

</details>



<details>
<summary> <strong>Sprint 3</strong> </summary>
  

## 🎯 MVP
O MVP da terceira entrega permitirá que a IA forneça recomendações de produtos baseadas nas opiniões de consumidores de segmentos específicos, ajudando o funcionário do departamento de compras a tomar decisões mais direcionadas. A interface será refinada para garantir uma navegação intuitiva com uma identidade visual agradável e fácil de usar, melhorando a experiência do usuário final. Além disso, um vídeo tutorial estará disponível para orientar usuários não técnicos no uso eficiente da plataforma, garantindo acessibilidade e usabilidade para todos.

  
## 📃 Backlog da Sprint
 
| Rank | Prioridade | User Story | Estimativa | Sprint | Requisito       |
|------|:----------:|------------|:----------:|:------:|-----------------|
| 6    | Média      | **Recomendações de Produtos por Segmento de Pessoas**<br><br>Como um funcionário do departamento de compras, ao especificar uma categoria de produtos para um público específico, eu quero receber recomendações de produtos dessa categoria com base na tendência de opiniões de pessoas de um mesmo segmento, para que eu possa tomar decisões embasadas sobre quais produtos adquirir para esse grupo.<br> | 13         | 3      | RF2, RF5         |
| 7    | Baixa      | **Sugestões de Pesquisa no Frontend**<br><br>Como um usuário do sistema, eu quero ter acesso a um botão que sugira perguntas mockadas, para que eu possa me basear nas informações do sistema e entender melhor como utilizar o chat para tirar dúvidas sobre produtos.<br>                                                                                                                           | 20         | 3      | RNF5      |
| 8    | Baixa      | **Tutorial em Vídeo**<br><br>Como um usuário final não técnico, eu quero acessar um vídeo tutorial, para que eu possa entender como usar a interface do chatbot de maneira eficiente.<br> | 2          | 3      | RNF4             |


</br>

## 📌 DOR
 
### 📄 User Stories e Critérios de Aceitação
 
**US #6:**  Como um funcionário do departamento de compras, ao especificar uma categoria de produtos para um público específico, eu quero receber recomendações de produtos dessa categoria com base na tendência de opiniões de pessoas de um mesmo segmento, para que eu possa tomar decisões embasadas sobre quais produtos adquirir para esse grupo.
 
**Critérios de aceitação:**
 - AC1: Funcionalidade de recomendação baseada em análise de tendência de opinião
Dado que o usuário está no sistema e especificou uma categoria de produtos para um público específico (Exemplo: Como um designer quero um notebook para trabalho, quais são os melhores para meu caso?), o sistema deve fornecer uma recomendação clara de produto com base nas tendências e preferências identificadas (Recomendação de pelo menos um Notebook para designers baseado em comentários de designers).

- AC2: Justificativa da recomendação
Dado que o sistema recomendou um produto, quando o usuário visualizar a recomendação, então a recomendação deve ser acompanhada de uma justificativa detalhada que explique a escolha, incluindo:
Feedbacks de usuários no segmento especificado, características adequadas que atendem ao público-alvo e considerações de tendências de consumo e preferências do grupo.


			
</br>

**US #7:** Como um usuário do sistema, eu quero ter acesso a um botão que sugira perguntas mockadas, para que eu possa me basear nas informações do sistema e entender melhor como utilizar o chat para tirar dúvidas sobre produtos.
 
**Critérios de aceitação:** </br>

- AC1. Botão de Sugestão de Perguntas:<br>				
		Um botão deve ser adicionado ao frontend com a label "Sugestões de Perguntas", conforme design definido no Figma.			<br>
		Ao clicar no botão, o usuário deve visualizar uma lista de perguntas mockadas, baseadas nos requisitos funcionais.			<br>
- AC2. Perguntas Mockadas:				<br>
		As perguntas devem ser baseadas de acordo com os requisitos funcionais, devendo conter 50 perguntas que serão apresentadas ao usuário 5 dessas perguntas de forma aleatória. Exemploas com as respectivas perguntas e respostas esperadas que serão apresentadas ao usuário:	<br>		
			Pergunta 1: Quais características a Cadeira de Escritório Dot All Black mais se destacam nas avaliações?		<br>
			Pergunta 2: Qual opção de notebook é recomendada de acordo com as reviews dos usuários?		<br>
			Pergunta 3: Quais as principais diferenças entre os notebooks da marca Dell e os da marca Lenovo Ideapad em termos de desempenho e custo-benefício?		<br>
			Pergunta 4: Qual a percepção geral dos usuários sobre o Kit Teclado e Mouse Wireless KM636 Dell em termos de conforto?		<br>
			Pergunta 5: Quais notebooks têm recebido melhores feedbacks de profissionais que trabalham em casa?		<br>

</br>

**US #8:** Como um usuário final não técnico, eu quero acessar um vídeo tutorial, para que eu possa entender como usar a interface do chatbot de maneira eficiente.
 
**Critérios de aceitação:**

- AC1. O vídeo deve cobrir todos os aspectos fundamentais do uso da interface do chatbot.
- AC2. O vídeo deve ter uma duração máxima de 3 minutos.
- AC3. O vídeo deve ser publicado em uma plataforma acessível a todos os usuários finais. 

 
</br>

### 📄 Protótipo - Figma
<img src="https://github.com/4DeskGroup/API-2024.2/blob/main/docs%20sprints/scrn-principal.jpg">

 
## 💾 Dados para IA

Para essa entrega, os dados utilizados para construção do chat bot com IA foram a partir do repositório https://huggingface.co/datasets/ruanchaves/b2w-reviews01

</br>

## 🖥️ Tutorial

### Link do vídeo no youtube do tutorial
[Assista ao vídeo do tutorial no YouTube](https://youtu.be/Yzo6zup9Mxg?si=uh-asarPQKFxIEXY)

## 🖥️ Entrega

![Meu GIF](https://github.com/4DeskGroup/API-2024.2/blob/main/docs%20sprints/sprint-3-entrega.gif)

### Link do vídeo no youtube
[Assista ao vídeo da entrega no YouTube](https://youtu.be/VvczQxSXH4w?si=WqYL17PQ2BzY9ctn)
 
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















