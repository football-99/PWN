# PWN
Описание и пример эксплуатации системной уязвимости- переполнение буфера.

# Список виртуальных машин(Windows7 и Kali Linux), которые использовалисьв ходе выполнения проекта доступны по ссылке:
https://disk.yandex.ru/d/LlwUQ9-_5EE-aA?w=1

# Задачи  работы

В ходе выполнения  работы необходимо:
1) определить уязвимость «переполнение буфера» в исследуемом 
приложении;
2) проанализировать собранные данные;
3) проэксплуатировать уязвимость «переполнение буфера», реализовав 
атаку срыва стека;
4) собрать необходимые сведения с помощью различных инструментов 
(отладчика , утилит pattern_create и findjmp);
5) познакомиться со специальным программным обеспечением для анализа 
уязвимых приложений;
6) провести отладки исследуемого приложения;
7) смоделировать поведения злоумышленника и пользователя уязвимого 
приложения при совершении атаки на пользовательскую систему.

# Резльтат:

В ходе выполнения работы
1) Было рассмотрено уязвимое приложение serv.exe, которое содержала системную уязвимость-переполнение буфера: 
2) Написан шелл-код для эскплуатации данной узявимости;
3) Написан скрипт на языке Python для автоматизации атаки.

В результутате успешно проведенной атаки на стороне пользователя, был получен полный доступ к его ЭВМ и в качестве примера было запущено приложение "Калькулятор".

