# 🌱 Projeto: Website da ONG Semeando o Futuro  
**Atividade 3 - Dinamismo com JavaScript Avançado**

## 🧩 Sobre  
Esta terceira entrega do projeto tem como foco a **implementação de JavaScript** para transformar a interface — antes estática (HTML e CSS) — em uma aplicação web **dinâmica e interativa**.  

O objetivo principal é demonstrar domínio sobre:  
- Manipulação do **DOM**;  
- Gerenciamento de **eventos**;  
- Criação de **funcionalidades reais** simulando o comportamento de uma aplicação web moderna.

---

## 🛠️ Tecnologias Utilizadas  
- **HTML5**  
- **CSS3**  
- **JavaScript (ES6+)**

---

## 📁 Estrutura de Arquivos  

/
|-- /css/
| |-- style.css (Folha de estilos principal)
|
|-- /js/
| |-- main.js (Arquivo central com o código JavaScript)
|
|-- /images/
| |-- (Imagens utilizadas no site)
|
|-- index.html (Página inicial)
|-- projetos.html (Página de Projetos e Doações)
|-- cadastro.html (Página de Cadastro de Voluntários)
|
|-- README.md (Este arquivo)
---

## ⚙️ Especificações Técnicas Implementadas  

### 🧩 1. Código JavaScript Modular  
O arquivo `main.js` foi estruturado de forma **modular**, com o código dividido por blocos de funcionalidades:  
- **SPA (Single Page Application);**  
- **Validação de Formulário;**  
- **Funções Auxiliares.**  

Essa abordagem garante **legibilidade**, **organização** e **facilidade de manutenção** do código.

---

### 🧭 2. Manipulação do DOM — Sistema de SPA  

Foi desenvolvido um sistema de **Single Page Application (SPA) básico**, que permite a navegação entre as páginas sem recarregar o site.  

- **Navegação Dinâmica:**  
  Ao clicar nos links do menu, o conteúdo da página de destino é carregado dentro da tag `<main>` **dinamicamente**, utilizando a **Fetch API** e manipulação direta do DOM.  

- **Template Vivo:**  
  A tag `<main>` atua como um “container dinâmico”, onde o conteúdo é substituído em tempo real pelo JavaScript, sem a necessidade de recarregar o site.

---

### 🧾 3. Funcionalidade Obrigatória — Verificação de Formulário  

Um sistema completo de **validação de formulário** foi implementado no arquivo `main.js`, garantindo que os dados sejam inseridos de forma correta e padronizada.  

#### 🔍 Validações Incluídas:
- Campos obrigatórios com verificação de preenchimento.  
- Formato de **e-mail** validado via expressão regular.  
- Controle de **quantidade de dígitos** para CPF, CEP e telefone.  
- Bloqueio de caracteres inválidos (permitindo apenas números nos campos numéricos).  

#### 💬 Feedback ao Usuário:
1. **Mensagens de erro** aparecem logo abaixo dos campos inválidos.  
2. **Notificações visuais** informam o status da operação:  
   - 🟢 Verde: envio realizado com sucesso.  
   - 🔴 Vermelho: erros de preenchimento detectados.  

---
