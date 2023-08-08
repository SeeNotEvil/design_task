# Техническое задание на дизайн и моделирование волшебного свитка с подставкой
Задача разработать дизайн и смоделировать "волшебный свиток" вместе с "подставкой" под него.   

### По итогу должно получиться.   
1) Модель с текстурами, готовая к импорту в игровой движок unreal engine 5.   
2) Ряд скриншотов с отрандеренными моделями и текстурами, 5-6 штук, с разных ракурсов. Обязательно фронтальное изображение и перспектива.        
3) Оригинальные модели в vbx, с текстурами.     

#### Требования к модели   
1) Ограничения на полигоны нету.   
2) High poly модель приветствуется.   
3) Высокий уровень детализации и текстур.    
4) Импортируется в игровой движок unreal engine 5.    

#### Примеры аналогичных работ по уровню.  
https://www.artstation.com/artwork/DAGOJ0   
https://www.artstation.com/artwork/lxgK65   
https://www.artstation.com/artwork/EvLzB0   
https://www.artstation.com/artwork/Jvb4rZ   
https://www.artstation.com/artwork/kDl2aA   
https://www.artstation.com/artwork/Oo2OWv   
https://www.artstation.com/artwork/04zYQe   

### Структура
Схематично свиток состоит из следующих частей.   
1 - Верхняя планка   
2 - Нижняя планка   
3 - Активная зона - часть на которой будут рисунки (ее ничего не должно перекрывать)   
4 - Обрамление   
5 - Наконечники   
6 - Дракон (о нем смотри ниже)

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/sctructure.jpg" width="400"/>   

### Размеры
Размеры должны быть в метрической системе.   

1 - Верхняя планка - радиус 3.8 см, ширина 25 см   
2 - Нижняя планка - радиус 3.8 см, ширина 25 см   
3 - Активная область - ширина 20.3 см, высота 28.4 см. Она плотно прилегает к планкам сверху и снизу   
4 - Обрамление - ширина 0.85 см по краям   
5 - Наконечники - размеры подбираются индивидуально, около 3-6 см ширина каждого         
6 - Дракон - размеры подбираются индивидуально (о нем смотри ниже)   

#### Активная область   
Высота 28.4 см   
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/size_active_area.jpg" width="400"/> 
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/plank_add.jpg" width="400"/>  

Ширина 20.3 см   
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/size_active_area_2.jpg" width="400">  

#### Планки   
Радиус 3.8 см   
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/size_plank.jpg" width="400"/>  

Ширина 25 см  
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/size_plank_2.jpg" width="400"/>

#### Обрамление   
Ширина 0.85 см   
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/size_border.jpg" width="400"/>   

#### Наконечники
Наконечники находятся на всех планках, по краям справа и слева. Их ширина добавляется к каждой планке сверх ее ширины, то есть 25 см + 3-6 см с каждой из сторон.   

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/plank_border_2.jpg" width="400"/>   

### Внешний вид   
Свиток вертикальный, в развернутом виде.    
Активная зона у свитка прямая.    
На вверху верхней планки должна быть небольшая фигура дракона. Дракон не должен перекрывать активную зону свитка.      
Свиток в открытом виде ставится на подставку.    

Общий каркас свитка (без дракона)   

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/structure.jpg" width="400"/>   
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/structure_2.jpg" width="400"/>   

### Референсы

#### Планка (верхняя и нижняя)
Нужно, соблюдая такую же цветовую гамму и стиль, задизайнить планку исходя из референсов.   

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/plank_scroll_3.jpg" width="400"/> 
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/plank_scroll_6.jpg" width="400"/>     

#### Обрамление    
Обрамление должно быть в виде орнамента.  

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/stand.jpg" width="400"/>   

#### Наконечники  
На планки помимо обрамления добавляются драконьи наконечники.   

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/plank_border.jpg" width="400"/>  

#### Дракон.   
Расположен на верхней планке. Он не должен перекрывать активную зону свитка и быть не сильно громоздким.    

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/Dragon.jpg" width="400"/>   
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/Dragon_3.jpg" width="400"/>   

По текстуре дракон должен быть таким.   

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/Dragon_2.jpg" width="400"/>   

#### Пергамент   
Нужно сделать два вида пергамента внутри свитка, на месте его активной зоны.  
На пергаментах ничего не изображаем, свитки должны быть пустые.   

##### Черный пергамент   

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/black_pergament.jpg" width="400"/>   
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/black_pergament_2.jpg" width="400"/>   

На черном пергаменте должны быть видны хорошо разноцветные цернила.   
Там будут магические руны и т д.   

Пример цветов для магических рун.   

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/color.jpg" width="400"/>   
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/color_2.jpg" width="400"/>   

##### Белый пергамент.   

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/white_pergament.jpg" width="400"/>  

На белом пергаменте должны хорошо быть видны черные цернила.      

### Подставка
Свиток в развернутом виде ставится на подставку.   

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/stand_structure.jpg" width="400"/>   

#### Референсы    
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/stand_structure.jpg" width="400"/>   
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/stand_2.jpg" width="400"/>    

#### Размеры   
Размеры подставки подогнать под свиток, в зависимости от дизайна.   