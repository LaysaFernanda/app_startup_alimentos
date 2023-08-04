# app_startup_alimentos
Projeto de análise comportamental de usuários do aplicativo de uma startup de produtos alimentícios.

Neste projeto trabalho em uma startup que vende produtos alimentícios. Preciso analisar o comportamento do usuário para o aplicativo da empresa e descobrir:
- Como os usuários chegam à etapa de compra?
- Quantos usuários realmente chegam a essa etapa?
- Quantos ficam presos nas fases anteriores?
- Quais etapas em particular?

Em seguida, preciso analisar os resultados do teste A/A/B. (Os designers gostariam de alterar as fontes de todo o aplicativo, mas os gerentes temem que os usuários achem o novo design intimidador. Eles decidem tomar
a decisão com base nos resultados de um teste A/A/B).

### Descrição dos Dados:
- EventName — nome do evento
- DeviceIDHash — dentificador de usuário exclusivo
- EventTimestamp — hora do evento
- ExpId — número do experimento: 246 e 247 são os grupos de controle, 248 é o grupo de teste

### Bibliotecas usadas:
- pandas
- plotly
- matplotlib
- scipy
