# Laboratorio-Banco-de-Dados

O Dr. Vilegas é pediatra e atende pacientes tanto via plano de saúde quanto de forma
particular. As consultas são agendadas pela secretária. Para pacientes novos, o
registro inicial inclui apenas o nome da criança, nome do responsável, telefone de
contato e tipo de plano.
Para cada paciente, são mantidas as seguintes informações: nome da criança, nome
dos pais, data de nascimento, endereço completo (com UF), telefones residencial e
celular (identificando a quem pertencem), sexo, prontuário de cada consulta, além do
histórico de peso e altura. O sistema também emite o receituário, contendo as
prescrições, nome e CRM do médico.
Cada prontuário de consulta deve registrar a descrição dos sintomas, resultados da
observação clínica, medicamentos prescritos (com dosagem, modo de administração
e duração do tratamento), e exames solicitados. Além disso, para cada paciente deve
constar o nome do plano de saúde ou a informação de atendimento particular.
Descrição: Este caso de uso tem por objetivo permitir ao médico registrar todas as
informações da consulta no prontuário do paciente, bem como prescrever os
medicamentos e exames necessários, solicitando ao final a geração do receituário.
Atores: Médico
Pré-condição: existir cadastro prévio de medicamentos e exames.
Cenário principal:
1. O sistema exibe todas as consultas agendadas para o dia, com as seguintes
informações para cada uma:
- horário (exemplo: 09:30h, 16h)

- nome da criança
- se é paciente novo
2. O usuário seleciona uma consulta.
3. O sistema exibe o prontuário para o usuário, com as seguintes opções
habilitadas:
3.1. Consultar últimos lançamentos do prontuário
3.2. Consultar histórico de peso
3.3. Consultar histórico de altura
4. O sistema prepara uma lista de medicamentos cadastrados.
5. O sistema prepara uma lista de exames cadastrados.
6. O usuário informa no prontuário, em qualquer ordem:
6.1. peso do paciente
6.2. altura do paciente
6.3. descrição dos sintomas
6.4. resultado da observação clínica
6.5. para cada medicamento prescrito, o usuário informa:
6.5.1. nome do medicamento, selecionado da lista pré-existente
6.5.2. dosagem
6.5.3. administração
6.5.4. tempo de uso
6.6. para cada exame prescrito, o usuário informa:
6.6.1. nome do exame, selecionado da lista pré-existente
