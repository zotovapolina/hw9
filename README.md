# hw9
## Задание №1
Чтобы убрать пустые строки, я использовала регулярное выражение **\n\r** и заменила все вхождения на **\0**.

Все пустые строки удалились. 

![](https://raw.githubusercontent.com/zotovapolina/hw9/master/%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%201.png)

## Задание №2
Чтобы найти всех князей и города, имя и название которых оканчивается на "слав", использовала регулярное выражение \b[А-Я][а-я]*слав[а-я]{0,3}\b
 
 Всего упоминаний в тексте:561
 ![](https://raw.githubusercontent.com/zotovapolina/hw9/master/%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%202.png)
 
 ## Задание №3 
Чтобы найти все упоминания Новгорода, использовала регулярное выражение Н\D?о\D?в\D?г\D?о\D?р\D?о\D?д\w*
59 упоминаний Новгорода в тексте.
![](https://raw.githubusercontent.com/zotovapolina/hw9/master/%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%203.png)
