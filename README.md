# TASK 3.  Identical Elements 
Написати функцію  *findSameElements(int\* Arr1, int size1, int\* Arr2, int size2)*,\
яка приймає два масиви та знаходить в них однакові елементи.\
Виводить  значення та їх кількість, у порядку зростання значень.\
Фунція знаходиться в окремому файлі з назвою *functions.cpp,  functions.h*
\
Якщо масив, що потрапляє у функцію,  не валідний (вказує на **NULL**), то виводиться інформація про помилку *"Wrong array data"*.\
Якщо розмір масиву, що потрапляє у функцію, незадовільний, то виводиться інформація про помилку *"Wrong array size"*. \
Не забуваємо вкінці виводу '\n' або  **endl**.


### FYI 
Для перевірки своє функції можете писати код в *main.cpp*.\
Розмір масивів довільний, але не більше 20;  пам\*ять виділяється динамічно (через *new*).\
*main.cpp* не використовується для оцінювання задачі.


### Example
**Вхідні дані:** \
*масив1:     4, 1, 5*\
*масив2:     1,  5,  5, 4*\
\
**Вихідні дані:**\
//значення  -  к-ть\
          1 - 1\
          4 - 1\
          5 - 2
