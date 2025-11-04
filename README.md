# 🌐 Projeto Landing Page - IFCE Campus Maranguape

- ## 🧑‍💻 Desenvolvido por

**Dupla:**  
- Maria Jardiele Silva de Souza
- Murilo Silva Rodrigues

## 📘 1. Objetivo do Projeto

O objetivo deste projeto é **criar uma landing page** para promover um **servidor do IFCE - Campus Maranguape**, aplicando todos os **conceitos de HTML e CSS** aprendidos até o momento.

A atividade deve ser desenvolvida **em dupla**, e cada grupo deve escolher **um servidor** como tema do site (professor, técnico administrativo, intérprete de Libras, etc.).  
> ⚠️ **Importante:** Não pode haver repetição de servidor entre as duplas.

---

## ⚙️ 2. Requisitos Técnicos

### 🏠 2.1 Estrutura da Página Principal (`index.html`)

A página principal deve conter:

- **Nome completo do servidor** em destaque (`<h1>`)
- **Foto do servidor** (`<img>`)
- **Pequena biografia** (`<p>`)
- **Menu de navegação** (`<nav>`) com links (`<a>`) para as demais páginas
- Uso de **tags semânticas**: `header`, `section`, `article`, `aside` e `footer`
- **Botão para baixar o currículo** do servidor (`<a href="docs/curriculo.pdf" download>`)

### 🎨 Estilização (CSS)
- Aplicar **tipografia, cores, margens, paddings e posicionamentos** (`relative` e `absolute`)
- **Não utilizar**:
  - `display: flex`
  - `display: grid`

---

## 📄 2.2 Subpáginas Obrigatórias

| Página | Descrição |
|--------|------------|
| `sobre.html` | Informações sobre o servidor: biografia detalhada, fotos, hobbies, etc. |
| `formacao.html` | Formações acadêmicas e experiências profissionais, utilizando listas (`<ul>` e `<ol>`) |
| `disciplinas.html` | (Para professores) Tabela de horários ou disciplinas ministradas |
| `contato.html` | Formulário de contato com os campos: **Nome**, **E-mail**, **Assunto**, **Mensagem** e **Botão de envio** |

### ✉️ Estrutura do Formulário (`contato.html`)

O formulário deve conter:
- `input type="text"` → Nome  
- `input type="email"` → E-mail  
- `select` → Assunto  
- `textarea` → Mensagem  
- `input type="submit"` → Enviar  

---

## 🎨 2.3 Regras de Estilo (CSS)

O arquivo CSS deve estar **externo**, localizado em `css/style.css`.

### Deve conter:
- 🎨 **Cores personalizadas** (plano de fundo, textos, links, etc.)  
- 🖋️ **Fontes estilizadas** (tamanho, cor, tipo)  
- 📦 **Box Model:** uso de `padding`, `margin` e `border`  
- 📍 **Posicionamento:** uso de `position: relative` e `absolute`  
- 💡 **Estilização específica** para:
  - Tabelas  
  - Listas  
  - Links  
  - Formulários  

> 🚫 **Proibido o uso de Flexbox ou Grid Layout** nesta atividade.

---

## 🗂️ 2.4 Estrutura de Pastas

projeto/

│

├── index.html

│

├── html/

│ ├── sobre.html

│ ├── formacao.html

│ ├── disciplinas.html

│ └── contato.html

│

├── css/

│ └── style.css

│

├── img/

│ └── (imagens utilizadas)

│

└── docs/

└── curriculo.pdf


---

## 👨‍🏫 3. Professor Responsável

**Disciplina:** Desenvolvimento Web I  
**Professor:** *Thomaz Maia*  
**Instituição:** IFCE - Campus Maranguape

---

📅 **Projeto - Landing Page | Desenvolvimento Web I - IFCE Campus Maranguape**
