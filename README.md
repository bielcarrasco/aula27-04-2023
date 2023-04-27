# User story

Como usuário 
eu gostaria de receber um lembrete de confirmação por e-mail alguns dias antes da minha consulta
para que eu não perca a consulta.

# Tarefas tecnicas

configuração de timer para o tempo de envio

criação do sistema de confirmação ou cancelamento da consulta

automatização do cancelamento caso o paciente não possa comparecer

# pontuação

Configuração do timer para o tempo de envio

Reach: Alta. Todos os pacientes que agendam consultas pelo site serão impactados pela funcionalidade de lembrete de consulta.

Impacto: Médio. A funcionalidade pode melhorar a experiência do usuário, mas não tem um impacto direto nos resultados da clínica.

Confiança: Alta. A configuração do timer é uma tarefa relativamente simples e tem baixo risco de erros.

Esforço: Médio. A configuração do timer envolverá a implementação de uma biblioteca ou cron job para automatizar o envio de mensagens, o que requer conhecimentos técnicos.

RICE: (R * I * C) / E = (3 * 2 * 4) / 3 = 8



Criação do sistema de confirmação ou cancelamento da consulta

Reach: Alta. Todos os pacientes que agendam consultas pelo site serão impactados pela funcionalidade de confirmação/cancelamento de consulta.

Impacto: Alto. O sistema de confirmação/cancelamento pode melhorar significativamente a eficiência da clínica e a experiência do paciente.

Confiança: Média. A implementação do sistema pode envolver desafios técnicos e de integração com outros sistemas.

Esforço: Alto. A criação do sistema envolverá o desenvolvimento de uma interface de usuário, integração com bancos de dados e sistemas de notificação.

RICE: (R * I * C) / E = (3 * 4 * 2) / 4 = 6

Automatização do cancelamento caso o paciente não possa comparecer

Reach: Alta. Todos os pacientes que agendam consultas pelo site serão impactados pela funcionalidade de cancelamento automático.

Impacto: Alto. A automatização do cancelamento pode melhorar significativamente a eficiência da clínica e reduzir o número de consultas perdidas.

Confiança: Média. A implementação do sistema pode envolver desafios técnicos e a configuração correta dos parâmetros para o cancelamento automático.

Esforço: Alto. A criação do sistema envolverá o desenvolvimento de um algoritmo e integração com bancos de dados e sistemas de notificação.

RICE: (R * I * C) / E = (3 * 4 * 2) / 4 = 6
