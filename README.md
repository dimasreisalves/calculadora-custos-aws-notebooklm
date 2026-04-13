# ☁️ Guia Inteligente: Dominando Custos AWS com NotebookLM

## 🎯 Contexto e Objetivos
Este projeto foi desenvolvido como parte de um desafio da DIO para explorar o poder do NotebookLM na curadoria de conhecimentos complexos. O foco escolhido foi a **Gestão de Custos na AWS (FinOps)**, visando desmistificar o uso da AWS Pricing Calculator e ferramentas de monitoramento.

## 📚 Curadoria de Fontes
Para alimentar a IA, foram utilizadas as seguintes fontes:
1. Documentação Oficial: AWS Pricing Calculator User Guide.
2. Whitepaper: AWS Cost Optimization Pillar.
3. Como controlar e reduzir custos na AWS - Curso Gratuito Amazon Web Services na Prática

## 🧠 Engenharia de Prompts e "Cicatrizes"
### Prompts Testados:
* **Prompt 1:** "Resuma como configurar um alarme no AWS Budgets para um gasto de $50."
* **Prompt 2:** "Como usar o AWS Budgets para evitar surpresas na conta? "

### Cicatrizes (Desafios):
* *Dificuldade:* A IA inicialmente não detalhou a diferença entre custos de transferência de dados regionais vs. globais. 
* *Solução:* Ajustei o prompt solicitando uma tabela comparativa específica para tráfego de saída.

## 🛠️ Materiais Gerados (Entrega Final)
Aqui estão os resultados consolidados da consultoria gerada pela IA:

* **Slides/Estudo Completo:** [Baixe o Guia em PDF aqui](AWS_FinOps_Mastery.pdf)
* **Mapa Mental:** !Mapa Mental: ![Mapa Mental](FinopsAws.png)
* **Glossário de FinOps:**
    * **TCO:** Total Cost of Ownership.
    * **Reserved Instances:** Instâncias com desconto por reserva de longo prazo.
    * **Spot Instances**  Instâncias com até 90% de desconto usando capacidade ociosa. 
    **AWS Budgets**  Ferramenta de alertas para controle de teto de gastos. 
    **Data Transfer Out**  Taxas aplicadas quando dados saem da nuvem AWS para a internet. 

---
⭐ Projeto desenvolvido para o curso de IA da [DIO](https://www.dio.me/).
