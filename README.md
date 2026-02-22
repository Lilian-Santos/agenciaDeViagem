# ✈️ Agência de Viagens – Formulário Responsivo para Orçamentos

Projeto desenvolvido com **HTML5 e CSS3**, com foco na **criação de formulários completos** e na **implementação de responsividade com Media Queries**, garantindo uma boa experiência em diferentes tamanhos de tela.

---

## 🧩 Sobre o projeto

A **Agência de Viagens** é um site fictício que permite ao usuário:

- 📋 Solicitar um orçamento de viagem  
- 🎯 Informar preferências de hospedagem  
- 🏖️ Visualizar ofertas promocionais  
- 🌿 Explorar destinos turísticos  

O principal objetivo do projeto é praticar:

- Estruturação de formulários  
- Diferentes tipos de inputs  
- Organização com Flexbox  
- Responsividade com Media Queries  

---

## 📝 Estrutura do Formulário

O formulário foi desenvolvido com foco em organização, usabilidade e validação nativa do HTML.

### 👤 Dados Pessoais
- 🔤 `input type="text"` (Nome)  
- 📧 `input type="email"` (Validação automática de e-mail)  
- 📱 `input type="tel"` (Telefone)  

Todos utilizando o atributo **`required`**.

---

### 📅 Dados da Viagem
- 🛫 `input type="date"` (Data da ida)  
- 🛬 `input type="date"` (Data da volta)  

Organizados lado a lado em telas maiores e empilhados em telas menores.

---

### 🌎 Origem e Destino
- 🔽 `select` para cidade de origem  
- 🔽 `select` para cidade de destino  

Permite escolha entre múltiplas capitais brasileiras.

---

### 🛏️ Preferências

#### 👶 Quarto com cama infantil?
- 🔘 `input type="radio"` (Sim / Não)

#### 🏨 Preferências de hospedagem
- ☑️ `input type="checkbox"` para múltiplas opções:
  - Piscina  
  - Wi-fi  
  - Garagem  
  - Suíte  

O uso de `checkbox` permite múltiplas seleções simultâneas.

---

## 🎯 Conceitos aplicados

- ✔️ Estrutura semântica (`header`, `main`, `section`, `footer`)  
- ✔️ Organização de formulário com `label` e `for`  
- ✔️ Validações nativas do HTML5  
- ✔️ Uso de `radio` e `checkbox`  
- ✔️ Layout com Flexbox  
- ✔️ Responsividade com Media Queries  
- ✔️ Uso de fonte externa (Google Fonts – Raleway)  
- ✔️ Organização visual com cards e galerias  

---

## 📱 Responsividade com Media Queries

O projeto utiliza dois principais pontos de quebra:

---

### 📲 Até 768px

- 🔘 Botão do formulário ocupa 100% da largura  
- 🖼️ Galeria de ofertas reorganizada em coluna  
- 🏝️ Cards empilhados verticalmente  
- 📦 Rodapé reorganizado em coluna  

---

### 📱 Até 540px

- 📅 Campos de data empilhados  
- 🌎 Origem e destino exibidos em coluna  
- ☑️ Radio buttons e checkboxes organizados verticalmente  

Esses ajustes garantem melhor leitura e usabilidade em dispositivos móveis.

---

## 🎨 Estilização

O projeto utiliza:

- 🎨 Paleta principal em roxo (#5d15d1)  
- 🖼️ Background com imagem na área do formulário  
- 📐 Flexbox para organização estrutural  
- 🗂️ Cards com `object-fit: cover` para melhor ajuste de imagens  
- 🔠 Fonte personalizada via Google Fonts  

---

## 🖥️ Tecnologias utilizadas

- HTML5  
- CSS3  
- Media Queries  
- Google Fonts  

---

## 📸 Seções do Projeto

### ✈️ Área de Solicitação de Orçamento
Formulário completo com múltiplos tipos de entrada e validação nativa.

### 🎯 Área de Ofertas
Galeria com destaque promocional de até 50%.

### 🌿 Área de Anúncios
Cards informativos com imagem + descrição.

### 📞 Rodapé
Informações de contato e redes sociais.

---

## 📚 Objetivo de aprendizado

Este projeto foi desenvolvido para aprofundar conhecimentos em:

- Estruturação de formulários profissionais  
- Experiência do usuário (UX)  
- Organização visual com Flexbox  
- Adaptação de layout para múltiplos dispositivos  
- Boas práticas em HTML semântico  

---

✨ Projeto desenvolvido para fins de estudo em Front-end.
