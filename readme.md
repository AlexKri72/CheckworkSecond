## Итоговая проверочная работа.
    
### Перед нами поставлена следующая задача:   
---
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа.   
Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.  

Примеры:  
["hello", "2", "world", ":-)"] -> ["2", ":-)"]  
["1234", "1567", "-2", "computer science"] -> ["-2"]  
["Russia", "Denmark", "Kazan"] -> []

### Решение:
---
Организован запрос количества слов и самих слов с клавиатуры.
Введенные слова записываются во входящий строковый массив `stringInArray` соответствующего размера.  
Далее в цикле берется каждый элемент из данного массива и присваивается строковому литералу, чтобы можно было узнать его длину.  
Если длина менее или равна трём, то этот элемент записывается в выходящий массив, для которого организован отдельный счётчик элементов, чтобы не было пустых строк.  
В конце производится печать выходного массива.
### Пример работы программы:
---

![Принт-скрин работы программы](/image.png)
