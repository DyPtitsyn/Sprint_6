Sprint_6

Проект автоматизации тестирования для учебного сервиса «Яндекс.Самокат»

Все page_object - в директории page_objects

Фикстуры - в файле conftest.py

Все тесты - в директории tests </br>
- test_home_page - файл с тестами на проверку выпадающего списока в разделе «Вопросы о важном». </br>
-- test_check_text_answer 
- test_logo_redirect - файл с тестами на проверку перехода на Дзен</br>
--test_logo_scooter_redurect</br>
--test_logo_yandex_redirect
- test_order - файл с тестами на проверку всего флоу позитивного сценария с двумя наборами данных, точки входа в сценарий</br>
-- test_success_order</br>
--test_order_button_header</br>
--test_order_button_middle</br>

Два набора данных для позитивного сценария - в файле data.py

Команда для установки внешних зависимостей - pip3 install -r requirements.txt