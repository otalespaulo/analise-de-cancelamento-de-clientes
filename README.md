# Análise de Cancelamento de Clientes (Churn)

Projeto desenvolvido durante a **Jornada Python da Hashtag Treinamentos** para analisar os motivos do cancelamento de clientes em uma empresa e encontrar soluções para reduzir essa taxa.

## 🛠️ Tecnologias usadas

- **Python**
- **Pandas** (tratamento e análise dos dados)
- **Plotly** (geração dos gráficos interativos)

## 📌 Passo a passo do projeto

1. **Importação dos dados:** Leitura da base de dados em arquivo CSV.
2. **Limpeza dos dados:** Remoção da coluna de ID (que não ajuda na análise) e exclusão de linhas com informações vazias (`dropna`).
3. **Análise inicial:** Verificação da taxa geral de cancelamento (mais de 50% dos clientes cancelaram).
4. **Análise de causas e gráficos:** Criação de histogramas para comparar cada coluna com os cancelamentos e identificar os principais problemas.

## 💡 Principais descobertas e soluções

Analisando os dados e gráficos, identifiquei três pontos críticos:

1. **Contrato Mensal:** Praticamente todos os clientes do plano mensal cancelam. 
   - *Solução:* Oferecer descontos para migrarem para os planos trimestral ou anual.
2. **Ligações pro Call Center:** Clientes que ligam mais de 4 vezes para o suporte cancelam o serviço.
   - *Solução:* Melhorar o atendimento para resolver o problema do cliente em até 3 ligações.
3. **Dias de Atraso:** Clientes com mais de 20 dias de atraso cancelam a assinatura.
   - *Solução:* Criar um sistema de alerta/cobrança antes de fechar os 20 dias de atraso.

---

**Autor:** Tales

