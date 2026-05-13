# Handoff · Comissionamento Closer no CIC

> Construir o módulo de Comissionamento do **Closer** dentro do CIC.
> Cabe sob `Pessoas > Grade > Closer` no sidebar do CIC.

---

## 🎯 Definição da cadeira Closer

**Closer = vendedor que fecha a venda.** Atende reuniões qualificadas (CAU realizadas pelo SDR), aplica framework de venda (SPIN→NEPQ), conduz objeções e fecha contrato.

**Resultado direto que ele gera:** receita fechada (faturamento bruto).

---

## 📐 Estrutura de remuneração · 3 linhas

Toda remuneração de Closer na metodologia WeRev é composta por:

| Linha | O que é | Lógica de cálculo |
|---|---|---|
| **1 · Fixo** | Valor de mercado pela cadeira × senioridade | Pesquisa de mercado · benchmark · cadeira-padrão |
| **2 · Comissão** | % progressivo sobre faturamento | Cresce em **tiers** conforme performance mensal |
| **3 · Bônus** | Escalonado por nível de performance | Tabela manual · cresce em degraus |

**Total mensal = Fixo + Comissão + Bônus (F+C+B)**

---

## 🪜 Senioridades (cada uma tem sua tabela)

A cadeira Closer tem 3 níveis de senioridade, **cada um com sua tabela própria**:

- **Closer Júnior** — fixo menor, % menor, bônus menor
- **Closer Pleno** — fixo médio, % média, bônus médio
- **Closer Sênior** — fixo maior, % maior, bônus maior

A tabela detalhada abaixo é do **Closer Júnior** especificamente (exemplo real de cliente). Closer Pleno e Sênior seguem a **mesma lógica estrutural**, com valores proporcionalmente maiores.

---

## 📊 Exemplo concreto · Closer Júnior (cliente real)

**Premissas:**
- Ticket médio: **R$ 25.000** (constante)
- Fixo: **R$ 2.500/mês** (independe do nível atingido)
- Número de níveis de performance: **7** (varia por empresa)

### Tabela completa

| Nível | Faturamento | Nº Vendas | % Comissão | $$ Comissão | Fixo | Bônus | **F+C+B** |
|---|---|---|---|---|---|---|---|
| **1** | R$ 160.000 | 6 | 0,5% | R$ 800 | R$ 2.500 | R$ 0 | **R$ 3.300** |
| **2** | R$ 180.000 | 7 | 0,5% | R$ 900 | R$ 2.500 | R$ 600 | **R$ 4.000** |
| **3** | R$ 220.000 | 9 | 0,7% | R$ 1.540 | R$ 2.500 | R$ 2.000 | **R$ 6.040** |
| **4** | R$ 280.000 | 11 | 0,7% | R$ 1.960 | R$ 2.500 | R$ 3.000 | **R$ 7.460** |
| **5** | R$ 360.000 | 14 | 1,0% | R$ 3.600 | R$ 2.500 | R$ 5.000 | **R$ 11.100** |
| **6** | R$ 500.000 | 20 | 1,5% | R$ 7.500 | R$ 2.500 | R$ 7.000 | **R$ 17.000** |
| **7** | R$ 650.000 | 26 | 1,5% | R$ 9.750 | R$ 2.500 | R$ 8.000 | **R$ 20.250** |

### O que essa tabela ensina

**1. "Nível" = patamar de performance do mês, NÃO senioridade**
O mesmo Closer Júnior pode estar no Nível 3 num mês e Nível 6 no próximo. Ele **sobe e desce** entre níveis conforme atinge o faturamento.

**2. Fixo é cadeira-padrão (não escala com nível)**
R$ 2.500 em todos os 7 níveis. Confirma que **o Fixo = piso da cadeira**, independente da performance mensal.

**3. % Comissão tem 4 tiers, não 7 níveis lineares**

| Tier | % | Aplica nos Níveis |
|---|---|---|
| Tier 1 | 0,5% | 1-2 |
| Tier 2 | 0,7% | 3-4 |
| Tier 3 | 1,0% | 5 |
| Tier 4 | 1,5% | 6-7 |

O salto entre Tier 1 e Tier 4 é de **3×**. Vendedor que escala ganha **mais por venda também** — não só mais vendas.

**4. Bônus é meta-escalonado manualmente**
Cresce em degraus distintos: R$0 → R$600 → R$2k → R$3k → R$5k → R$7k → R$8k. Não é fórmula automática — é tabela editável.

**5. Efeito composto na remuneração total**

| Comparação | Faturamento | F+C+B | % sobre faturamento |
|---|---|---|---|
| Nível 1 | R$ 160k | R$ 3.300 | 2,06% |
| Nível 7 | R$ 650k | R$ 20.250 | 3,11% |

Vendedor que **dobra a performance ganha mais que o dobro** — esse é o mecanismo central de incentivo.

---

## 🧮 Lógica de calibração (para outras empresas)

A % de comissão na faixa **0,5% a 1,5%** desse cliente é **abaixo da faixa de mercado** (2% a 5%). Razão:

> *"Vou vender um produto de R$ 100k, mas só 2 por mês. Eu vou ter uma demanda de R$ 10 milhões. Eu não posso dar 5% pra essa pessoa, porque senão ele vai ganhar muito com pouco esforço."* (Matheus, áudio 13/05/2026)

**Regra de calibração da % do Closer:**

| Ticket | Demanda | % sugerida |
|---|---|---|
| Alto (>R$10k) | Baixa volumetria | **0,3% a 1,5%** (esse cliente) |
| Médio (R$1k-10k) | Volume médio | **1,5% a 3,5%** |
| Baixo (<R$1k) | Alta volumetria | **3% a 5%** |

---

## 🚫 Anti-padrões específicos do Closer

1. **Dar % alto em produto caro com baixa demanda** — vendedor ganha muito com pouco esforço, perde fome
2. **Comissão linear (mesma % em todos os patamares)** — não incentiva escala
3. **Bônus sobre Faturamento bruto sem clawback** — se cliente cancela, vendedor leva dinheiro de venda que não virou cash
4. **Fixo abaixo do mercado** — Closer bom não aceita; você atrai só quem está sem alternativa
5. **Comissão sem cap** — se a venda for muito grande pra média, vendedor ganha algo desproporcional

---

## 🛠️ Implementação no CIC

### Posição no sidebar

```
SIDEBAR
└── 4 PILARES
    └── Pessoas
        └── Grade
            └── Closer  ← essa tela
                ├── Júnior
                ├── Pleno
                └── Sênior
```

### Tela "Grade Closer"

**Layout sugerido:**

```
┌──────────────────────────────────────────────────────┐
│ Grade · Closer  [Júnior ▾ Pleno · Sênior]            │
│                                                      │
│ Premissas do cliente                                 │
│ ┌──────────────────────────────────────────────────┐ │
│ │ Ticket Médio          [R$ 25.000          ▾]     │ │
│ │ Fixo Closer Júnior    [R$ 2.500           ▾]     │ │
│ │ Número de níveis      [7                  ▾]     │ │
│ └──────────────────────────────────────────────────┘ │
│                                                      │
│ Tabela de Níveis                                     │
│ ┌──┬──────────┬────┬─────┬───────┬─────┬─────┬─────┐│
│ │N │Faturamto │Vds │  %  │ $$ Co │ Fixo│ Bons│ F+C+B││
│ ├──┼──────────┼────┼─────┼───────┼─────┼─────┼─────┤│
│ │ 1│ 160.000  │  6 │ 0,5%│   800 │2.500│    0│ 3.300││
│ │ 2│ 180.000  │  7 │ 0,5%│   900 │2.500│  600│ 4.000││
│ │..│ ...      │... │ ... │  ...  │ ... │ ... │  ... ││
│ │ 7│ 650.000  │ 26 │ 1,5%│ 9.750 │2.500│8.000│20.250││
│ └──┴──────────┴────┴─────┴───────┴─────┴─────┴─────┘│
│ [+ Adicionar nível] [Salvar grade]                   │
│                                                      │
│ Visualização gráfica · "Onde estou hoje?"            │
│ [bar chart mostrando F+C+B por nível]                │
└──────────────────────────────────────────────────────┘
```

### Comportamentos

1. **Campos editáveis:**
   - Ticket Médio (input R$)
   - Fixo (input R$)
   - Número de níveis (1 a 20 — varia por empresa)
   - Por linha: Faturamento, % Comissão, Bônus

2. **Cálculos automáticos:**
   - **Nº Vendas** = Faturamento ÷ Ticket Médio
   - **$$ Comissão** = Faturamento × % Comissão
   - **F+C+B** = Fixo + $$ Comissão + Bônus
   - **% sobre faturamento** (na linha) = F+C+B ÷ Faturamento × 100

3. **Validações:**
   - Faturamento crescente por linha (alerta se invertido)
   - % Comissão crescente ou estável (não pode regredir entre tiers)
   - F+C+B sempre crescente (sanity check)

4. **Visualização:**
   - Bar chart mostrando F+C+B por nível
   - Highlight do nível atingido no mês atual (cruza com COC do mês)

5. **Toggle entre senioridades:**
   - Tab/dropdown alterna entre Júnior · Pleno · Sênior
   - Cada uma é uma tabela separada salva no banco
   - Estrutura visual igual, valores diferentes

### Integração com COC

A tabela do Closer alimenta o **Custo Variável · Time Comercial** do COC mensal:

- $$ Comissão do mês = entra no Custo Variável
- Bônus do mês = também entra no Custo Variável
- Fixo do mês = entra no Custo Fixo

Quando o COC for atualizado para um mês, ele puxa os valores da Grade do Closer (no nível atingido).

---

## 🔴 Pendências (validar com Matheus antes ou durante implementação)

1. **Tabelas de Closer Pleno e Sênior** ainda não definidas — provavelmente fixo de R$ 4-5k (Pleno) e R$ 6-8k (Sênior), % e bônus proporcionais
2. **Base da % é Faturamento ou Cash Collected?** Premissa atual: **Faturamento** (porque tabela mostra "Faturamento" coluna). Validar.
3. **Pagamento na assinatura ou no cash?** Validar política de clawback
4. **Como o sistema sabe em qual nível o Closer está?** Resposta de Matheus: **pelo Faturamento Realizado no mês**
5. **Renovação tem regra própria?** Ainda não definido
6. **Split entre cadeiras (Closer + SDR na mesma venda)?** Ainda não definido

---

## 🔗 Referências cruzadas (outros arquivos do workspace)

- **`comissionamento_premissa_v1.md`** — filosofia geral · 3 princípios fundadores · 4 variáveis críticas
- **`metodologia-werev/references/12-benchmark-pessoas.md`** — benchmark de mercado · custo de contratação errada · curva Josh Bersin
- **`HANDOFF_coc_para_cic.md`** — módulo COC onde a comissão entra como Custo Variável
- **`HANDOFF_comissionamento_sdr.md`** — handoff do SDR (similar estrutura)
- **`HANDOFF_comissionamento_head.md`** — handoff do Head (estrutura diferente)

---

## 📞 Frase de kickoff pro chat do CIC

```
Preciso implementar a tela "Grade Closer" dentro do CIC,
sob Pessoas > Grade. Esse handoff explica tudo:
estrutura de remuneração 3 linhas (Fixo + Comissão + Bônus),
tabela de níveis progressiva, 3 senioridades (Jr/Pleno/Sr),
exemplo real do Closer Júnior, integração com COC.
Anexo HANDOFF_comissionamento_closer.md.
Identidade ICP. Form editável na tela.
NÃO incluir Comissão WeRev no cálculo (já está fora do COC).
```

---

*Handoff criado em 13/05/2026 · Origem: chat de metodologia · Próximo passo: implementação no chat do CIC.*
