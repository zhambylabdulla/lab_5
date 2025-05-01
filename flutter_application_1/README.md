1. Navigator.push - Переход со FirstScreen на SecondScreen. При нажатии кнопки открывается второй экран. Можно вернуться назад с помощью pop().
2. Navigator.pushNamed - Переход со FirstScreen на SecondScreen с использованием именованного маршрута. Используется строка-имя маршрута. Возврат также возможен.
3. Navigator.pushReplacement - Заменяет текущий экран (FirstScreen) на SecondScreen. FirstScreen удаляется из стека. Кнопка "назад" не вернет на него.
4. Navigator.pushAndRemoveUntil - Переход на SecondScreen и удаление всех предыдущих экранов из стека. Только SecondScreen остается в стеке. Вернуться назад невозможно.
5. Navigator.pushNamedAndRemoveUntil - То же самое, что и выше, но с использованием именованного маршрута. Все предыдущие маршруты очищаются. Остается только SecondScreen.
6. Navigator.pop - Возврат на предыдущий экран. При нажатии на кнопку на SecondScreen происходит возврат на FirstScreen.
7. Navigator.popAndPushNamed - Удаляет текущий экран и сразу открывает ThirdScreen по имени маршрута. SecondScreen закрывается, ThirdScreen открывается.