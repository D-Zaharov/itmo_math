# Задание 1
Найти период функции:
$$
y=3\sin (4\pi x+5).
$$

## Решение:
Период синусоидальной функции определяется как расстояние между двумя соседними точками с одинаковыми значениями функции. Обозначим период как $T$.
Для нахождения периода данной функции рассмотрим аргумент синуса, $4\pi x+5$.

В данном случае период находится как отношение периода функции $sin x$ к аргументу при переменной x .

Поскольку период синусоидальной функции равен $2\pi$, можем записать:

$T = \frac{2\pi}{4\pi}=\frac{1}{2}$

**Ответ:** Период функции $y=3\sin(4\pi x+5)$ равен $\frac{1}{2}$.



# Задание 2
Найти общее решение дифференциального уравнения
$$
y''+4y'+8y=0.
$$


##Решение:
Имеем линейное однородное уравнение второго порядка с постоянными коэффициентами.

Составим характеристическое уравнение и найдем его корни

$$k^{2} + 4k + 8 = 0$$

$D = 16 - 32 = -16$

$$k_{1} = -2 + 2i$$
$$k_{2} = -2 - 2i$$
тогда получаем, что
$y = (C_{1} ⋅ \sin 2x + C_{2} ⋅ \cos 2x) ⋅ e^{-2x}$

**Ответ:** $y = (C_{1} ⋅ \sin 2x + C_{2} ⋅ \cos 2x) ⋅ e^{-2x}$



# Задание 3

Вычислить интеграл
$$
\int\cfrac{2 dx}{3x+5}.
$$

## Решение

1. Замена переменной:
$u = 3x + 5$
$du = 3dx$
$dx = \frac{du}{3}$

2. Заменим переменную $x$ и $dx$ в исходном интеграле:
   $$\int\cfrac{2 dx}{3x+5} = \int\cfrac{2}{u}\cfrac{du}{3} = \cfrac{2}{3}\int\cfrac{du}{u}.$$

3. Проинтегрируем полученное выражение:
   $$\cfrac{2}{3}\int\cfrac{du}{u} = \cfrac{2}{3}\ln|u| + C.$$

4. Вернемся к исходной переменной:
   Подставим обратную замену $u = 3x + 5$:
   $$\cfrac{2}{3}\ln|u| + C = \cfrac{2}{3}\ln|3x + 5| + C.$$

Окончательное решение интеграла $\cfrac{2}{3}\ln|3x + 5| + C$, где $C$ - произвольная постоянная.

**ОТвет:** $\cfrac{2}{3}\ln|3x + 5| + C$, где $C$ - произвольная постоянная.



# Задание 4

Найти производную
$$
y=\sqrt{\tg x}.
$$

## Решение
Для нахождения производной функции $y=\sqrt{\tg x}$ воспользуемся правилом дифференцирования сложной функции.

Обозначим $u=\tg x$. Тогда функция $y$ может быть переписана в виде $y=\sqrt{u}$.

Применим правило дифференцирования сложной функции:

$$
\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx}.
$$

Найдем производные отдельных частей:
$$
\frac{dy}{du} = \frac{1}{2\sqrt{u}}
$$

$$
\frac{du}{dx} = \frac{1}{cos^{2} x}.
$$

Тогда

$$
\frac{dy}{dx} = \frac{1}{2\sqrt{\tg x} \cdot cos^{2} x}
$$

**Ответ:** $\frac{1}{2\sqrt{\tg x} \cdot cos^{2} x} $


# Задание 5

Найти интервалы возрастания и точки экстремума функции
$$
y=2x^3-6x^2-18x+22
$$

##Решение

1. Найдем производную функции $y$. Производная позволит нам определить моменты, когда функция возрастает или убывает, а также точки экстремума:
$$y' = 6x^2 - 12x - 18$$

2. Найдем точки, где производная равна нулю. Решим уравнение:

$$6x^2 - 12x - 18 = 0.$$

Разделим уравнение на 6:
$$x^2 - 2x - 3 = 0$$

По т. Виета:
$x_1 = 3$
$x_2 = -1$

3. Исследуем знак производной на интервалах между найденными точками и за пределами этих точек:

- Для $x < -1$:
Подставим $x = -2$ в производную $y'$:
$$y'(-2) = 6(-2)^2 - 12(-2) - 18 = 12 > 0.$$
Таким образом, на интервале $(-\infty, -1)$ функция возрастает.

- Для $-1 < x < 3$:
Подставим $x = 0$ в производную $y'$:
$$y'(0) = 6(0)^2 - 12(0) - 18 = -18 < 0.$$
Таким образом, на интервале $(-1, 3)$ функция убывает.

- Для $x > 3$:
Подставим $x = 4$ в производную $y'$:
$$y'(4) = 6(4)^2 - 12(4) - 18 = 42 > 0.$$
Таким образом, на интервале $(3, \infty)$ функция возрастает.
     
4. Найдем значения функции $y$ в найденных точках и на концах интервалов:
- Для $x = -1$: $$y(-1) = 2(-1)^3 - 6(-1)^2 - 18(-1) + 22 = 28.$$
- Для $x = 3$: $$y(3) = 2(3)^3 - 6(3)^2 - 18(3) + 22 = -4.$$

Итак, на основе анализа производной и значений функции в критических точках и на концах интервалов, получаем следующую информацию:

- Функция возрастает на интервалах $(-\infty, -1)$ и $(3, \infty)$.
- Функция убывает на интервале $(-1, 3)$.
- Точка экстремума: $x = -1$, $y = 28$ (максимум).
- Точка экстремума: $x = 3$, $y = -4$ (минимум).

**Ответ:** интервалы возрастания функции: $(-\infty, -1)$ и $(3, \infty)$, а точки экстремума: $(-1, 28)$ и $(3, -4)$.



# Задание 6

Решить систему уравнений наибольшим числом способов
$$
  \left\{
    \begin{aligned}
      2x+3y=12,\\
      3x+2y=13.            
    \end{aligned}
  \right.
$$

## Решение

### Способ 1, метод алгебраического сложения

1. Умножим первое уравнение на 2 и второе уравнение на 3, чтобы коэффициенты при $y$ в обоих уравнениях стали одинаковыми:
$$
  \left\{
    \begin{aligned}
      4x+6y=24,\\
      9x+6y=39.            
    \end{aligned}
  \right.
$$

2. Вычтем из уравнения 2 уравнение 1, чтобы устранить переменную $y$:

$5x = 15$
$x = 3$

3. Подставим найденное значение $x$ в любое из исходных уравнений, например, в первое уравнение и найдем y:

$2(3) + 3y = 12$
$3y = 6$

$y = 2$


**Ответ:** (3, 2)
### Способ 2, метод Крамера

1. Вычислим определитель основной системы уравнений:
   $$D = \begin{vmatrix} 2 & 3 \\ 3 & 2 \end{vmatrix} = (2 \cdot 2) - (3 \cdot 3) = -5.$$

2. Вычислим определитель для переменной x, заменяя столбец коэффициентов x:
   $$Dx = \begin{vmatrix} 12 & 3 \\ 13 & 2 \end{vmatrix} = (12 \cdot 2) - (3 \cdot 13) = -15.$$

3. Вычислим определитель для переменной y, заменяя столбец коэффициентов y:
   $$Dy = \begin{vmatrix} 2 & 12 \\ 3 & 13 \end{vmatrix} = (2 \cdot 13) - (12 \cdot 3) = 26 - 36 = -10.$$

4. Найдем значения переменных, разделив соответствующие определители на определитель основной системы:
   $$x = \frac{Dx}{D} = \frac{-15}{-5} = 3.$$
   $$y = \frac{Dy}{D} = \frac{-10}{-5} = 2.$$

Таким образом, решение системы уравнений методом Крамера:
$$\left\{ \begin{aligned}
x = 3, \\
y = 2.
\end{aligned} \right.$$

**Ответ:** (3, 2)

###Способ 3, метод подстановки
Выразим из первого уравнения x и подставим во второе:
$x = \frac{12 -3y}{2}$

$3 \cdot \frac{12 -3y}{2} +2y=13$

домножим обе части на 2

$3 \cdot (12 -3y) +4y=26$

$36 -9y +4y=26$

$36 -5y=26$

$-5y = -10$
$ y = 2$

Подставим в первое уравнение и найдем x:

$2x + 3 \cdot 2 = 12$

$2x + 6 = 12$
$2x = 6$
$x = 3$

**Ответ:** (3, 2)

### Способ 4, метод Гаусса

Для решения системы уравнений методом Гаусса приведем матрицу коэффициентов системы к единичному виду:

$$
\begin{bmatrix}
2 & 3 & 12 \\
3 & 2 & 13 \\
\end{bmatrix}
$$

Умножим первую строку на 3 и вторую строку на 2, а затем вычтем вторую строку из первой:

$$
\begin{bmatrix}
6 & 9 & 36 \\
6 & 4 & 26 \\
\end{bmatrix}
$$

Вычтем из второй строки первую:

$$
\begin{bmatrix}
6 & 9 & 36 \\
0 & -5 & -10 \\
\end{bmatrix}
$$

разделим первую строку на 6, а вторую на -5

$$
\begin{bmatrix}
1 & 1,5 & 6 \\
0 & 1 & 2 \\
\end{bmatrix}
$$
домножим вторую строку на -1,5 и сложим с первой:

$$
\begin{bmatrix}
1 & 0 & 3 \\
0 & 1 & 2 \\
\end{bmatrix}
$$

таким образом, $x = 3$, $y = 2$

**Ответ:** (3, 2)



#Задание 7
Исследовать  функцию на непрерывность
$$
y=\cfrac{x-1}{2+2^{1/x}}+\cfrac{|x+2|}{x^2+5x+6}.
$$

## Решение

Для исследования функции на непрерывность, мы должны учесть два аспекта: определение функции на всей области определения и отсутствие разрывов функции.

1. Область определения функции:
Избегаем деления на ноль и неопределенности под корнем. Для этого рассмотрим знаменатели обеих дробей в функции:

- Знаменатель первой дроби $2+2^{1/x}$:
Для того чтобы избежать деления на ноль, знаменатель не должен быть равен нулю. Так как $2^{1/x}$ всегда положительное число, то $2+2^{1/x}$ будет положительным для всех $x$.

- Знаменатель второй дроби $x^2+5x+6$:
Для избежания деления на ноль, знаменатель не должен быть равен нулю.
Найдем корни уравнения:
$x^2+5x+6 = 0$
по т. Виета:
$x_1 = -2$ 
$x_2 = -3$

В данных точках знаменатель равен 0

Область определения функции: $(-\infty, -3) \cup (-3, -2) \cup (-2, \infty)$.

2. Разрывы функции:
Проверим наличие разрывов в точках, где функция может быть неопределена или иметь различное значение на разных сторонах.

- В точке $x = -2$:
Проверим пределы функции при $x$ стремящемся к $-2$ справа и слева:
$$\lim{x \to -2^+} \left(\cfrac{x-1}{2+2^{1/x}}+\cfrac{|x+2|}{x^2+5x+6}\right) = -\infty,$$
$$\lim{x \to -2^-} \left(\cfrac{x-1}{2+2^{1/x}}+\cfrac{|x+2|}{x^2+5x+6}\right) = +\infty.$$
Пределы различны, поэтому функция имеет разрыв в точке $x = -2$.

- В точке $x = -3$:
Проверим пределы функции при $x$ стремящемся к $-3$ справа и слева:
$$\lim_{x \to -3^+} \left(\cfrac{x-1}{2+2^{1/x}}+\cfrac{|x+2|}{x^2+5x+6}\right) = +\infty,$$
$$\lim_{x \to -3^-} \left(\cfrac{x-1}{2+2^{1/x}}+\cfrac{|x+2|}{x^2+5x+6}\right) = +\infty.$$
Пределы равны, поэтому функция непрерывна в точке $x = -3$.

**Ответ:** функция $y$ непрерывна на интервалах $(-\infty, -3)$, $(-3, -2)$ и $(-2, \infty)$, кроме точки $x = -2$, где она имеет разрыв.



# Задание 8

Найти предел
$$
\lim_{n\to\infty} \cfrac{3n +4}{n^2+n+11}
$$
## Решение:
В числителе многочлен первой степени, а в знаменателе - второй. Многочлен второй степени при n, стремящейся к бесконечности будет расти быстрее, чем многочлен первой степени. Таким образом, данный предел будет равен 0.

также, для понимания этого можно поделить числитель и знаменатель на $n^{2}$

**Ответ:** 0



# Задание 9

На ГенАссамблее ООН присутствут 142 страны, делегаты которых говорят на разных языках. Сколько переводчиков нужно, чтобы обеспечит перевод между любыми  делегациями? (Переводчик для перевода, например, между русскоязычной и англоязычной делегацией один. Он обеспечивает перевод как с английского, так и с русского языка).


## Решение
Количество переводчиков будет зависеть от комбинации языков, на которых говорят делегаты. Пусть в общей сложности у нас есть n делегаций.

Тогда, чтобы определить количество переводчиков, нам нужно рассмотреть количество комбинаций языков между всеми делегациями.

Формула для определения количества комбинаций языков для n делегаций можно записать как формулу арефметической прогрессии:

Количество комбинаций = $n \cdot \frac{n - 1}{2}$

тогда:

Количество комбинаций = $\frac{142 \cdot 141}{2} = 10011$

Таким образом, нам потребуется 10011 переводчиков, чтобы обеспечить перевод между любыми делегациями при условии, что каждая делегация говорит на своем официальном языке.

**Ответ:** 10011



# Задание 10

Вокруг  круглого стола расставлены 6 стульев. Какова вероятность, что из  6 человек, которые случайным образом рассаживаются по этим стульям, двое избранных сядут рядом?

## Решение

Предположим, что один из выбранных человек уже сел. Тогда остается 5 свободных стульев и 5 человек, которые могут на них сесть. Для благоприятного исхода, второй выбранный человек должен сесть либо на стул слева, либо на стул справа от первого, всего 2 варианта. Тогда вероятность, что 2 выбранных человека будут сидеть рядом считается как:
$P = \frac{2}{5} = 0,4$

**Ответ:** 0,4