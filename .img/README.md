## Описание датасетов

### Датасет - players_data:

1. Team - команда
2. Season - сезон
3. Player - Имя игрока
4. Player_number - игровой номер
5. Position - роль в команде,
  1. G - голкипер
  2. D - защитник
  3. F - форвард
  ...
6. Captain - статус игрока:
  1. C - капитан
  2. A - ассистент
7. Birthplace - место рождения
8. Age - возраст на момент парсинга, 5 jun 2023,
9. Height - рост в см,
10. Weight - вес в кг,
11. Stick - хват клюшки,
12. Player_link - ссылка на страницу игрока, уникальное поле

### Датасет - players_personal_data:
1. Player_name - имя игрока,
2. Date_of_Birth - полная дата рождения,
3. Position - игровое амплуа, значения как в players_data,
4. Age - полных лет на момент выборки, 14 jun 23,
5. Place_of_Birth - место рождения, через запятую трёхбуквенное обозначение страны,
6. Nation - гражданство, если несколько, то перечислены через /,
7. Grip - хват клюшки,
8. Youth_Team - молодежная команда, в которой игрок начинал карьеру,
9. Height_cm - рост в см,
10. Height_ft - рост в футах,
11. Weight_kg - вес в кг,
12. Weight_lbs - вес в фунтах,
13. Awards - список наград по сезонам в формате JSON,
14. Player_link - ссылка на страницу игрока, уникальное поле.

### Датасет transfers:
1. Date - дата перехода,
2. Player - имя игрока,
3. Player_link - ссылка на страницу игрока,
4. From_team - старая команда,
5. From_team_link - ссылка на старую команду,
6. To_team - новая команда,
7. To_team_link - ссылка на новую команду.

## Датасет players_stats:
1. Player_name - имя игрока
2. Season - сезон
3. Team - команда
4. League - лига
5. Player_link - ссылка на страницу игрока
6. Регулярный сезон
7. Regular_Games_Played - количество сыгранных игр
8. Показатели только для полевых игроков (регулярный сезон)
9. Regular_Goals - количество голов
10. Regular_Assists - количество передач
11. Regular_Total_Points - общее количество очков
12. Regular_Penalty_Minutes - количество штрафных минут
13. Regular_Plus_Minus - показатель плюс-минус
Показатели только для вратарей (регулярный сезон)
Regular_Games_Dressed - количество игр, на которых вратарь был заявлен на игру, но сидел в запасе
Regular_GAA - коэффициент надёжности, показывает, сколько в среднем шайб пропускает вратарь за 60 минут игрового времени
Regular_Saves_Percentage - процент отраженных бросков
Regular_Goals_Against - количество пропущенных голов
Regular_Saves- количество сейвов
Regular_Shutouts - количество игр на ноль
Regular_WLT - win-lose-tie, соотношение выигранных, проигранных и ничейных (в основное время) игр
Regular_TOI - время на льду
Плей-офф (аналогично с регулярным сезоном)
Postseason_Games_Played
Показатели только для полевых игроков (плей-офф)
Postseason_Goals
Postseason_Assists
Postseason_Total_Points
Postseason_Penalty_Minutes
Postseason_Plus_Minus
Показатели только для вратарей (плей-офф)
Postseason_GAA
Postseason_Saves_Percentage
Postseason_Goals_Against
Postseason_Saves
Postseason_Shutouts
Postseason_WLT
Postseason_TOI
Датасет players:

player_link - ссылка на команду
player - имя игрока
team - команда
start_date - дата начала игры в команде
end_date - дата конца игры в команде
Датасет stat:

player_link - ссылка на игрока
player - имя игрока
position - игровое амплуа
born - дата рождения
age - возраст
country - страна рождения
hight - рост
weight - вес
shoot - захват клюшки
GP - количество игр
G - количество голов
Assists - количество передач
PTS - количество очков, присуждаемое в команде
+/- - очки +/-
'+' - очки +
'-' - очки минус
Статистика игроков по амплуа

PIM
ESG
PPG
SHG
OTG
GWG
SDS
SOG
%SOG
S/G
FO
FOW
%FO
TOI/G
SFT/G
TIE/G
SFTE/G
TIPP/G
SFTPP/G
TISH/G
SFTSH/G
HITS
BLS
FOA
TkA
W
L
SOP
GA
Sv
%Sv
GAA
SO
