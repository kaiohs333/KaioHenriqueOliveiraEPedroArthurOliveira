# Red Teaming Automatizado de Large Language Models em Domínios Críticos: Uma Abordagem de Avaliação de Vulnerabilidades Domain-Aware

## 📌 Descrição do Projeto
Este repositório contém os artefatos desenvolvidos para o Trabalho de Conclusão de Curso (TCC) do curso de Engenharia de Software da PUC Minas.

A pesquisa investiga vulnerabilidades de segurança em Large Language Models (LLMs) por meio de técnicas de Red Teaming Automatizado Domain-Aware aplicadas a domínios críticos, como saúde, financeiro e jurídico.

O estudo busca analisar como diferentes famílias de ataques adversariais impactam modelos open-source e closed-source, avaliando a robustez dos mecanismos atuais de defesa em contextos de alta criticidade.

---

## 👨‍🎓 Alunos
- Pedro Arthur Oliveira Silva
- Kaio Henrique Silveira

---

## 👨‍🏫 Orientadores
- Cleiton Silva Tavares
- Danilo de Quadros Maia Filho
- João Pedro Oliveira Batisteli
- Leonardo Vilela Cardoso

---

## 🎯 Objetivo Geral
Avaliar vulnerabilidades de Large Language Models por meio de red teaming automatizado domain-aware em domínios críticos.

---

## 🎯 Objetivos Específicos
- Desenvolver um dataset de queries adversariais específicas para saúde, finanças e direito.
- Avaliar a eficácia comparativa de ataques Prompt-Based, Optimization-Based e Multi-Turn.
- Comparar vulnerabilidades entre modelos open-source e closed-source.
- Identificar diferenças de comportamento entre domínios críticos.
- Propor diretrizes de mitigação baseadas nas vulnerabilidades identificadas.

---

## 🔬 Problema de Pesquisa
Grande parte da literatura atual avalia vulnerabilidades em LLMs utilizando queries genéricas, sem considerar particularidades semânticas, regulatórias e contextuais de domínios críticos.

Dessa forma, surge a seguinte questão de pesquisa:

> Como a eficácia de ataques de jailbreak varia entre domínios críticos e em que medida as defesas atuais são insuficientes nesses contextos?

---

## 🧠 Fundamentação da Pesquisa
A pesquisa se fundamenta em conceitos de:

- Engenharia de Software
- Segurança de Software
- Red Teaming Automatizado
- Jailbreaking de LLMs
- Adversarial Attacks
- Prompt Injection
- Avaliação Experimental de IA

A proposta aplica princípios de Engenharia de Software, como automação, experimentação controlada e uso de métricas quantitativas para avaliar LLMs como componentes críticos de software.

---

## 📊 Métricas Avaliadas
Os experimentos utilizarão as seguintes métricas:

- ASR (Attack Success Rate)
- Transferability
- Stealthiness
- FPR (False Positive Rate)

---

## 🧪 Metodologia
A pesquisa segue uma abordagem experimental quantitativa composta por quatro etapas principais:

1. Preparação do Dataset Domain-Aware
2. Execução do Red Teaming Automatizado
3. Ciclo de Ataques e Refinamento
4. Análise Cross-Domínio e Cross-Modelo

---

## 🧱 Estrutura do Repositório

```bash
📁 Artigo/
 ├── Referencias/
 ├── PDF/
 ├── Overleaf/
 
📁 Divulgação/
 ├── Apresentação/
 
📁 Dataset/

📁 Experimentos/

📁 Documentação/

README.md
📄 Slides da Apresentação

Os slides do projeto encontram-se em:

Divulgação/Apresentação/
📑 Documento no Overleaf

https://www.overleaf.com/read/ctryrxdcmkwv#9f087b

📚 Trabalhos Relacionados

Os principais trabalhos utilizados como base para esta pesquisa incluem:

Niloy et al. (2025)
Knowlton et al. (2026)
Yang et al. (2025)
Chao et al. (2025)
Segireddy (2025)

Os artigos encontram-se disponíveis na pasta:

Artigo/Referencias/
🛠 Tecnologias e Ferramentas
Python
Jupyter Notebook
HuggingFace
OpenAI API
LaTeX
Overleaf
🏫 Instituição

Pontifícia Universidade Católica de Minas Gerais (PUC Minas)

Curso: Engenharia de Software
Ano: 2026
