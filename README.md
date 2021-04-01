# PWN
Описание и пример эксплуатации системной уязвимости- переполнение буфера.
Список виртуальных машин(Windows7 и Kali Linux), которые использовалисьв ходе выполнения проекта доступны по ссылке:
https://disk.yandex.ru/d/LlwUQ9-_5EE-aA?w=1

Задачи  работы

В ходе выполнения  работы необходимо:
1) собрать необходимые сведения с помощью различных инструментов 
(отладчика , утилит pattern_create и findjmp);
2) проанализировать собранные данные;
3) проэксплуатировать уязвимость «переполнение буфера», реализовав 
атаку срыва стека.
После выполнения лабораторной работы обучающиеся получат 
следующие основные навыки:
1) определение уязвимости «переполнение буфера» в исследуемом 
приложении;
2) работа со специальным программным обеспечением для анализа 
уязвимых приложений;
3) проведение отладки исследуемого приложения;
4) моделирование поведения злоумышленника и пользователя уязвимого 
приложения при совершении атаки на пользовательскую систему

Резльтат:
В ходе выполнения работы было рассмотрено уязвимое приложение serv.exe, которое содержала системную уязвимость-переполнение буфера. Был написан шелл-код для эскплуатации данной узявимости и скрипт на языке Python для автоматизации атаки. В резльтутате успешно проведенной атаки на стороне пользователя, был получен полный доступ к его ЭВМ и в качестве примера было запущено приложение "Калькулятор".

