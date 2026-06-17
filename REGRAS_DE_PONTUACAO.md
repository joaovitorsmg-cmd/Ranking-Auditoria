# Programa de Excelência em Auditoria de Estoque — AGROQUIMA
## Como funciona a pontuação (guia para Supervisores)

Este documento explica, de forma simples, **como o Score de cada auditoria é calculado** e **como o Ranking Anual** (o que define a premiação) é montado. O objetivo é que todo supervisor entenda exatamente o que está sendo medido e por quê sua filial ficou com a nota que ficou.

---

## 1. O Score de cada auditoria (por período)

Toda vez que uma filial passa por uma auditoria, ela recebe um **Score daquela auditoria**, que vai de 0 a 100 pontos (+ um bônus de até 5 pontos). Esse score é a soma de 4 critérios:

| Critério | Peso máximo | Como é medido |
|---|---|---|
| **Semente** | 40 pontos | Tudo ou nada: a filial só ganha os 40 pontos se **não tiver nenhuma pendência** (Sem Pendência = 0). Se houver qualquer pendência, o critério vale **0**. |
| **Pedido** | 30 pontos | Tudo ou nada: a filial só ganha os 30 pontos se o **% de Pedido Confirmado for ≥ 95%**. Abaixo de 95%, o critério vale **0** — não existe pontuação parcial. |
| **Vencidos** | 20 pontos | Calculado pelo **% do valor vencido sobre o faturamento da filial no período**. Quanto menor o % de vencidos sobre o faturamento, mais próximo dos 20 pontos. Faixas: até 0,5% = pontuação máxima; até 1% = 35 pts (escala interna); até 2% = 15 pts; acima de 2% = 0. |
| **Canhoto** | 10 pontos | Tudo ou nada: a filial só ganha os 10 pontos se o **% de Canhoto Confirmado for ≥ 95%**. Abaixo de 95%, o critério vale **0**. |

**Regra importante (tudo ou nada):** Pedido e Canhoto **não têm pontuação proporcional**. Não existe "quase lá" — se a filial fechar a auditoria com 94% de Pedido confirmado, por exemplo, o critério Pedido vale **zero** naquela auditoria, mesmo estando muito próximo de 95%. É obrigatório atingir ≥95% em **todas** as auditorias do ano para que a média anual desses critérios se mantenha alta.

### Bônus de Volume (até 5 pontos)
Além dos 100 pontos acima, cada auditoria pode ganhar um **bônus de até 5 pontos**, calculado de forma relativa: a filial com o maior volume de pedidos+canhotos conferidos naquele período/mês ganha o bônus máximo, e as demais ganham proporcionalmente ao seu volume.

**Score da auditoria = Semente + Pedido + Vencidos + Canhoto + Bônus de Volume** (máximo teórico: 105 pontos)

---

## 2. O Ranking Anual (o que vale para a premiação)

O **Ranking Anual** é o ranking oficial da premiação. Ele é calculado pela **média de todos os Scores de auditoria** que a filial teve durante o ano (todas as rodadas/visitas).

> Exemplo: se a filial teve 4 auditorias no ano com scores 90, 85, 95 e 88, a média anual será (90+85+95+88)/4 = 89,5 pontos.

### 2.1. Critério extra: Nota Média de Auditoria (quando carregada)

Ao longo do ano, a Auditoria Interna pode importar uma planilha separada com o resultado consolidado das auditorias formais (coluna "Status" = Finalizada) de cada filial. Essa nota tem **peso igual ao da Semente** e, quando carregada, muda a composição do score anual:

- **Sem a Nota de Auditoria carregada:** Semente 40 + Pedido 30 + Vencidos 20 + Canhoto 10 (fórmula padrão acima).
- **Com a Nota de Auditoria carregada para a filial:** Semente passa a valer 20, e a Nota de Auditoria também vale 20 (peso igual entre as duas) — Pedido, Vencidos e Canhoto continuam exatamente com os mesmos pesos (30/20/10).

**Regras dessa nota:**
- Só entram na média **auditorias com Status = "Finalizada"**. Auditorias "Em andamento" são ignoradas, mesmo que já tenham uma pontuação lançada.
- A data é considerada apenas por **mês/ano** (não importa o número da auditoria) — não há filial auditada duas vezes no mesmo mês.
- Essa nota pode ser **incluída ou removida a qualquer momento** pela área de Auditoria, para dar uma prévia de quem está na frente mesmo antes do fechamento do ano. Toda inclusão/remoção é sincronizada automaticamente com a base na nuvem.

### 2.2. Critérios de desempate
Quando duas ou mais filiais ficam com a mesma média de score, o desempate segue esta ordem:
1. Maior score médio (já citado).
2. Menor % de vencidos sobre o faturamento.
3. Maior volume total conferido (pedidos + canhotos).
4. Menor reincidência de vencidos (filiais com vencidos em 2 ou mais auditorias no ano perdem no desempate).

### 2.3. Selos especiais na tabela
- **REINC** — a filial teve valor de vencidos em 2 ou mais auditorias durante o ano.
- **12M+** — a última auditoria da filial foi feita há mais de 12 meses (dado desatualizado).
- **🏆 (nota)** — a filial já tem a Nota de Auditoria Anual carregada e ela está sendo considerada no score.

---

## 3. Onde consultar o valor de faturamento da filial

O **valor de faturamento usado em cada auditoria não aparece na tela de forma destacada**, pois ele só é usado como referência para calcular o % de vencidos. Caso a diretoria pergunte "quanto essa filial faturou no período?", consulte em:

- **Aba "Por Período"**: a tabela agora tem duas colunas extras — **"Vlr Faturamento"** (o valor de faturamento daquele mês usado no cálculo) e **"%Venc/Fat."** (o percentual de vencidos sobre esse faturamento).
- **Aba "⚙ Configurações" → card "💰 Base de Faturamento"**: mostra a base de faturamento carregada (arquivo, data de geração, período de cobertura, quantas filiais/meses estão preenchidos).
- **Exportação (.xlsx)**: a aba "Por Período" do arquivo exportado também traz a coluna de faturamento e o % de vencidos sobre faturamento.

---

## 4. Resumo rápido para passar ao supervisor

> "Sua filial só ganha os pontos de Pedido (30) e Canhoto (10) se fechar a auditoria com 95% ou mais de confirmação em cada um — não tem nota parcial, é tudo ou nada. A Semente (40) só vale se não tiver pendência nenhuma. Os Vencidos (20) dependem de quanto isso representa do faturamento do mês — quanto menor, melhor. No final do ano, sua filial é ranqueada pela média de todas as auditorias que fez, e se a Auditoria Interna lançar a Nota Anual de Auditoria (só conta a 'Finalizada'), ela passa a valer o mesmo peso que a Semente."
