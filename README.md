# Projeto de Testes - SauceDemo 

##  Objetivo
Validar o fluxo principal de compra e regras de negócio do e-commerce SauceDemo.

##  Cenários de Teste (Exemplo de BDD)

### CT-01: Validar erro no checkout (Campo obrigatório)
**Dado** que o usuário está na tela "Checkout: Your Information"
**Quando** deixa o campo "Last Name" vazio e clica em "Continue"
**Então** o sistema deve exibir a mensagem de erro: "Error: Last Name is required".

---

##  Evidências de Teste

### Bug/Validação: Campo "Last Name" obrigatório
![Evidência de Erro](evidencia.regradenegociook.png)
