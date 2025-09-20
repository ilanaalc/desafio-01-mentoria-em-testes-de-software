# Desafio #01: Teste de Produto com IA Generativa

Este projeto foi desenvolvido como parte de um desafio da mentoria **M2.0 em Testes de Software do Júlio de Lima**.
Nosso objetivo era aplicar a mentalidade de testes de software de pessoas referências na área como Glenford Myers, Michael Bolton e Elisabeth Hendrickson em um e-commerce da nossa escolha, utilizando prompts para a IA Generativa como forma de nos apoiar no levantamento de testes, melhoria para títulos de defeitos que mostrem de forma mais clara o impacto para o negócio e também na identificação de riscos com base nos defeitos encontrados.

🧠O desafio foi realizado em conjunto com os seguintes alunos da turma 2:
- Bruna Gomes ([Link do LinkedIn](https://www.linkedin.com/in/bruna-gomes-b055b778/))
- Douglas Lang ([Link do LinkedIn](https://www.linkedin.com/in/douglas-lang-40457b10/))
- João Coutinho ([Link do LinkedIn](https://www.linkedin.com/in/joao-vitor-carvalho-coutinho/))
- Larissa Freitas ([Link do LinkedIn](https://www.linkedin.com/in/larissa-de-sousa-freitas-091974254))
---
### **Abordagem e Metodologia**

💡Utilizamos as mentalidades de teste de **Glenford Myers** e **Michael Bolton** como referência

💡Para otimizar o processo, contamos com o apoio do **ChatGPT** como IA Generativa, seguindo prompts estruturados com os elementos: **Objetivo**, **Contexto**, **Regras**, **Exemplo** e **Formato**.

💡Para a organização das tarefas, usamos a ferramenta **Trello**, dividindo o trabalho em duas "user stories". Sendo que a primeira focou no desenvolvimento e execução dos testes, enquanto a segunda, na estruturação do material de entrega. Cada integrante foi responsável por testar uma seção específica do site com o objetivo de aplicar os prompts estruturados para a identificação dos testes com base nas mentalidades, realizar os testes, fazer o levamento de defeitos e riscos associados para o negócio.

---
### **E-commerce e Escopo de Teste**

* **E-commerce Testado:** `https://www.fusqueijao.com.br/`
* **Seções Testadas:**
    * A. Seção de Navegação e Menus
    * B. Busca e Catálogo de Produtos
    * C. Seção de Fluxo de Compra e Carrinho
    * D. Cadastro, Login e Mobile
    * E. Finalização do Pedido e Pagamento

---
### ✅**Resultados: Defeitos e Impactos no Negócio**

Identificamos diversos defeitos que podem impactar negativamente a experiência do usuário e os resultados do negócio. Abaixo estão alguns exemplos dos problemas encontrados e seus potenciais riscos.

* **Cadastro com Senha Fraca:** O sistema permite senhas de apenas um caractere, o que aumenta o risco de invasões e fraudes.
  * Isso pode comprometer dados e a confiança do cliente, gerando perdas financeiras para o e-commerce.

* **Restrição de Idade Ineficaz:** Mesmo informando ser menor de idade, o sistema permite navegar e selecionar produtos alcoólicos.
  * A empresa pode sofrer sanções legais e prejudicar sua reputação.

* **Navegação Inacessível por Teclado:** Submenus não são acessíveis para usuários que dependem exclusivamente do teclado.
  * A falta de conformidade com a acessibilidade pode resultar em perda de vendas e riscos legais.

* **Problemas na Busca:** A busca exibe produtos não relacionados ao inserir caracteres especiais.
  * Transmite falta de profissionalismo e gera desconfiança.
  
* **Desconto Não Aplicado:** Ao trocar a forma de pagamento para PIX, o desconto anunciado não era aplicado.
  * Essa inconsistência pode levar o cliente a abandonar o carrinho e pode ser considerada propaganda enganosa, o que pode resultar em multas para a marca.

---
### 📖**Notas Adicionais**

* Todos os prompts foram criados com base no que foi ensinado durante a mentoria.
* A organização do projeto no Trello permitiu que todos os integrantes participassem da execução de testes, do levantamento de defeitos e da análise de riscos.
* Uma etapa de revisão foi realizada por todos os membros do grupo para garantir a qualidade final da entrega.



### 📌README.md por:

👩🏽‍💻 Ilana Alcantara ([Link do LinkedIn](https://www.linkedin.com/in/ilana-alcantara/))
