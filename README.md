# LH Games - E-commerce de Jogos com Angular

Este projeto consiste em um layout de site de jogos desenvolvido com o framework Angular, integrando componentes do **Angular Material** e estilização com **Bootstrap**. A aplicação conta com navegação entre as páginas Home (Início) e Login, apresentando um design responsivo com banners rotativos e vitrine de produtos.

> **Observação:** Este projeto faz parte da atividade final da disciplina **"Framework Front-End com Consumo de API"** do curso **"Desenvolvedor FullStack"** do **Senai**.

---

## 🚀 Tecnologias Utilizadas

O projeto foi construído utilizando as seguintes ferramentas e bibliotecas:

* **Angular:** Framework principal para construção da Single Page Application (SPA).
* **Angular Material:** Utilizado para componentes de UI modernos como `mat-toolbar`, `mat-card`, `mat-grid-list`, `mat-button` e `mat-icon`.
* **Bootstrap:** Utilizado para a estrutura de layout (Grid system) e o componente de Carousel de imagens.
* **TypeScript:** Linguagem base para a lógica do Angular.
* **HTML5 & CSS3:** Estrutura e estilização personalizada.

---

## 🛠️ Funcionalidades Implementadas

### 1. Sistema de Rotas
Implementação do roteamento do Angular para permitir a navegação entre:
* `inicio`: Página principal com vitrine de jogos.
* `login`: Tela de autenticação de usuário.

### 2. Interface do Usuário (UI)
* **Menu (Navbar):** Cabeçalho fixo com logo e botões de navegação estilizados com Angular Material.
* **Carousel:** Banner rotativo na página inicial utilizando componentes do Bootstrap para destaque de promoções.
* **Grid de Produtos:** Vitrine de jogos organizada através do `mat-grid-list`, garantindo uma visualização limpa e profissional.
* **Rodapé:** Footer informativo contendo créditos e direitos autorais.

---

## 📁 Estrutura do Projeto

Abaixo, os principais componentes desenvolvidos dentro da pasta `Projeto-Login-Angular`:

```text
src/app/
├── inicio/    # Componente da página principal (Banner e Vitrine)
├── login/     # Componente do formulário de acesso
├── menu/      # Componente de navegação superior
└── rodape/    # Componente de rodapé da aplicação

```
---

## 📦 Como executar o projeto
Para clonar e executar este projeto localmente, siga os passos abaixo no seu terminal:

### 1. Clone o repositório:
```text
git clone [https://github.com/raphasandes/LH-Games---Projeto-FullStack.git](https://github.com/raphasandes/LH-Games---Projeto-FullStack.git)
```
### 2. Entre na pasta do projeto:
```text
cd LH-Games---Projeto-FullStack/Projeto-Login-Angular
```
### 3. Instale as dependências necessárias:
```text
npm install
```
### 4. Execute o servidor de desenvolvimento:
```text
ng serve
```
### 5. Acesse no navegador: Abra o endereço http://localhost:4200/ para visualizar o site.

---
## 👨‍🎓 Créditos
Desenvolvido como critério de avaliação no curso Desenvolvedor FullStack - Senai.
