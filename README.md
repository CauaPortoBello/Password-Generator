# 🔒 Password Generator

> Uma aplicação web moderna, responsiva e de alta performance desenvolvida para a geração automatizada de senhas seguras e personalizáveis.

---

## 🔗 Demonstração Prática

O projeto está totalmente funcional e disponível para testes em ambiente de produção através do GitHub Pages.

💻 **Teste o projeto:** [Testar o Password Generator](https://cauaportobello.github.io/Password-Generator/)

---

## 🚀 Sobre o Projeto

O **Password Generator** foi concebido para resolver de forma rápida e intuitiva a necessidade de criação de credenciais de segurança robustas. O sistema mitiga vulnerabilidades permitindo que o utilizador parametrize totalmente a estrutura da string gerada, garantindo conformidade com os requisitos de segurança mais exigentes da web (critérios corporativos, plataformas bancárias e e-commerces).

### Principais Funcionalidades:
* **Controlo Dinâmico de Comprimento:** Definição exata do número de caracteres da senha (suporte de 4 a 128 caracteres).
* **Filtros de Complexidade Avançados:** Opções para inclusão seletiva de:
    * Letras Maiúsculas (`ABCDEFGHIJKLMNOPQRSTUVWXYZ`)
    * Letras Minúsculas (`abcdefghijklmnopqrstuvwxyz`)
    * Números (`0123456789`)
    * Caracteres Especiais (`!@#$%^&*()_-+={}[]|\/?><:;"'.,~``)
* **Garantia de Inclusão Absoluta:** O algoritmo assegura que pelo menos um caractere de cada categoria selecionada estará obrigatoriamente presente na senha gerada.
* **Embaralhamento Criptográfico Robusto:** Implementação do método de ordenação randómica baseado em arrays para evitar padrões previsíveis.
* **Cópia de Alta Performance:** Mecanismo integrado à API nativa do sistema operacional para transferência instantânea para a área de transferência (*clipboard*).
* **Sistema de Feedback (UI/UX):** Integração de notificações visuais interativas (*toasts*) para alertas de sucesso ou de parametrização incorreta.

---

## 🛠️ Tecnologias Utilizadas

A arquitetura do projeto priorizou o uso de tecnologias nativas para garantir o menor tempo de carregamento (*Time to Interactive*) e máxima fluidez visual.

* **HTML5:** Estruturação semântica e acessível dos elementos da interface.
* **CSS3:** Estilização avançada, layout otimizado, uso de variáveis internas e total responsividade para dispositivos móveis e desktops.
* **JavaScript (ES6+):** Lógica de programação assíncrona, manipulação dinâmica do DOM, gestão de eventos e lógica algorítmica para criptografia randómica.
* **Toastify JS:** Biblioteca externa leve para fornecimento de feedback visual premium através de notificações temporizadas na interface.
* **Font Awesome 6:** Biblioteca de vetores e ícones de alta fidelidade para enriquecimento da experiência visual da interface do utilizador.

---

## 📈 Detalhes Técnicos e Validações

O código conta com uma arquitetura baseada em funções isoladas com responsabilidade única, facilitando a manutenção e futuras expansões:

1.  **`getPasswordSize()`:** Valida se a entrada do utilizador é um número válido e restringe o intervalo de segurança estritamente entre 4 e 128 caracteres.
2.  **`getChartTypes()`:** Cria uma matriz de dados dinâmica baseada exclusivamente nos filtros ativados pelo utilizador através dos *checkboxes*.
3.  **`generatePassword()`:** Consolida os tipos de caracteres escolhidos, gera o comprimento solicitado garantindo a presença dos elementos obrigatórios e reorganiza o resultado final de forma totalmente aleatória através de um processamento de conversão *Array-String*.

---
