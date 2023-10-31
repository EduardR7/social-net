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
    1. Regular_Goals - количество голов
    2. Regular_Assists - количество передач
    3. Regular_Total_Points - общее количество очков
    4. Regular_Penalty_Minutes - количество штрафных минут
    5. Regular_Plus_Minus - показатель плюс-минус
9. Показатели только для вратарей (регулярный сезон)
    1. Regular_Games_Dressed - количество игр, на которых вратарь был заявлен на игру, но сидел в запасе
    2. Regular_GAA - коэффициент надёжности, показывает, сколько в среднем шайб пропускает вратарь за 60 минут игрового времени
    3. Regular_Saves_Percentage - процент отраженных бросков
    4. Regular_Goals_Against - количество пропущенных голов
    5. Regular_Saves- количество сейвов
    6. Regular_Shutouts - количество игр на ноль
    7. Regular_WLT - win-lose-tie, соотношение выигранных, проигранных и ничейных (в основное время) игр
    8. Regular_TOI - время на льду
    9. Плей-офф (аналогично с регулярным сезоном)
    10. Postseason_Games_Played
10. Показатели только для полевых игроков (плей-офф)
    1. Postseason_Goals
    2. Postseason_Assists
    3. Postseason_Total_Points
    4. Postseason_Penalty_Minutes
    5. Postseason_Plus_Minus
    6. Показатели только для вратарей (плей-офф)
    7. Postseason_GAA
    8. Postseason_Saves_Percentage
    9. Postseason_Goals_Against
    10. Postseason_Saves
    11. Postseason_Shutouts
    12. Postseason_WLT
    13. Postseason_TOI

### Датасет players:
1. player_link - ссылка на команду
2. player - имя игрока
3. team - команда
4. start_date - дата начала игры в команде
5. end_date - дата конца игры в команде

### Датасет stat:
1. player_link - ссылка на игрока
2. player - имя игрока
3. position - игровое амплуа
4. born - дата рождения
5. age - возраст
6. country - страна рождения
7. hight - рост
8. weight - вес
9. shoot - захват клюшки
10. GP - количество игр
11. G - количество голов
12. Assists - количество передач
13. PTS - количество очков, присуждаемое в команде
    1. +/- - очки +/-
    2. '+' - очки +
    3. '-' - очки минус
14. Статистика игроков по амплуа
    1. PIM
    2. ESG
    3. PPG
    4. SHG
    5. OTG
    6. GWG
    7. SDS
    8. SOG
    9. %SOG
    10. S/G
    11. FO
    12. FOW
    13. %FO
    14. TOI/G
    15. SFT/G
    16. TIE/G
    17. SFTE/G
    18. TIPP/G
    19. SFTPP/G
    20. TISH/G
    21. SFTSH/G
    22. HITS
    23. BLS
    24. FOA
    25. TkA
    26. W
    27. L
    28. SOP
    29. GA
    30. Sv
    31. %Sv
    32. GAA
    33. SO
