# Car plates OCR

### Что пробовал:

* Изначально планировал сделать пайплайн из двух сетей **RetinaNet** + **LPRNet**.

RetinaNet:

Теорию смотрел тут *https://arxiv.org/abs/1708.02002*

Реализацию взял *https://github.com/fizyr/keras-retinanet*

Много времени потратил на модификацию сети, но так и не смог нормально реализовать rotated bounding boxes. 

LPRNet:

Теория: *https://github.com/sirius-ai/LPRNet_Pytorch*

Реализация: *https://arxiv.org/abs/1806.10447v1*

Так что в итоге, так и не смог все правильно друг к другу прикрутить.

* Параллельно запускал обучаться бейзлайн предоставленный преподователями, но не смог побить бейзлайн на Kaggle.

![submit](https://github.com/mirpulatov/CV/blob/master/contest2/screen1.png)

### Финальный submit:

* Воспользовался идеей Алексея, при детекции в коде бейзлайна использовал MaskRCNN (Повзаимствовал часть кода с семинара).

Этот результат и был засчитан, как финальный.

![submit](https://github.com/mirpulatov/CV/blob/master/contest2/screen2.png)