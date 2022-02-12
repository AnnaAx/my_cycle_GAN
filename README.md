# my_cycle_GAN
Anna_Andreevskikh_project_DeepLearningSchool_Advanced_autumn_2021

В проекте для генерации изображений реализована модель CycleGAN.

Задача: генерация реалистичных изображений с использованием в качестве исходных данных 
реальных фотографий(или изображений) различных объектов
Например, генерация реалистичного изображения зебры из фото зебр и лошадей,
генерация псевдо картин Моне из фото, 
генерация изображений овощей и т.п.

Примеры сгенерированных изображений будут прикреплены.

Ресурсы Colab не позволили обучать модель долго, однако для несложных задач, 
как например, генерация изображений овощей, качество изображений, как мне кажется,  получилось удовлетворительным.
При генерации изображений зебр из лошадей и наоборот, модель иногда допускает ошибки, 
разрисовывая полосками не те области, которые нужно. Возможно, это "лечится" более длительным обучением.

При генерации псевдо картин из фотоизображений, результат тоже удовлетворительный, 
а вот сгенерировать качественное фото из картины не получилось.

Также я пробовала более сложные задачи, например, 
использовала в качестве исходных данных фото лиц людей и фото тигров. 
Эта задача оказалась слишком сложна. 
Хотя, возможно, длительное обучение и использование более крупного датасета решит эту проблему.

Инструкция.
Загружено 2 блокнота:
1. Для  обучения и генерации 
Andreevskikh_project_training&generation.ipynb
2. Только для генерации 
Andreevskikh_project_training&generation.ipynb
Для запуска обоих блокнотов нужны датасеты, сохранение параметров на ГуглДиск 
Ссылка на блокноты на ГД:
https://drive.google.com/drive/folders/1IJZUEbKNkDvQaUBx_BzUmeEhiYcScTIn?usp=sharing
Параметры обученных моделей:
https://drive.google.com/drive/folders/1z7n9NChsgtCFeUKE4tt2I2DmJ28ccQy3?usp=sharing
Исходныq датасет овощей здесь: 
hhttps://drive.google.com/drive/folders/1CJryy67BR9EM2qtLTE7TTc2Ltn60TTr7?usp=sharing

Сгенерированные картинки овощей здесь: 
https://drive.google.com/drive/folders/1-yqyss1KINTcJ5pO4jeK3MaoBhSwUiMj?usp=sharing

![01](https://user-images.githubusercontent.com/90407728/153718331-e9153ae6-5d9c-4e5a-befc-11438c28c3cc.jpg)
![06](https://user-images.githubusercontent.com/90407728/153718406-c44a4b6f-3108-4e4c-85c5-a6b3b8edcbbe.jpg)

![05](https://user-images.githubusercontent.com/90407728/153718391-a4248f6f-c2ea-46dd-adf1-a8701dda4f36.jpg)
![04](https://user-images.githubusercontent.com/90407728/153718418-edc60746-e77e-40b3-9b84-58f2935c6166.jpg)

Сгенерированные на других датасетах картинки:
![mph01](https://user-images.githubusercontent.com/90407728/153720171-74cbb37b-c99b-4811-bb88-e0786ef27177.jpg)
![mph02](https://user-images.githubusercontent.com/90407728/153720178-41b2730e-72a3-4ba9-aa4c-926c52372efe.jpg)

![zh01](https://user-images.githubusercontent.com/90407728/153720189-bce4824e-1646-4f5c-a4e5-034f475f653e.jpg)
![zh02](https://user-images.githubusercontent.com/90407728/153720194-199dc41c-5f9f-449d-8e51-dcaaec84591f.jpg)

![ht01](https://user-images.githubusercontent.com/90407728/153720200-dce04480-2ccb-4a08-a4c7-fb412207481e.jpg)
![ht02](https://user-images.githubusercontent.com/90407728/153720204-dd8a4297-8adf-4295-b474-a097f4f64cef.jpg)







