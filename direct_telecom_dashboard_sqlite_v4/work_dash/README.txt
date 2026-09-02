DIRECT TELECOM — DASHBOARD OPERACIONAL

Estrutura:
  dashboard/index.html  -> painel completo
  database/direct_telecom.sqlite -> banco SQLite inicial
  assets/direct_telecom_logo.png -> logo

Uso:
1. Abra dashboard/index.html no navegador.
2. Use "Novo evento" para cadastrar atividades sem escrever código.
3. Use "Salvar banco" para exportar o SQLite atualizado.
4. Use "Abrir banco SQLite" para carregar a base salva.

Campos adicionais:
- Técnico fusionista e Auxiliar, com listas baseadas nos nomes da base e opção de adicionar técnico.
- Ano baseado na base, com opção de novo ano.
- Motivo de despesa: Café, Almoço, Jantar, Hotel.
- Complexidade: ALTO, MEDIO, BAIXO.
- Ranking dos 3 melhores técnicos.
- TMA: média de (alarme -> acionamento) + tempo de deslocamento.
- Tempo médio de execução: alarme -> finalização UP.
- Filtros individuais por coluna nos registros.
