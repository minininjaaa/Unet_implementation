# Unet implementation

В этой работе я имплементирую архитектуру U-Net для решения задачи сегментации родинок на медицинских изображениях.

![Оригинал](https://github.com/minininjaaa/Unet_implementation/blob/main/image/1.jpg)
![Маска](https://github.com/minininjaaa/Unet_implementation/blob/main/image/2.jpg)

Оценка качества модели будет по метрике IoU.

В процессе обучения нейросети я брала 3 разных лосса для сравнения: BCE, Dice, Focal

![лоссы](https://github.com/minininjaaa/Unet_implementation/blob/main/image/3.png)

Результат:

![результат](https://github.com/minininjaaa/Unet_implementation/blob/main/image/4.png)
