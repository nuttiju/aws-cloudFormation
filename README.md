# Desafio CloudFormation - Bootcamp Code Girls Santander (DIO)

Este repositório contém a implementação do **primeiro template CloudFormation**, criado como parte do desafio proposto no **Bootcamp Code Girls - Santander na DIO**.  

O objetivo foi praticar **Infraestrutura como Código (IaC)** utilizando AWS CloudFormation, aplicando os conceitos estudados e documentando a experiência para consolidar o aprendizado.

---

## 📌 Objetivo do Desafio
- Implementar a primeira **Stack** utilizando AWS CloudFormation.  
- Praticar os conceitos aprendidos durante as aulas.  
- Criar um repositório bem estruturado no GitHub, documentando o processo.  

---

## 🛠️ O que este template faz?
O template cria um **bucket S3** com as seguintes características:
- Nome fixo: `bucketnutti`  
- **Versionamento habilitado** (mantém histórico de versões dos objetos)  
- **Tags adicionadas** para organização e boas práticas:
  - Projeto: `ExemploCloudFormation`
  - Autor: `JuliaNutti`
  - Ambiente: `Dev`  
- **Outputs configurados**:
  - Nome do bucket criado
  - ARN do bucket criado  

---
