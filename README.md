# markdown-math-test

Документация формул http://docs.mathjax.org/en/latest/index.html.

Макросы http://docs.mathjax.org/en/latest/input/tex/macros/index.html.

Логотипы $\TeX$, $\LaTeX$

Математика в тексте $1_{23}^3 + \frac12 + \left(\frac{1}{\frac{1}{\frac{1}{2}}}\right) + \dfrac{1}{\dfrac{1}{\dfrac{1}{2}}}$.

Выключная формула: $$E=mc^2 .$$

Коши с `\quad` после запятой: $$y'(t)=\frac{1}{6}(t+y), \quad y(0)=6 .$$

Семантика `\text` в математике + у латиницы гарнитура CM, у кириллицы – нет: $$math \qquad \text{semantics, семантика} \qquad математика .$$

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

Ошибка в формуле выглядит так: $\oshibka{}$

Невозможно всавить формулу в GH Markdown структуры:

Заголовок:
###### $1+1$

Список:
- $1+1$
1. $1+1$

Таблица:
| $1+1$ 	|
|---	|

Ссылка:
[$1+1$](/README.md)

Переносы длинной формулы на новую строку отстутсвуют: $1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1+1$

Нет альтернативы `$ $` на `\(  \)`.

Equation окружение не поддерживает нумерацию: $$\begin{equation}1+1\end{equation} .$$

Отсутствие подмены комбинаций символов на лигатуры $\text{<< >> -- ---}$ .

Отсутствие многострочных формул (системы уравнений, матрицы, gather окружения) http://docs.mathjax.org/en/latest/output/linebreaks.html.

