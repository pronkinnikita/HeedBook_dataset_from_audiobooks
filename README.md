# HeedBook_dataset_from_audiobooks
Script for catching dataset for speech-to-text from audiobooks

# Пронькин Никита Валерьевич ПМИ 162 "Making noize-resisted speech-to-text system on base of data-set from audiobooks " 

Существующие API для распознавания речи, которые предложены для свободного использования, такие, как Google Speech и PocketSphinx, оказываются плохо пременимы для работы в условиях плохого качества звука и шума.

Задача проекта бросить вызов зашумленным условиям и построить систему, предобученную с акцентом на разпознавание голоса в плохих акустических условиях, с качествов распознавания в этих условиях, превосходящим существубщие системы, ориентированные на общие условия.

# План работы

1) Первая стадия проекта заключается в извелечении необходимого для обучения системы датасета из аудиокниг.
Используются Google Speech и PocketSphinx для распознавания текста аудиокниги, а также алгоритм динамического программирования Нидлмана-Вунша для поиска максимального соответствия между распознанным и исходным текстом книги.

2) Данные, извлеченные из аудикниг "стирильны", и возникает простор для творчесвта, по искуственному созданию зашемленных условий.
Создание "Эхо", замедление и ускорение случайных кусков или окончаний слов аудио, наложение "математических шумов", наложение "реальных шумов", по возможности класиффицированных.

3) Обучение нейросетей и вероятностных моделей.
4) Тестирование

-раздел, содержащий описание актуальности решаемой задачи, в том числе, обзор существующих решений;
- обзор используемых технологических решений, и обоснование их выбора;


- план работы по реализации функциональности проекта, в котором должны быть указаны предполагаемые сроки выполнения отдельных критериев, перечисленных в описании проекта на Вики ФКН, учитывая, что критерии на 4 балла должны быть готовы к моменту сдачи второй контрольной точки (12-17 марта 2018).
