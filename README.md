<b>Часть первая</b>  

Иерархическая кластеризация данных и использование функции DBSCAN().
Использовался набор данных mtcars (Motor Trend Car Road Tests). Данные содержат информацию о 32 автомобилях (1973-1974 года выпуска). По каждому автомобилю 
представлено 11 характеристик: число цилиндров двигателя, объем двигателя (куб. дюймов), мощность двигателя, передаточное число заднего моста, вес и пр.

Для иерархической кластеризации и построения дендрограммы использовались функции linkage и dendrogram из библиотеки scipy.cluster.hierarchy. Предварительно данные были 
стандартизированы. Результат приведен в виде дендрограммы.

Функцию DBSCAN рекомендуют использовать для «зашумленных» данных, но для наглядности результата был использован тот же набор данных. Данные были стандартизированы, 
а затем для визуализации на плоскости методом главных компонент сведены к двум переменным.

На графике данные, относящиеся к первому кластеру выделены желтым цветом, ко второму – зеленым, к третьему – синим, красный соответствуем выбросам, с точки зрения алгоритма

<b>Часть вторая</b>  

Написать сверточный автоэнкодер длясжатия и восстановления изображений.  
Изображения генерировались с помощью ImageDataGenerator библиотеки Keras.

