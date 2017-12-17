## 1.Что это такое ?
Это программа для решения квадратный уравнений
Программа принимает на вход значение коэффициентов a,b,c квадратного уравнения и возвращает значение корней

## 2.Системные требования
Для работы с программой понадобится Python3.5,который скорее всего у вас уже установлен, но если по каким-то причинам его не оказалось:
 -   sudo apt install python3.5, для deb-систем
 -   sudo yum install python3.5, для rpm-систем

## 3.Где можно заполучить этот  код  
Можно скачать здесь - [quadratic_equations](https://github.com/aligang/7_mistery_fix)

## 4.Как этим пользоваться...   
Программа не предназначена для прямого запуска, но описанные в ней функции  могут  быть исползованы через импорт

## 5.Какие функции могут быть переиспользованы в вашем коде  
В программе присутвует функция:  
- get_roots

**get_roots** отвечает  за решение квадратного уравнения. Импортировать функцию кода можно, добавив следущую строчку:  
`from quadratic_equation import get_roots`  
и использовать укаказав коэффициенты квадратного уравнения, например  
`root1,root2 = get_roots(a,b,c)`

## 6. Цели
Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)

