Итоговый проект по автоматизации тестирования
Инструментом для тестирования послужил Selenium так как позволяет автоматизировано управлять браузером (webdriver.Chrome)
При тестировании формы регистрации Ростелеком использовалась техника parwise testing (попарное тестирование) для тестирования 
полей ввода ввода при помощи класса эквивалентности (валидное значение, невалидное значение, пустое значение)
Также использовался метод “Причина и следствие”, который помогает предусмотреть возможные действия пользователя  протестировать их

В директории находится файл tests.py, в котором располагаются тесты

В корневой директории лежит файл settings.py, в которой предполагается нахождение информации о валидном логине, пароле, номере телефона, 
электронной почты и лицевом счете компании Ростелеком

В корневой директории присутствует файл conftest.py, в котором находится параметризация валидных 
номеров телефона в разных вариантах написания

Методы имеют подродное описаниe
