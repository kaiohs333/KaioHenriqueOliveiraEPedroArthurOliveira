# Red Teaming Automatizado de LLMs em Domínios Críticos

> Research on automated red teaming of Large Language Models in critical domains (health, financial, legal) using a domain-aware vulnerability assessment approach.

---

## Sobre a pesquisa

A pesquisa investiga vulnerabilidades de Modelos de Linguagem de Grande Escala (*Large Language Models* — LLMs) em domínios críticos — saúde, financeiro e jurídico — por meio de uma abordagem de *red teaming* automatizado sensível ao contexto de aplicação (*domain-aware*).

Diferentemente dos estudos existentes, que avaliam LLMs com *queries* genéricas e foco predominante em ataques *prompt-based*, este trabalho aplica três famílias de ataque — *prompt-based*, *optimization-based* (GCG) e *multi-turn* — sobre modelos especializados por domínio, comparando pares open-source e closed-source.

---

## Modelos a serem avaliados

| Domínio | Open-source | Closed-source |
|---|---|---|
| Saúde | MedLLaMA | Med-PaLM 2 |
| Financeiro | FinMA | BloombergGPT |
| Jurídico | SaulLM-7B | GPT-4 |

---

## Metodologia

1. **Preparação e Dataset** — construção de *queries* adversariais com critérios de violação calibrados por domínio
2. **Execução do Red Teaming** — aplicação dos 3 tipos de ataque sobre pares open/closed por domínio
3. **Ciclo de Ataques e Refinamento** — loop iterativo com registro de ASR por domínio
4. **Análise e Resultados** — comparação *cross-domínio* e *cross-modelo* com proposta de mitigações *domain-aware*

---

## Métricas

| Métrica | Descrição |
|---|---|
| **ASR** | *Attack Success Rate* — taxa de sucesso dos ataques adversariais |
| **TR** | Transferabilidade — eficácia do ataque em modelos distintos do original |
| **Stealthiness** | Similaridade do prompt adversarial com inputs benignos (escala 1–5) |
| **FPR** | *False Positive Rate* — taxa de queries legítimas bloqueadas incorretamente |

---

## Famílias de ataque

- **Prompt-based** — role-play, inversão de instrução e manipulação de contexto
- **Optimization-based (GCG)** — sufixos adversariais otimizados por busca gulosa para maximizar ASR
- **Multi-turn** — conversas persistentes de 8+ turnos que degradam progressivamente o alinhamento do modelo

---

## Referências principais

- Niloy et al. (2025) — *Jailbreaking Large Language Models: A Red Teaming Perspective*. IEEE COMPAS.
- Knowlton et al. (2026) — *Prompt-Based Jailbreaking of Leading LLM Chatbots: A Survey of Attacks and Defenses*. IEEE Transactions on Artificial Intelligence.
- Greshake et al. (2023) — *Not What You've Signed Up For: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection*. ACM AISec.
- Goh et al. (2025) — *Scaling Responsible Generative AI: Automating Red Teaming of LLM Applications*. IEEE CAI.
- Segireddy (2025) — *LLM-Driven Automated Penetration Testing: Architectures, Benchmarks, and Safety Considerations*. IEEE ICSSS.

---

## Autores

**Alunos**
- Kaio H. Silveira
- Pedro A. Oliveira

**Orientadores**
- Cleiton Silva Tavares
- Danilo de Quadros Maia Filho
- João Pedro Oliveira Batisteli
- Leonardo Vilela Cardoso

**Instituição:** PUC Minas — Bacharelado em Engenharia de Software — 2026
