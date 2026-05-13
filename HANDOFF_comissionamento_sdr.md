# Handoff · Comissionamento SDR no CIC

> Construir o módulo de Comissionamento do **SDR** dentro do CIC.
> Cabe sob `Pessoas > Grade > SDR` no sidebar do CIC.

---

## 🎯 Definição da cadeira SDR

**SDR = Sales Development Representative.** Faz prospecção ativa, qualificação inicial e **agenda reuniões** com Closer. Em alguns clientes faz inbound (recebe MQL → qualifica → agenda). Em outros faz outbound (cold call · prospecção fria).

**Resultado direto que ele gera:** **CAU realizada** — reunião marcada que efetivamente aconteceu (não cancelada, não no-show).

---

## 🚨 Princípio crítico do SDR · CAU REALIZADA, não agendada

Esse é o princípio mais importante do comissionamento do SDR:

> *"Pagar pelas causas que ele agendar? Não. A gente começa a pagar ele pelas causas realizadas."* (Matheus, áudio 13/05/2026)

### Por quê CAU realizada e não agendada?

| Modelo | Resultado |
|---|---|
| Pagar por CAU **agendada** | SDR força marcação, agenda lead frio/desqualificado, no-show explode, Closer perde tempo, conversão cai |
| Pagar por CAU **realizada** | SDR filtra qualidade, confirma presença, lead chega pronto, conversão sobe |

**A diferença está no alinhamento de incentivo.** CAU realizada alinha o SDR ao resultado real (conversa que aconteceu), não ao output intermediário (marcação no calendário).

---

## 📐 Estrutura de remuneração · 3 linhas

Igual ao Closer, mas com métrica diferente:

| Linha | O que é | Lógica de cálculo |
|---|---|---|
| **1 · Fixo** | Valor de mercado pela cadeira × senioridade | Cadeira-padrão |
| **2 · Comissão** | Valor fixo R$ **por CAU realizada** (não %) | Multiplica # CAUs × R$/CAU |
| **3 · Bônus** | Por meta atingida — **número de CAUs + meta de venda do time** | Escalonado por degraus |

**Total mensal = Fixo + (R$/CAU × Nº CAU Realizadas) + Bônus**

---

## 🪜 Senioridades

Mesma lógica do Closer — 3 senioridades, cada uma com tabela própria:

- **SDR Júnior** — fixo menor, R$/CAU menor, bônus menor
- **SDR Pleno** — valores médios
- **SDR Sênior** — fixo maior, R$/CAU maior, bônus maior

---

## 📊 Estrutura proposta · SDR (template para preencher)

> ⚠️ **Nota:** Matheus não compartilhou tabela real do SDR ainda. Esse é um **template estrutural** a ser preenchido com valores reais. Os números abaixo são **placeholders ilustrativos**.

### Premissas a definir

| Variável | Exemplo | Definição |
|---|---|---|
| Fixo mensal SDR Júnior | R$ 1.800 | Piso de mercado |
| R$ por CAU realizada | R$ 50 – 150 | Calibrar pelo histórico do candidato + meta da empresa |
| Meta básica de CAU/mês | 40 | Para liberar bônus inicial |
| % de no-show esperado | 25-35% | Diferença entre agendada e realizada |

### Tabela de Níveis (template)

| Nível | CAU Realizadas | R$/CAU | $$ Comissão | Fixo | Bônus | F+C+B |
|---|---|---|---|---|---|---|
| 1 | 20 | R$ 50 | R$ 1.000 | R$ 1.800 | R$ 0 | **R$ 2.800** |
| 2 | 30 | R$ 50 | R$ 1.500 | R$ 1.800 | R$ 300 | **R$ 3.600** |
| 3 | 40 | R$ 70 | R$ 2.800 | R$ 1.800 | R$ 600 | **R$ 5.200** |
| 4 | 55 | R$ 70 | R$ 3.850 | R$ 1.800 | R$ 1.000 | **R$ 6.650** |
| 5 | 70 | R$ 100 | R$ 7.000 | R$ 1.800 | R$ 1.500 | **R$ 10.300** |
| 6 | 90 | R$ 100 | R$ 9.000 | R$ 1.800 | R$ 2.500 | **R$ 13.300** |

*(Esses valores são exemplo · validar com cliente)*

### Bônus por meta de venda (extra)

Bônus pode também ser **adicional** atrelado à meta de venda do time:

| Atingiu meta do time | Bônus extra do SDR |
|---|---|
| 80% da meta | R$ 0 |
| 100% da meta | R$ 500 |
| 120% da meta | R$ 1.000 |
| 150% da meta | R$ 2.000 |

Esse bônus extra é independente do nível da tabela acima.

---

## 🧮 Calibração da R$/CAU

A definição do valor por CAU não é arbitrária. Considera:

### 4 variáveis críticas (vide `comissionamento_premissa_v1.md`)

1. **Meta de venda da empresa** — quantas reuniões precisam acontecer para atingir
2. **Ticket médio do produto** — se ticket é alto, vale pagar mais por CAU qualificada
3. **Demanda real** — quantos leads chegam, qual a taxa de qualificação
4. **Pretensão salarial do candidato** — calibrar pela realidade

### Cenário canônico (cliente real do Matheus)

> *"Nós temos a meta de vender R$ 500 mil por mês. Para vender R$ 500 mil, precisamos realizar em torno de 80 reuniões. E nessas 80 reuniões temos conversão de 20% para bater o ticket médio."*

Desdobrando:
- 80 CAU realizadas/mês = 4 SDRs × 20 CAU cada
- Se SDR Pleno faz 20 CAU realizadas → recebe **R$ 50-100/CAU = R$ 1.000-2.000 comissão**
- Mais Fixo (R$ 1.800-2.500) + Bônus de meta
- Total mensal **R$ 3.500-5.500** para SDR Pleno em mês padrão

---

## 🚫 Anti-padrões específicos do SDR

1. **Pagar por CAU agendada** — gera lixo no funil, no-show explode
2. **Pagar SDR sobre venda fechada** — SDR não tem controle do fechamento (é do Closer); desmotiva e injusto
3. **R$/CAU fixo sem progressão** — não incentiva volume nem qualidade
4. **Fixo abaixo do mercado** — SDR bom não fica; alta rotatividade no ponto mais difícil de contratar
5. **Bônus só por meta da empresa** — SDR pode ter feito tudo certo e ainda assim não bater (porque depende do Closer); precisa de bônus pelas próprias atividades também

---

## 🛠️ Implementação no CIC

### Posição no sidebar

```
SIDEBAR
└── 4 PILARES
    └── Pessoas
        └── Grade
            └── SDR  ← essa tela
                ├── Júnior
                ├── Pleno
                └── Sênior
```

### Tela "Grade SDR"

**Layout sugerido:**

```
┌──────────────────────────────────────────────────────┐
│ Grade · SDR  [Júnior ▾ Pleno · Sênior]               │
│                                                      │
│ Premissas do cliente                                 │
│ ┌──────────────────────────────────────────────────┐ │
│ │ Fixo SDR Júnior      [R$ 1.800           ▾]      │ │
│ │ Meta CAU/mês básica  [40                 ▾]      │ │
│ │ Número de níveis     [6                  ▾]      │ │
│ └──────────────────────────────────────────────────┘ │
│                                                      │
│ Tabela de Níveis                                     │
│ ┌──┬──────┬──────┬───────┬─────┬─────┬─────┐         │
│ │N │CAU R │R$/CAU│ $$ Com│ Fixo│ Bons│F+C+B│         │
│ ├──┼──────┼──────┼───────┼─────┼─────┼─────┤         │
│ │ 1│  20  │   50 │ 1.000 │1.800│    0│2.800│         │
│ │ 2│  30  │   50 │ 1.500 │1.800│  300│3.600│         │
│ │..│ ...  │  ... │  ...  │ ... │ ... │ ... │         │
│ │ 6│  90  │  100 │ 9.000 │1.800│2.500│13.300│        │
│ └──┴──────┴──────┴───────┴─────┴─────┴─────┘         │
│                                                      │
│ Bônus extra por meta do time (opcional)              │
│ ┌────────────────────────────────────────────────┐   │
│ │ 100% da meta = R$ 500                          │   │
│ │ 120% da meta = R$ 1.000                        │   │
│ │ 150% da meta = R$ 2.000                        │   │
│ └────────────────────────────────────────────────┘   │
│                                                      │
│ [+ Adicionar nível] [Salvar grade]                   │
└──────────────────────────────────────────────────────┘
```

### Comportamentos

1. **Campos editáveis:**
   - Fixo (input R$)
   - Meta CAU/mês (input nº)
   - Número de níveis (1 a 20)
   - Por linha: CAU Realizadas, R$/CAU, Bônus

2. **Cálculos automáticos:**
   - **$$ Comissão** = CAU Realizadas × R$/CAU
   - **F+C+B** = Fixo + $$ Comissão + Bônus
   - **Bônus extra por meta do time** (calcula separadamente se aplicável)

3. **Validações:**
   - CAU Realizadas crescente por linha
   - F+C+B sempre crescente
   - R$/CAU pode ser estável ou crescente, não decrescente

4. **Integração com Pipedrive (futuro):**
   - Quando MCP Pipedrive estiver completo, puxar nº de CAU realizadas automaticamente
   - Calcular comissão do mês sem input manual

### Integração com COC

Comissão SDR alimenta **Custo Variável · Time Comercial** do COC mensal (mesma regra do Closer).

---

## 🔴 Pendências (precisam de input do Matheus)

1. **Valores reais de Fixo SDR (Júnior/Pleno/Sênior)** — não compartilhado ainda
2. **R$/CAU realista** — depende do cliente; entrevistar o histórico salarial
3. **Tabela de níveis específica** — quantos níveis e em que faixas
4. **Política de no-show** — se o lead cancela <24h antes, conta como realizada?
5. **Mecânica do bônus** — só por CAU própria, ou também por meta de venda do time?
6. **Pagamento de bônus team-based** — se meta do time bateu mas SDR só atingiu Nível 2, recebe bônus extra?
7. **Diferenças por canal** (Inbound vs Outbound) — SDR de outbound geralmente tem comissão maior por CAU porque o esforço é maior

---

## 🔗 Referências cruzadas

- **`comissionamento_premissa_v1.md`** — filosofia geral · 4 variáveis críticas · 3 princípios
- **`metodologia-werev/references/12-benchmark-pessoas.md`** — benchmark de custo de contratação · validação externa
- **`HANDOFF_coc_para_cic.md`** — módulo COC onde a comissão entra como Custo Variável
- **`HANDOFF_comissionamento_closer.md`** — handoff do Closer (similar estrutura)
- **`HANDOFF_comissionamento_head.md`** — handoff do Head (estrutura diferente)

---

## 📞 Frase de kickoff pro chat do CIC

```
Preciso implementar a tela "Grade SDR" dentro do CIC,
sob Pessoas > Grade. Esse handoff explica tudo:
estrutura 3 linhas (Fixo + R$/CAU Realizada + Bônus),
métrica-base CAU REALIZADA (nunca agendada),
3 senioridades (Jr/Pleno/Sr), template de níveis,
integração com COC e Pipedrive (futuro).
Anexo HANDOFF_comissionamento_sdr.md.
Identidade ICP. Form editável na tela.
Vários campos pendentes de input do Matheus —
implementar com placeholders e marcar.
```

---

*Handoff criado em 13/05/2026 · Origem: chat de metodologia · Próximo passo: implementação no chat do CIC.*
