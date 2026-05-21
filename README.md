# Atividade-Python
Este é um simulador de matrícula da ufrpe via terminal estruturado em Programação Orientada a Objetos.
O sistema separa rigidamente as responsabilidades entre a matriz curricular, o histórico do aluno e a interface.
Ele valida três regras de negócio essenciais durante o fluxo:

Limite máximo de 4 disciplinas por semestre.

Bloqueio de trilhas específicas conforme o período do estudante.

Exigência de pré-requisitos baseada apenas em matérias já concluídas no passado.
Isso impede que o usuário puxe uma matéria e sua dependência juntas no mesmo semestre.
Além disso, trata erros de digitação comuns no teclado para garantir que o fluxo não quebre no meio do processo.
