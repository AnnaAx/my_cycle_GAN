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
