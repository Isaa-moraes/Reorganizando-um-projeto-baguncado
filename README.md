# 🛒 Projeto Loja Virtual — Organização de Estrutura

![Status](https://img.shields.io/badge/status-conclu%C3%ADdo-brightgreen)
![SENAI](https://img.shields.io/badge/SENAI-Programa%C3%A7%C3%A3o%20Back--end-blue)
![License](https://img.shields.io/badge/license-educacional-lightgrey)

---

## 📌 Sobre o Projeto

Este repositório contém a **reorganização completa da estrutura de um projeto de Loja Virtual**, que anteriormente estava desorganizado, com arquivos de **front-end e back-end misturados**, nomes fora do padrão e ausência de boas práticas.

O objetivo foi aplicar conceitos de **organização de projetos**, **padronização de nomenclatura** e **separação de responsabilidades**, conforme solicitado em atividade do **SENAI**.

---

## 🎯 Objetivos

- Identificar problemas estruturais no projeto original  
- Padronizar nomes de arquivos e pastas  
- Separar corretamente **Front-end (React)** e **Back-end (API)**  
- Organizar pastas por responsabilidade  
- Remover arquivos duplicados  
- Adicionar arquivos de configuração essenciais  

---

## 🖥️ Front-end — `loja-frontend`

Aplicação desenvolvida em **React**, responsável pela interface do usuário.

### 📁 Pastas
- **components/** → Componentes reutilizáveis  
- **pages/** → Telas da aplicação  
- **services/** → Comunicação com a API  
- **styles/** → Estilos globais e específicos  

### 🛠 Tecnologias
- React  
- JavaScript  
- CSS  

---

## ⚙️ Back-end — `loja-api`

API responsável pelas regras de negócio, autenticação e gerenciamento de dados.

### 📁 Pastas
- **config/** → Configurações (ex: banco de dados)  
- **controllers/** → Lógica das requisições  
- **middlewares/** → Autenticação e validações  
- **models/** → Modelos de dados  
- **routes/** → Rotas da API  
- **services/** → Regras de negócio  
- **utils/** → Funções utilitárias  

### 🛠 Tecnologias
- Node.js  
- Express  
- JavaScript  

---

## ✅ Boas Práticas Aplicadas

- Separação de responsabilidades  
- Padronização de nomenclatura (PascalCase e kebab-case)  
- Organização por camadas  
- Exclusão de arquivos duplicados  
- Uso de arquivos de configuração (`.env`, `.gitignore`, `README.md`)  

---

## 👩‍💻 Autora

**Isadora Aquino Moraes**  
Estudante de Programação Back-end — SENAI  

---

## 📚 Observação

Projeto desenvolvido com **finalidade educacional**, focado em organização de código e arquitetura de software.

---
