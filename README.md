# markdown-math-test

## Документация

Документация формул http://docs.mathjax.org/en/latest/index.html.

Макросы http://docs.mathjax.org/en/latest/input/tex/macros/index.html.

## Фичи

Математика в тексте $1_{23}^4 + 1^\frac23 + 1_2^\frac34 + \dots + \dotsc + \frac12 + \left(\frac{1}{\frac{2}{\frac{3}{4}}}\right) + \dfrac{1}{\dfrac{2}{\dfrac{3}{4}}}$.

Выключная формула: $$E=mc^2 .$$

Коши с `\quad` после запятой: $$y'(t)=\frac{1}{6}(t+y), \quad y(0)=6 .$$

Многострочные уравнения должны быть в 1 строку в исходном тексте, вместо `\\` использовать `\\\\` (https://github.com/github/markup/issues/1547) $$\begin{multline} 1 + 2 + 3 + 4 + 5 + \\\\ + 6 + 7 + 8 + 9 + 10 + \\\\ + 11 + 12 + 13 + 14 + 15 . \end{multline}$$

Возможно вставать формулы в GH Markdown структуры:

Список:
- $1+1$
1. $1+1$

Таблица:
| $1+1$ 	|
|---	|

Семантика `\text` в математике + у латиницы гарнитура CM, у кириллицы – нет: $$math \qquad \text{semantics, семантика} \qquad математика .$$

## Расширенный алфавит

Греческий алфавит:

----- 
Альфа A \alpha	$A\ \alpha$

Бета	B \beta	$B\ \beta$

Гамма	\Gamma \gamma	$\Gamma\ \gamma$

Дельта	\Delta \delta	$\Delta\ \delta$

Эпсилон	E \epsilon \varepsilon	$E\ \epsilon\ \varepsilon$

Дзета	Z \zeta	$Z\ \zeta$

Эта	H \eta	$H\ \eta$

Тета	\Theta \theta \vartheta	$\Theta\ \theta\ \vartheta$

Йота	I \iota	$I\ \iota$

Каппа	K \kappa \varkappa*    	$K\ \kappa\ \varkappa$

Лямбда	\Lambda \lambda	$\Lambda\ \lambda$

Мю (ми)	M \mu	$M\ \mu$

Ню (ни)	N \nu	$N\ \nu$

Кси	\Xi \xi	$\Xi\ \xi$

Омикрон	O o	$O\ o$

Пи	\Pi \pi \varpi	$\Pi\ \pi\ \varpi$

Ро	P \rho \varrho	$P\ \rho\ \varrho$

Сигма	\Sigma \sigma \varsigma	$\Sigma\ \sigma\ \varsigma$

Тау	T \tau	$T\ \tau$

Ипсилон	\Upsilon \upsilon	$\Upsilon\ \upsilon$

Фи	\Phi \phi \varphi	$\Phi\ \phi\ \varphi$

Хи	X \chi	$X\ \chi$

Пси	\Psi \psi	$\Psi\ \psi$

Омега	\Omega \omega	$\Omega\ \omega$

----------

## Экранирование

Экранировать `$` в markdown можно, вставив внутрь кавычек \` или внутрь тега span `<span>$</span>`

## Лого

$\TeX$, $\LaTeX$.

## Ошибки

Ошибка в формуле выглядит так: $\oshibka{}$

$$\oshibkaVVikluchennoyFormule$$

## Невозможно сделать

Невозможно вставить формулу в GH Markdown структуры:

Заголовок:

###### $1+1$

Ссылка:

[$1+1$](/README.md)

Переносы длинной формулы на новую строку отсутсвуют: $1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1$

Нет альтернативы `$ $` на `\(  \)`. \(1_2^3\)

Equation окружение не поддерживает нумерацию: $$\begin{equation}1+1\end{equation} .$$

Отсутствие подмены комбинаций символов на лигатуры $<<$, $>>$, $--$, $---$.


