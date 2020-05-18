# obrabMultimediaLab4
### --Flip horizontal--
Оранжевый= 0.1
Синий= 0.09
Красный= 0.085.


Обучающая выборка: 

1) на графике точности Оранжевый сходится лучше остальных. 

2) На графике потерь все ведут себ япрактически одинаково, у Оранжевого виден выброс на 37 шаге.
В конце Оранжевый имеет наименьшее значение.

![1](https://github.com/IGRICHINSKYBSU/obrabMultimediaLab4/raw/master/1.jpg) 
Валидационная выборка: 

1) на графике точности Оранжевый имеет наименьший разброс по сравнению с Синим и Красным. 

2) На графике потерь Красный изначально имеет выброс, но потом значение ошибки уменьшается и поведение всех трех графиков очень схоже.

![1](https://github.com/IGRICHINSKYBSU/obrabMultimediaLab4/raw/master/2.jpg)
### Считаю что наилучший график Оранжевый= 0.1

### --Rotate--
Оранжевый=(lr = 0.1, поворот на 45)
Синий=(lr = 0.09, поворот на 90)
Красный=(lr = 0.005, поворот на 23)


Обучающая выборка: 

1) на графике точности Синий обучается медленно, но лучше остальных, скорость схождения у него маленькая. Оранжевый и Красный ведут себя похоже. 

2) на графике потерь видно, что все ведут себя примерно одинаково, Красный сходится быстрее остальных, но в конце минимальное значение имеет Синий график, равное 0.4152, Красный 0.6712, Оранжевый 0.8642
![1](https://github.com/IGRICHINSKYBSU/obrabMultimediaLab4/raw/master/3.jpg)
Валидационная выборка: 

1) на графике точности все имеют достаточно большие разбросы, но если посмотреть на Синий, то под конец у него замечается снижение точности, в то время как Оранжевый и Красный ведут себя примерно одинаково. 

2) на графике потерь Оранжевый график сходится на 1 шаге и после поведение графиков очень схоже, без выбросов.

![1](https://github.com/IGRICHINSKYBSU/obrabMultimediaLab4/raw/master/4.jpg)
### Считаю что наилучший график Оранжевый=(lr = 0.1, поворот на 45)

### --Brightness and contrast--
Оранжевый=(lr = 0.1, brightness = 0.4, contrast = 0.9-2.1)
Синий=(lr = 0.1, brightness = 0.2, contrast = 0.1-1.9)
Красный=(lr = 0.1, brightness = 0.3, contrast = 0.2-0.7)


Обучающая выборка: 

1) на графике точности все ведут себя примерно одинаково, но по моему мнению Синий показывает себя немного лучше остальных, тк принимает максимальное на 73 шаге, равное 0.7238. В конце так же Синий имеет наибольшую точность равную 0.6347.

2) на графике потерь Синий график сходися быстрее остальных. Далее можно видеть совсем небольшие выбросы у каждого. В конце Синий график имеет наименьшее значение 0.9352, Красный- 1.034, Оранжевый- 0.9888.

![1](https://github.com/IGRICHINSKYBSU/obrabMultimediaLab4/raw/master/5.jpg)

Валидационная выборка: 

1) на графике точности все имеют примерно одинаковый разброс, но Синий график имеет более меньшие скачки вниз. 

2) на графике потерь можно у каждого заметить выброс, при том у Красного он значительно больше. Оранжевый и Синий себя ведут примерно одинаково и имеют выбросы, как и Красный на все графике. 

![1](https://github.com/IGRICHINSKYBSU/obrabMultimediaLab4/raw/master/6.jpg)
### Считаю что наилучший график Оранжевый=(lr = 0.1, brightness = 0.2, contrast = 0.1-1.9)


### --Crop--
Оранжевый=(lr = 0.1, вырез 20х20 из 224х224)
Синий=(lr = 0.1, вырез 40х40 из 224х224)
Красный=(lr = 0.1, центральное приближение 0.3)

Обучающая выборка:

1) на графике точности Синий прервался на 79 шаге. Можно выделить Красный график, тк у него верхние скачки имеют наибольшие значениия, а нижние-менее выражены по сравнению с остальными. 

2) на графике потерь графики ведут себя похоже, без характерных выбросов и сходятся примерно одинаково.

![1](https://github.com/IGRICHINSKYBSU/obrabMultimediaLab4/raw/master/7.jpg)
Валидационная выборка: 

1) на графике точности все ведут себя примерно одинаково, у Красного графика наименее выраженные выбросы вниз. 

2) на графике потерь Оранжевый и Красный схоже себя ведут, в то время как у Синего графика имеется имеется значительный выброс в самом начале.

![1](https://github.com/IGRICHINSKYBSU/obrabMultimediaLab4/raw/master/8.jpg)
### Считаю что наилучший график Красный=(lr = 0.1, центральное приближение 0.3)

