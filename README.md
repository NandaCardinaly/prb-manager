# 🍅 Pomodoro PRB Tracker
Um aplicativo Pomodoro para gerenciar múltiplos PRBs (Pedidos de Revisão de Bug/Feature) com controle individual de tempo e acompanhamento de progresso.

## 🚀 Características

- 📝 **Gerenciamento de PRBs**: Adicione múltiplos PRBs com nome, descrição e horas estimadas
- ⏱️ **Pomodoro Individual**: Cada PRB tem seu próprio timer Pomodoro (25min trabalho / 5min pausa)
- 📊 **Tracking Preciso**: Acompanhe tempo trabalhado vs estimado para cada PRB
- ⚠️ **Alertas de Tempo**: Identifique rapidamente PRBs que ultrapassaram a estimativa
- 💾 **Armazenamento Local**: Todos os dados são salvos automaticamente no navegador
- 📥 **Exportar/Importar**: Faça backup completo de todos os PRBs em JSON
- 🔔 **Notificação Sonora**: Alerta quando cada ciclo Pomodoro termina
- ⏸️ **Pausar Anytime**: Pause durante reuniões ou outras atividades
- 📈 **Resumo Geral**: Visualize estatísticas consolidadas de todos os PRBs


## 🎯 Fluxo de Trabalho

### 1. Adicionar PRB
- Clique em "Adicionar PRB" no painel esquerdo
- Preencha:
  - **Nome**: Título do PRB (obrigatório)
  - **Descrição**: Detalhes do que precisa ser feito (opcional)
  - **Horas Estimadas**: Quanto tempo você estima que levará (obrigatório)

### 2. Iniciar Pomodoro
- Clique em "▶️ Iniciar Pomodoro" no PRB que deseja trabalhar
- O timer de 25 minutos começa automaticamente
- Você pode pausar a qualquer momento durante reuniões ou interrupções

### 3. Completar Ciclos
- Ao completar 25 minutos, o tempo é automaticamente registrado no PRB
- Uma pausa de 5 minutos é iniciada automaticamente
- Após a pausa, você pode continuar com outro pomodoro no mesmo PRB ou mudar para outro

### 4. Acompanhar Progresso
- Cada PRB mostra:
  - ⏱️ **Horas Estimadas**: Sua estimativa inicial
  - ✅ **Horas Trabalhadas**: Tempo real gasto
  - 📊 **Diferença**: +/- em relação à estimativa
  - 🍅 **Pomodoros**: Quantidade de ciclos completos
  - Barra de progresso visual (vermelha se ultrapassar estimativa)

## 📊 O que é Registrado

### Para cada PRB:
- Nome e descrição
- Horas estimadas
- Total de minutos trabalhados
- Número de pomodoros completados
- Data de criação
- Status (ativo/inativo)

### Resumo Geral:
- Total de PRBs cadastrados
- Soma de todas as horas estimadas
- Soma de todas as horas trabalhadas
- Diferença total (indica se está adiantado ou atrasado)

## 💾 Backup e Restauração

### Exportar Dados
- Clique em "📥 Exportar Dados" no rodapé
- Um arquivo JSON será baixado com TODOS os seus PRBs
- Nome do arquivo: `prb-tracker-YYYY-MM-DD.json`
- **Use isso para fazer backup regular dos seus dados!**

### Importar Dados
- Clique em "📤 Importar Dados"
- Selecione um arquivo JSON previamente exportado
- Escolha:
  - **Mesclar**: Adiciona/atualiza PRBs mantendo os existentes
  - **Substituir**: Remove todos os PRBs atuais e usa apenas os importados

## ⚠️ Importante

- Apenas um PRB pode estar ativo por vez
- Faça backup regular dos seus dados (exportar JSON)
- Limpar dados do navegador apagará seus PRBs
- PRBs ativos não podem ser deletados (pare primeiro)

## 💡 Dicas

1. **Seja realista nas estimativas**: Use dados históricos para melhorar
2. **Faça pausas**: Respeite os intervalos de 5 minutos
3. **Exporte regularmente**: Faça backup semanal dos dados
4. **Use descrições**: Ajuda a lembrar contexto depois
5. **Um PRB por vez**: Foco é fundamental para produtividade

## 📝 Licença

Livre para uso pessoal e comercial.

## 🤝 Contribuições

Sinta-se à vontade para fazer fork e melhorar o projeto!

