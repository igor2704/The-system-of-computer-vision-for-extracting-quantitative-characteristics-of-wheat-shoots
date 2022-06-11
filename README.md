# Система компьютерного зрения для извлечения количественных характеристик проростков пшеницы
Цель выпускной квалификационной работы – создание системы компьютерного зрения для извлечения количественных характеристик проростков
пшеницы. Данная система в дальнейшем может улучшить результаты некоторых исследований, а также снизить их стоимость и трудозатратность. Объект исследования – изображения проростков пшеницы.

В работе были использованы следующие методы и алгоритмы: сверточная нейронная сеть архитектуры Unet, модифицированный индекс tgi, с
дальнейшем поиском максимума целевой функции при помощи генетического
алгоритма, обход в глубину(DFS), алгоритм Дейкстры, критерий Стюдента,
критерий Бартлетта, K²-тест Д’Агостино, критерий Манна-Уитни, критерий
Краскела-Уоллиса, логистическая регрессия, алгоритм машинного обучения
случайный лес, сверточная нейронная сеть архитектуры ResNet с 18, 50 и 101
слоями.

Созданная в этой работе система была протестирована на извлечении двух количественных характеристиках: плоидности и генотипа 1102/L-25. Для задачи сегментации изображений, предоставленных для определения плоидности, результаты лучших моделей на тестовых выборках –
0.8463870901428718 (IoU), для определения генотипа – 0.8999361294443262
(IoU). Результаты лучших моделей классификации на тестовых выборках
для решения задачи определения плоидности были следующими: без разделения на временные точки – 0.6538461538461539 (accuracy), первая временная точка – 0.6153846153846154 (accuracy), вторая временная точка –
0.7692307692307693 (accuracy), разница – 0.46153846153846156 (accuracy).
Лучшая модель классификации по генотипу 1102/L-25 предсказывала генотип безошибочно.
