# Техническое задание на дизайн и моделирование волшебного свитка с подставкой
Задача разработать дизайн и смоделировать "волшебный свиток" вместе с "подставкой" под него.   

## Требования   
#### По итогу должно получиться   
1) Модель с текстурами, готовая к импорту в игровой движок unreal engine 5.   
2) Ряд скриншотов с отрандеренными моделями и текстурами, минимум 5-6 штук, с разных ракурсов. Обязательно фронтальное изображение и перспектива.        
3) Оригинальные модели в vbx, с текстурами.     
4) Скриншоты с основными размерами модели (смотри раздел размеры).   

#### Требования к модели   
1) Ограничения на полигоны нет.   
2) High poly модель приветствуется.   
3) Высокий уровень детализации и текстур.    
4) Импортируется в игровой движок unreal engine 5.    

#### Примеры аналогичных по уровню работ  
https://www.artstation.com/artwork/DAGOJ0   
https://www.artstation.com/artwork/lxgK65   
https://www.artstation.com/artwork/EvLzB0   
https://www.artstation.com/artwork/Jvb4rZ   
https://www.artstation.com/artwork/kDl2aA   
https://www.artstation.com/artwork/Oo2OWv   
https://www.artstation.com/artwork/04zYQe   

## Структура и размеры   
Схематично свиток состоит из следующих частей.   
1 - Верхняя планка.   
2 - Нижняя планка.   
3 - Активная область - часть на которой будут рисунки (ее ничего не должно перекрывать).   
4 - Обрамление.   
5 - Наконечники.   
6 - Дракон.

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/scheme.jpg" width="400"/>   

#### Размеры
Размеры задаются в метрической системе.   

1 - Верхняя планка - диаметр 5 см, ширина 26.5 см.   
2 - Нижняя планка - диаметр 5 см, ширина 26.5 см.   
3 - Активная область - ширина 20.3 см, высота 27.1 см, толщина 1.35 мм. Она плотно прилегает к планкам сверху и снизу.   
4 - Обрамление - ширина 1.1 см по краям.   
5 - Наконечники - размеры подбираются индивидуально, около 1.5 см ширина и диаметр 6 см (можно делать больше).         
6 - Дракон - размеры подбираются индивидуально и исходя из референсов (о нем смотри ниже).   

#### Планки и наконечники 
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/size_plank.jpg" width="400"/>  

#### Щирина активной области и обрамление    
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/size_border.jpg" width="400"/>

#### Активная область  
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/size_active_area.jpg" width="400"/>  

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/plank_add.jpg" width="400"/>  

Высота между внутренними краями планок ~27.4 см.   
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/size_active_area_view.jpg" width="400"/>  

#### Дракон   
Размеры подбираются индивидуально и исходя из референсов. Единственное условие, в него должен помещаться квадрат 8 см x 5.5 x 1 см.   

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/dragon_size.jpg" width="400"/>  

## Внешний вид и референсы     
Свиток вертикальный, в развернутом виде.    
Активная область у свитка прямая.    
На вверху верхней планки расположена фигура дракона.      
Свиток в открытом виде ставится на подставку.    

Общий каркас свитка.     

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/structure.jpg" width="400"/>     

#### Планка (верхняя и нижняя)
Соблюдая такую же цветовую гамму и стиль, сделать дизайн, исходя из референсов.   

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/plank_scroll_6.jpg" width="400"/>   
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/plank_scroll_3.jpg" width="400"/>   
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/plank_scroll_4.jpg" width="400"/>  

#### Обрамление    
Обрамление, должно быть, в виде орнамента.  

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/stand.jpg" width="400"/>   

#### Наконечники  
На планки добавляются драконьи наконечники.   

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/plank_border.jpg" width="400"/>  

#### Дракон.   
Расположен на верхней планке. Он **не перекрывает собой активную область свитка**.   

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/Dragon.jpg" width="400"/>   

Должно оставаться место, для того чтобы, брать свиток руками.  
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/scroll_in_hand_2.jpg" width="400"/>   

**По текстуре и цвету дракон как на референсе ниже.**      

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/Dragon_2.jpg" width="400"/>   

#### Пергамент   
Сделать два вида пергамента внутри свитка, на месте его активной области.     
Пергаменты как пустые, так и с текстом (текст рыба) с разными чернилами.     
Чернила и свиток должны вместе сочетаться.   

##### Черный пергамент   
 
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/black_pergament_2.jpg" width="400"/>   

На черном пергаменте, должны хорошо, быть видны разноцветные чернила.   
Пример цветов (разноцветных, магических, светящихся) чернил.   

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/color.jpg" width="400"/>   
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/color_2.jpg" width="400"/>   

##### Белый пергамент     

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/white_pergament.jpg" width="400"/>  

На белом пергаменте, должны хорошо, быть видны черные чернила.      

## Подставка
Свиток в **развернутом** виде ставится на подставку.   
Угол под которым стоит свиток - 18 градусов.   
Активная область не должна загибаться, а быть прямой, как на рисунке ниже.   

<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/scroll_angle.jpg" width="400"/>   

#### Референсы подставки   
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/stand_structure.jpg" width="400"/>   
<img src="https://github.com/SeeNotEvil/design_task/blob/main/technical_task_scroll/stand_2.jpg" width="400"/>    

#### Размеры   
Размеры подставки подогнать под свиток, в зависимости от, дизайна.   
 
[Доп ссылка с файлом blend с которого снимались размеры](https://github.com/SeeNotEvil/design_task/tree/main/technical_task_scroll/blender) 
