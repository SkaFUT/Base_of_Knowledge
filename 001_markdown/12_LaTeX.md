# Тема: LaTeX
    Для того чтобы формулы стали восприниматься как LaTeX, нужно использовать символ($ или $$) в начале и в конце, при использовании $$ формула будет располагаться по центру страницы.

^b928ae

### 1. Инлайн-формулы:  

^157606

Квадратное уравнение: ax^2 + bx + c = 0  
$ax^2 + bx + c = 0$,где $a$, $b$ и $с$ - действительные числа
***

### 2. Выведенные формулы:

^cb0ab3

$$
ax^2 + bx + c = 0
$$

$$
E=mc^2
$$  
- Для добавления **порядкового номера** для формулы используем ниже приведённый пример:
$$
\begin{equation}
ax^2 + bx + c = 0
\end{equation}
$$

$$
\begin{equation}
E=mc^2
\end{equation}
$$
***

### 3. Греческие буквы :

^2688ff

- Для написания **греческих букв**, используем [эту таблицу](10_practice.md)  

$$
\pi
\theta
\xi
$$
- Также в LaTeX есть обозначения символов таких как принадлежности, больше меньше и тд
$$
n \in \N
$$
***

### 4. Дроби:

^0c9248

- Для создания **дроби** используется(\\frac{}{})
$$
\frac{1}{\frac{1}{\frac{1}{2\frac{1}{\frac{1}{2\frac{1}{2}}}}}}
$$
- Для создания **корня**(\\sqrt)  
$\sqrt{\frac{1}{2}}$
- **Точка** над символом (\\dot)
$$
\dot a
$$
- Более красивый знак **умножения**(\\cdot):
$$
a \cdot b
$$
***

### 5. Индексы и степени:

^e0ff23

- Для создания **индекса** используется символ (_), пример a_1, a_2 и тд.
$$
a_1,a_2,a_3...a_n
$$
- Для создания **степени** используется символ (^), пример a^2.
$$
a^2
$$
- Для создания **степеней/индексов** с *более чем 1 цифрой*(22,546), то используется (^{}/_{} соответственно), пример: a^{23}.  
***
Пример *ошибки*:
$$
a^22
$$
Пример *правильного* использования:
$$
a^{22}
$$
***

### 6. Сумма и интеграл:
- **Сумма**(\\sum_{*то что снизу*}^{*то что сверху*})
$$
e = \sum_{i=1}^{10}i=1+2+3...+10=\frac{10*11}{2}
$$
- **Интеграл**(\\int_{*то что снизу*}^{*то что сверху*})
$$
\int_{1}^{\infty}*\frac{dx}{x}=1
$$
***

### 7. Матрицы:

^f8044c

- Для создания матрицы мы используем (\\begin{bmatrix} и \\end{bmatrix}), а для разделения элементов внутри матрицы используем амперсанд(&).
$$
\begin{bmatrix}
1&1\\
2&4\\
6&45454\\
\end{bmatrix}
$$
***
[[MarkDown|Оглавление]]