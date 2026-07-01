# 🌐 STA Web — Automacao de Testes Web 🇧🇷

![Java](https://img.shields.io/badge/Java-8-009C3B?style=flat&logo=openjdk&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-4.0-FFDF00?style=flat&logo=selenium&logoColor=black)
![Cucumber](https://img.shields.io/badge/Cucumber-BDD-002776?style=flat&logo=cucumber&logoColor=white)

Framework modelo para automacao de testes de aplicacoes web (Sistema de Testes Automatizados — STA).

## Visao geral

Projeto-modelo Maven (Java 8) para testes automatizados de sites web. Combina **Selenium WebDriver 4** para interacao com navegadores, **Cucumber** (BDD com Gherkin) para escrita de cenarios, e **ExtentReports** para relatorios HTML. Inclui suporte a DBUnit (validacao em banco), Apache POI (dados em Excel), HtmlUnit/PhantomJS e integracao com Oracle/SQL Server/MongoDB.

Convencao de testes: classes prefixadas com `CT*.java` (Caso de Teste).

## Tecnologias

- **Java 8** / **Maven**
- **Selenium WebDriver 4.0** (Chrome, Firefox)
- **Cucumber 1.2.5** (BDD) + **Gherkin**
- **ExtentReports 3.1** + **cucumber-extentsreport**
- **JUnit 4.13** / **Hamcrest**
- **Apache POI 3.15** (leitura de Excel)
- **DBUnit 2.4** / **MongoDB 3.8** / **Oracle/SQL Server** (JDBC)
- **Log4j 2.13**

## Como usar

```bash
mvn test                    # executa testes CT*.java
mvn surefire-report:report  # gera relatorio
```

## Licenca

Uso interno/educacional.

---
*Feito com 💚💛💙 — cores da bandeira do Brasil 🇧🇷*
