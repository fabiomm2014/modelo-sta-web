<h1 align="center">🌐 STA Web — Automação de Testes Web 🇧🇷</h1>

<p align="center">
  <b>Framework modelo para automação de testes de aplicações web.</b><br>
  Sistema de Testes Automatizados (STA) com Selenium WebDriver,
  Cucumber BDD e relatórios ExtentReports.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-8-009C3B?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java 8">
  <img src="https://img.shields.io/badge/Selenium-4.0-FFDF00?style=for-the-badge&logo=selenium&logoColor=black" alt="Selenium">
  <img src="https://img.shields.io/badge/Cucumber-BDD-002776?style=for-the-badge&logo=cucumber&logoColor=white" alt="Cucumber">
  <img src="https://img.shields.io/badge/ExtentReports-3.1-009C3B?style=for-the-badge&logoColor=white" alt="ExtentReports">
  <img src="https://img.shields.io/badge/JUnit-4.13-FFDF00?style=for-the-badge&logo=junit5&logoColor=black" alt="JUnit">
  <img src="https://img.shields.io/badge/Maven-002776?style=for-the-badge&logo=apachemaven&logoColor=white" alt="Maven">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/-009C3B?style=flat-square&color=009C3B" height="6" width="120" alt="">
  <img src="https://img.shields.io/badge/-FFDF00?style=flat-square&color=FFDF00" height="6" width="120" alt="">
  <img src="https://img.shields.io/badge/-002776?style=flat-square&color=002776" height="6" width="120" alt="">
</p>

---

## 📑 Sumário

- [🔎 Visão geral](#-visão-geral)
- [✨ Funcionalidades](#-funcionalidades)
- [🛠️ Tecnologias](#️-tecnologias)
- [🚀 Como usar](#-como-usar)
- [📄 Licença](#-licença)

---

## 🔎 Visão geral

Projeto-modelo **Maven** (Java 8) para testes automatizados de sites web. Combina **Selenium WebDriver 4** para interação com navegadores, **Cucumber** (BDD com Gherkin) para escrita de cenários e **ExtentReports** para relatórios HTML. Inclui suporte a DBUnit (validação em banco), Apache POI (dados em Excel), HtmlUnit/PhantomJS e integração com Oracle/SQL Server/MongoDB.

Convenção de testes: classes prefixadas com `CT*.java` (Caso de Teste).

---

## ✨ Funcionalidades

| Módulo | Descrição |
| :----- | :-------- |
| 🌐 **Automação web** | Selenium WebDriver 4 (Chrome, Firefox) |
| 📝 **BDD** | Cenários em Gherkin com Cucumber |
| 📊 **Relatórios** | ExtentReports HTML + cucumber-extentsreport |
| 📑 **Dados Excel** | Leitura de planilhas via Apache POI |
| 🗄️ **Banco de dados** | DBUnit + Oracle/SQL Server/MongoDB |
| 📧 **E-mail** | javax.mail para notificações |
| 📋 **Logging** | Log4j 2.13 |

---

## 🛠️ Tecnologias

| Camada | Tecnologia |
| :----- | :--------- |
| 💻 **Linguagem** | Java 8 |
| 🌐 **Automação** | Selenium WebDriver 4.0 (Chrome, Firefox) |
| 📝 **BDD** | Cucumber 1.2.5 + Gherkin |
| 📊 **Relatórios** | ExtentReports 3.1 + cucumber-extentsreport |
| 🧪 **Testes** | JUnit 4.13, Hamcrest |
| 📑 **Dados** | Apache POI 3.15 (Excel) |
| 🗄️ **Banco** | DBUnit 2.4, MongoDB 3.8, Oracle, SQL Server |
| 📋 **Logging** | Log4j 2.13 |
| 🔧 **Build** | Maven |

---

## 🚀 Como usar

<details open>
<summary><b>▶️ Executar testes</b></summary>

```bash
mvn test                    # executa testes CT*.java
mvn surefire-report:report  # gera relatório HTML
```

</details>

---

## 📄 Licença

Projeto de uso interno/educacional.

<p align="center">
  <img src="https://img.shields.io/badge/-009C3B?style=flat-square&color=009C3B" height="6" width="120" alt="">
  <img src="https://img.shields.io/badge/-FFDF00?style=flat-square&color=FFDF00" height="6" width="120" alt="">
  <img src="https://img.shields.io/badge/-002776?style=flat-square&color=002776" height="6" width="120" alt="">
</p>

<p align="center"><sub>Feito com 💚💛💙 — cores da bandeira do Brasil 🇧🇷</sub></p>
