DIRECT TELECOM — DASHBOARD OPERACIONAL V5

Estrutura pronta para publicação no GitHub Pages.

Na raiz do repositório:
- index.html redireciona para work_dash/dashboard/index.html
- .nojekyll evita processamento do Jekyll

Dashboard:
- Visão geral: mantém os indicadores e gráficos existentes
- SLA / MTTR: SLA máximo de 6 horas, eventos dentro/fora do SLA, MTTR médio/mediano, histórico mensal e lista de violações
- Circuitos & custos: circuitos distintos, reincidência, indisponibilidade, custo médio, rankings e evolução de custos
- Equipe & operação: deslocamento, fora do horário, dia/hora de maior carga, produtividade por técnico, eventos por dia/hora e complexidade

Observação:
O cálculo do SLA considera o primeiro horário válido entre hr_alarme e hr_acionamento, até hr_finalizacao_up. Registros sem timestamps suficientes ficam fora do cálculo do SLA/MTTR e são contabilizados na cobertura.

O banco SQLite original foi preservado.
