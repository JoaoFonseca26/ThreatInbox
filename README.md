# 🛡️ ThreatInbox - Análise de Emails e Deteção de Fraudes com IA

> **Projeto Final (3.º Ano) - Licenciatura em Engenharia Informática** | **IPCB - EST**

<p align="left">
  <img src="https://img.shields.io/github/repo-size/JoaoFonseca26/ThreatInbox?style=for-the-badge&color=blue" alt="Repo Size">
  <img src="https://img.shields.io/github/languages/count/JoaoFonseca26/ThreatInbox?style=for-the-badge&color=orange" alt="Languages">
  <img src="https://img.shields.io/github/last-commit/JoaoFonseca26/ThreatInbox?style=for-the-badge" alt="Last Commit">
</p>

O **ThreatInbox** é uma plataforma web focada na análise de emails suspeitos (`.eml`) e na literacia em cibersegurança. O sistema permite submeter mensagens de correio eletrónico para avaliar potenciais tentativas de fraude, *phishing* e engenharia social, apresentando um relatório de risco claro e acessível ao utilizador.

---

## 🎯 Objetivo do Projeto

A maioria dos utilizadores tem dificuldade em identificar se um email é legítimo ou malicioso apenas pela sua aparência. O **ThreatInbox** tem como objetivo automatizar a inspeção técnica e semântica de ficheiros `.eml`, combinando a consulta de reputação de ameaças com um modelo de Inteligência Artificial local para explicar os riscos de forma simples e privada.

---

## ✨ Funcionalidades Principais

* **🔍 Página de Scan:** Submissão de ficheiros no formato `.eml` para análise detalhada da mensagem.
* **🦠 Consulta de Reputação (API VirusTotal):** Verificação de segurança dos URLs e anexos presentes no email através de integração com a API do VirusTotal.
* **🧠 Análise Semântica com IA Local:** Processamento local do conteúdo e indicadores do email através de um modelo de Inteligência Artificial para gerar um diagnóstico contextualizado.
* **📊 Relatório de Risco:** Apresentação dos resultados da análise com o nível de risco e a explicação detalhada das ameaças detetadas.
* **📚 Threat Guide:** Secção educativa com guias informativos sobre os principais tipos de esquemas e fraudes por email.
* **❓ Help & FAQs:** Secção de ajuda contendo um guia prático sobre como exportar ficheiros `.eml` a partir dos clientes de email e respostas às perguntas mais frequentes.
* **🌐 Multi-idioma:** Opção para alternar o idioma de visualização da plataforma.

---

## 🏗️ Arquitetura Geral do Sistema

O projeto encontra-se dividido em quatro componentes principais:

1. **Interface Web (Frontend):** Responsável pela interação com o utilizador, submissão de ficheiros `.eml`, visualização do relatório de risco e consulta das páginas informativas (*Threat Guide* e *Help & FAQs*).
2. **Servidor de Aplicação (Backend):** Responsável pela receção do ficheiro `.eml`, extração dos dados necessários para análise e coordenação entre os serviços.
3. **Motor de Inteligência Artificial Local:** Modelo de linguagem executado localmente para realizar a análise semântica e gerar o relatório final, garantindo a privacidade dos dados.
4. **Serviço Externo de Threat Intelligence:** Integração com a API do VirusTotal para validação de links e ficheiros anexados.

---

## 📐 Documentação Técnica

De acordo com o planeamento do Projeto Final de Engenharia Informática, a documentação do sistema inclui:

* **Diagrama de Casos de Uso**
* **Descrição e Especificação dos Casos de Uso**
* **Requisitos Funcionais (RF) e Não-Funcionais (RNF)**
* **Arquitetura do Sistema**
* **Protótipo e Design de Interface (Mockups)**

---

## 🖼️ Interface do Sistema

<p align="center">
  <img src="docs/mockups/Figmas" width="45%" alt="Página Inicial - Scan">
  <img src="docs/mockups/Figmas" width="45%" alt="Submissão de Ficheiro .eml">
</p>

<p align="center">
  <img src="docs/mockups/Figmas/" width="45%" alt="Página Threat Guide">
  <img src="docs/mockups/Figmas" width="45%" alt="Página Help & FAQs">
</p>

---
## 👥 Equipa de Desenvolvimento do projeto

| Foto | Nome | N.º de Aluno | GitHub |
| :---: | :--- | :---: | :---: |
| <img src="https://github.com/JoaoFonseca26.png" width="55"> | **João Fonseca** | `20241259` | [![GitHub](https://img.shields.io/badge/JoaoFonseca26-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JoaoFonseca26) |
| <img src="https://github.com/OscarMVieira.png" width="55"> | **Óscar Vieira** | `20240623` | [![GitHub](https://img.shields.io/badge/OscarMVieira-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/OscarMVieira) |

---


