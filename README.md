# Разработка полностью связанной нейронной сети

Код [link](https://github.com/AnnaPakir/pizza/blob/main/pizza_final_ipynb%22.ipynb)

Отчет [link](https://github.com/AnnaPakir/pizza/blob/main/%D0%9E%D1%82%D1%87%D0%B5%D1%82%20%D0%9B%D0%B0%D0%B1.2.pdf)

В данной работе был произведен эксперимент по созданию полносвязной нейронной сети для классификации изображений.

Ссылка на данные в Kaggle: [link](https://www.kaggle.com/datasets/carlosrunner/pizza-not-pizza/data)

![plot](https://github.com/AnnaPakir/pizza/blob/main/pizza_date.png)

В результате были созданы три подлосвязные модели:

| Модель  | Время обучения | Количество скрытых слоев | Функция активации | Accuracy |
| --- | --- | --- | --- | --- | 
| SimpleNN() | 4359 | 1| ReLU | 62,50 % |
| ReducedNN() | 17436 | 4| Tanh | 65,54 % |
| ComplexNN() | 19180 | 4| LeakyReLU | 70,27 % |

Был проанализирован и зафиксирован процесс обучения каждой нейронной сети:
![plot](https://github.com/AnnaPakir/pizza/blob/main/model_plot.png)

Проект показал, что использование только полносвязных нейронных сетей для работы с изображениями требует больших вычислительных ресурсов. Чем сложнее модель, тем лучше результат. Да даже в этом соучае результат не показывает высокие метрики. Для работы и изображением нужныф иные подходы, в том числе срерточные слои.
