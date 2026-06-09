# 🔒 Password Generator

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white" alt="GitHub Pages" />
</p>

<p align="center">
  <strong>Aplicação web moderna para a geração automatizada de senhas seguras.</strong><br>
  <strong>Modern web application for automated generation of secure passwords.</strong>
</p>

<p align="center">
  <a href="#-português-br">Português-BR</a> • 
  <a href="#-english">English</a>
</p>

---

# Português-BR

## 🔗 Demonstração Prática

O projeto está totalmente funcional e disponível para testes em ambiente de produção através do GitHub Pages.

💻 **Teste o projeto:** [Acessar Password Generator](https://cauaportobello.github.io/Password-Generator/)

---

## 🚀 Sobre o Projeto

O **Password Generator** foi concebido para resolver de forma rápida e intuitiva a necessidade de criação de credenciais de segurança robustas. O sistema mitiga vulnerabilidades permitindo que o utilizador parametrize totalmente a estrutura da string gerada, garantindo conformidade com os requisitos de segurança mais exigentes da web (critérios corporativos, plataformas bancárias e e-commerces).

### Principais Funcionalidades:
* **Controlo Dinâmico de Comprimento:** Suporte de 4 a 128 caracteres.
* **Filtros de Complexidade Avançados:** Inclusão de letras (Maiúsculas/Minúsculas), números e caracteres especiais.
* **Garantia de Inclusão Absoluta:** O algoritmo assegura que pelo menos um caractere de cada categoria selecionada estará presente na senha.
* **Embaralhamento Criptográfico Robusto:** Implementação de ordenação randômica para evitar padrões previsíveis.
* **Cópia de Alta Performance:** Integração com a API de Clipboard para cópia instantânea.
* **Sistema de Feedback (UI/UX):** Notificações visuais interativas (*toasts*) para alertas de sucesso ou erro.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica e acessível.
* **CSS3:** Estilização avançada, variáveis CSS e total responsividade.
* **JavaScript (ES6+):** Manipulação dinâmica do DOM e lógica algorítmica.
* **Toastify JS:** Biblioteca para notificações de feedback visual premium.
* **Font Awesome 6:** Ícones de alta fidelidade para a interface do utilizador.

---

## 📈 Detalhes Técnicos

1. **`getPasswordSize()`:** Valida e restringe o intervalo de segurança entre 4 e 128 caracteres.
2. **`getChartTypes()`:** Cria uma matriz de dados dinâmica baseada nos filtros ativos.
3. **`generatePassword()`:** Consolida os tipos escolhidos e garante a presença dos elementos obrigatórios de forma aleatória.

---

# English-US

## 🔗 Live Demo

The project is fully functional and available for testing in a production environment via GitHub Pages.

💻 **Try the project:** [Access Password Generator](https://cauaportobello.github.io/Password-Generator/)

---

## 🚀 About the Project

The **Password Generator** was designed to quickly and intuitively address the need for creating robust security credentials. The system mitigates vulnerabilities by allowing users to fully parameterize the structure of the generated string, ensuring compliance with the web's most demanding security requirements (corporate criteria, banking platforms, and e-commerce).

### Key Features:
* **Dynamic Length Control:** Set the exact number of characters (supports 4 to 128 characters).
* **Advanced Complexity Filters:** Selective inclusion of:
    * Uppercase Letters (`A-Z`)
    * Lowercase Letters (`a-z`)
    * Numbers (`0-9`)
    * Special Characters (`!@#$%^&*...`)
* **Guaranteed Inclusion:** The algorithm ensures that at least one character from each selected category is mandatory in the generated password.
* **Robust Cryptographic Shuffling:** Implementation of a random sorting method based on arrays to prevent predictable patterns.
* **High-Performance Copy:** Integrated mechanism using the OS native Clipboard API for instant transfer.
* **Feedback System (UI/UX):** Integration of interactive visual notifications (*toasts*) for success or incorrect setup alerts.

---

## 🛠️ Technologies Used

The project architecture prioritized native technologies to ensure the fastest load time (*Time to Interactive*) and maximum visual fluidity.

* **HTML5:** Semantic and accessible UI structuring.
* **CSS3:** Advanced styling, optimized layout, internal variables, and full responsiveness for mobile and desktop.
* **JavaScript (ES6+):** Asynchronous logic, dynamic DOM manipulation, event management, and algorithmic logic for random encryption.
* **Toastify JS:** Lightweight external library for premium visual feedback through timed notifications.
* **Font Awesome 6:** High-fidelity vector and icon library to enrich the user experience.

---

## 📈 Technical Details & Validations

The code features an architecture based on isolated functions with single responsibility:

1. **`getPasswordSize()`:** Validates user input and strictly restricts the security range between 4 and 128 characters.
2. **`getChartTypes()`:** Creates a dynamic data matrix based exclusively on the filters activated by the user through checkboxes.
3. **`generatePassword()`:** Consolidates chosen character types, generates the requested length ensuring mandatory elements, and reshuffles the final result randomly through *Array-to-String* conversion.
