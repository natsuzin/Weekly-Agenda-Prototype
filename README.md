## TEMA: REGISTROS/STRUCTS + RECURSIVIDADE – LINGUAGEM C++
Desenvolva o protótipo de uma agenda semanal de compromissos. As informações sobre cada compromisso são organizadas por dia da semana, e para cada dia tem-se a data atual (dia, mês, ano e dia da semana), e os compromissos, cujas informações são horário inicial e final (hora, minuto), tipo (reunião, atividade, aniversario), local e assunto (textos). Utilize tipos estruturados para representar estas informações. A agenda semanal deve ser armazenada em um vetor, organizada por data/hora. 

Considere que o número máximo de compromissos diários serão 6, e a quantidade de compromissos diários agendados deve controlada.
O programa a ser implementado deve permitir as seguintes operações (através de menu/subrotinas):
  - Inicialização de nova semana a qualquer momento da execução do programa. Antes de inicializar o vetor de compromissos solicite confirmação do usuário. Caso positivo, peça a data inicial da semana (no caso do exemplo 09/10/2022) e informe “Agenda inicializada”.
  - Inclusão de novo compromisso a qualquer momento da execução do programa. Antes de incluir verifique se a data/hora está disponível. Caso não esteja disponível, informar "Horário já ocupado". Caso contrário, solicite os demais dados ao usuário, e informe “Compromisso incluído”.
  - Exclusão de compromisso, buscando-se pela data/hora. Caso não exista, informar "Compromisso inexistente". Caso contrário, deve ser feita a exclusão física do referido compromisso e informar "Compromisso excluído".
  - Relatório 1: mostrar compromissos em uma determinada data – com todas as suas informações. Se a data estiver fora da agenda semanal deve-se emitir aviso de erro.
  - Relatório 2: agenda semanal – com todas as suas informações.

Subrotina(s) auxiliar(es): pesquisa e ordenação deverão ser implementadas de forma recursiva.
A qualquer entrada de dados deve-se realizar tratamento de dados/validação (inclusive de tipo). O sistema deverá apresentar uma interface básica, com menu e controle de rolamento de tela.

---

## THEME: RECORDS/STRUCTS + RECURSION - C++ LANGUAGE
Develop the prototype of a weekly agenda of appointments. The information about each appointment is organized by day of the week, and for each day there is the current date (day, month, year and day of the week), and the appointments, whose information is start and end time (hour, minute), type (meeting, activity, birthday), location and subject (texts). Use structured types to represent this information. The weekly agenda should be tored in a vector, organized by date/time. 

Consider that the maximum number of daily appointments will be 6, and the number of scheduled daily appointments must be controlled.
The program to be implemented must allow the following operations (via menu/subroutines):
  - Initialization of a new week at any time during the execution of the program. Before initializing the vector of appointments, ask the user for confirmation. If so, ask for the week's start date (in the case of the 09/10/2022 example) and enter "Agenda initialized".
  - Add a new appointment at any time during program execution. Before adding it, check that the date/time is available. If it is not available, enter "Schedule already taken". Otherwise, ask the user for the rest of the data and enter "Appointment included".
  - Deleting an appointment, searching for the date/time. If it doesn't exist, enter "Appointment doesn't exist". Otherwise, physically delete the appointment and enter "Appointment deleted".
  - Report 1: show appointments on a given date - with all their information. If the date is outside the weekly agenda, an error message should be issued.
  - Report 2: weekly agenda - with all its information. Auxiliary subroutine(s): search and sort should be implemented recursively.

Auxiliary subroutine(s): search and sort must be implemented recursively.
Data processing/validation (including type validation) must be carried out on any data input. The system should have a basic interface, with a menu and screen scroll control. 
