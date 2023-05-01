# KNN
Был реализован алгоритм k-ближайших соседей для бинарной и мультиклассовой задачи классификации. Расстояния между тестовыми и тренировочными данными считалось по 
L1 норме. Также были реализованы функция подсчета метрик: accuracy, precision, recall, f-меры и алгоритм кроссвалидации для выбора лучшего количества соседей K.  
                                       
# Linear classification
Был реализован алгоритм линейной классификации, который обучается за счет уменьшения функции ошибки: Cross-entropy loss. Для этого был реализован алгоритм градиентного
спуска. Градиент функции потерь считался аналитически и проверялся через вычисление численным методом. Предсказанные вероятности класса вычислялись при помощи функции softmax.

# Fully connected layer
Была реализована 2х слойная полносвязная нейронная сеть, решающая задачу классификации. 
Для решения задания понадобилось: реализовать полносвязный слой, прямой и обратный проход по нему, сохранение градиентов, функцию активации - ReLu, регуляризацию по норме L2, алгоритм уменьшения скорости обучения и моментный стохастический градиентный спуск.

# Convolutional Neural Network
Была реализована 3 слойная(2 convolutional и 1 fully connected layers) нейронная сеть для классификации изображений.
Для решение задания понадобилось: реализовать сверточный слой, maxpool, flattener прямой и обратный проход по ним, сохранение градиентов(остальные функции были взяты из предыдущего задания)



