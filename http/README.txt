ЗАДАНИЕ:
Практика по requests
В этом задании вы научитесь работать с библиотекой requests (https://requests.kennethreitz.org/en/master/),
а также научитесь работать с API сервиса VK и его документаций, что является достаточно частой задачей разработчика.

Необходимо написать клиент к API VK , который будет считать распределение возрастов друзей для указанного пользователя.
То есть на вход подается username или user_id пользователя, на выходе получаем список пар (<возраст>, <количество друзей с таким возрастом>),
отсортированный по убыванию по второму ключу (количество друзей) и по возрастанию по первому ключу (возраст). Например:
[(26, 8), (21, 6), (22, 6), (40, 2), (19, 1), (20, 1)]