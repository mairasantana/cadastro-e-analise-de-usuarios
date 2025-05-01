# 🧩 Sistema de Cadastro e Análise de Usuários

**Projeto:** Sistema de Cadastro e Análise de Usuários  
**Curso:** *Vem pra Neuro, mulher* – Neurotech e Télos  
**Nível:** Nível 04 Neurotech – Iniciando a Decolagem + Especialização  
**Professora:** Aline Soares  
**Aluna:** Maíra Letícia Ferreira  

---

## 🎯 Objetivo

Este programa foi desenvolvido para oferecer uma solução simples e eficiente de gerenciamento de usuários, permitindo:

- ✅ Cadastrar novos perfis com nome, idade e cidade  
- ✅ Listar todos os usuários registrados  
- ✅ Filtrar usuários por idade mínima  
- ✅ Gerar estatísticas básicas (média de idade, total de usuários, distribuição por cidade)  

Essas informações apoiam decisões rápidas e análises iniciais sobre o perfil da base de usuários.

---

## 💻 Ferramentas Utilizadas

Este repositório contém um programa **CLI (Command Line Interface)** que permite executar todas as funcionalidades acima diretamente pelo terminal.  
É uma prova de conceito didática para demonstrar:

- Lógica de programação
- Organização de funções
- Boas práticas em Python

O projeto foi **desenvolvido e testado no Visual Studio Code (VS Code)**, garantindo um fluxo de trabalho moderno, limpo e produtivo.

---

## 🛠️ Passo a Passo do Algoritmo

### 🔹 Passo 1: Criando a Estrutura de Dados
- Dicionário `usuarios` armazena os dados em memória.
- Variável `proximo_id` gera IDs únicos.

### 🔹 Passo 2: Criando Funções para o Cadastro
- Função `cadastrar_usuario()` insere novos registros com nome, idade e cidade.

### 🔹 Passo 3: Criando Funções para Analisar Usuários
- `listar_usuarios()` – Exibe todos os cadastros.
- `filtrar_por_idade()` – Mostra apenas usuários com idade mínima definida.
- `estatisticas_usuarios()` – Calcula e exibe média, mínima, máxima e total de usuários.

### 🔹 Passo 4: Criando um Menu Interativo
- Interface simples no terminal com opções numeradas para interagir com o sistema.

---

## 📊 Resultados e Impacto

Este sistema oferece um **retrato em tempo real do público cadastrado**, revelando idade média, extremos etários e concentração geográfica.  
Essas informações ajudam a direcionar campanhas, ofertas e estratégias de suporte.  
Além disso, o acompanhamento do total de usuários mostra a tração do sistema e permite detectar falhas de UX por meio de dados inconsistentes (outliers), garantindo uma base confiável para análises futuras.

---

📁 *Sinta-se à vontade para clonar, testar e evoluir este projeto!*
