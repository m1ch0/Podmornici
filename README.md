# Подморници
**Семинарска задача по предметот Визуелно програмирање**
##Опис на играта##
Семинарската задача ја опфаќа играта Подморници попозната под името ["Battleship"] (http://en.wikipedia.org/wiki/Battleship_%28game%29). Целта на играта да ги погодите поставените бродови на компјутерот и да издвојувате победа. Компјутерот имат две нивоа лесно и тешко за кои што се дефинирани алгоритами кои што во продолжение ќе биде подетално објаснети. И компјутерот и играчот имаат по 4 бродови со големина 2, 3, 4 и 5. Компјутерот ги разместува бродовите рандом, истата опција е овозможена за играчот или да ги размести самостојно како што тој сака. Откако бродчињата ќе бидат наместени играта може да започне.

##Објаснување на имлементацијата на играта##
Играта се состои од четири прозорци (форми). Во првата форма играчот внесува име, избира ниво и клика на копчето за започнување нова игра. Истотака може да отоври инструкции каде што накратко се дадени инструкции како да се игра играта.
![default](https://cloud.githubusercontent.com/assets/12381210/7554466/54ca1ee2-f72a-11e4-912a-551b92da94ad.png)

Со кликање на Нова игра се отвора вториот прозорец каде што корисникот треба да ги постави своите бродови на мапата. Има опција да бидат наместени случајно, самиот корисник да ги намести и доколку не е задоволен може да ги врати наместените бродови и да започне да ги реди одново. Со кликање на десен клик на бродовите може да ја менуваат својата положба од хоризонтално во вертикално и обратно.Доколку бродовите не се поставени во мапата или доколку има поклопивање истите се обојуваат црно со што му сугерираат на играчот дека не се добро поставени. Откако ќе бидат добро наредени односно нема да има поклопување играчот може да кликне на копчето започни игра.

 Лошо поставени бродови ![default](https://cloud.githubusercontent.com/assets/12381210/7554642/40759dc6-f730-11e4-8b0b-dddc69f1a4a1.png)
 
 Добро поставени бродови ![default](https://cloud.githubusercontent.com/assets/12381210/7554641/309bc7d6-f730-11e4-8416-4c03ebe41ce9.png)

Играта започнува со кликање на играчот на едно од полињата во деснтата мрежа при што доколку компјутерот има поставено брод квадратот се обојува црвено и играчот е повторно на потег, доколку промаши на потег е компјутерот. Доколку е погоден брод истиот се обојува со црна боја. Најдолу се соодвето поставени бродовите и во зависност од тоа дали се потопени или не се обојуваат во соодветна боја. Додадени се аудио фајлови за погодок на поле кое има брод, потопен брод и промашување.
![default](https://cloud.githubusercontent.com/assets/12381210/7554643/6063e87c-f730-11e4-9290-f8b793210a1d.png)

Играта завршува со потопување ан противничките бродови и соодветно се отвара последната форма, која што доколку сте победник изгледа :

![default](https://cloud.githubusercontent.com/assets/12381210/7554674/69ce0ffe-f731-11e4-9e8b-ab176b7f152e.png)

доколку изгубиде изгледа вака.

![default](https://cloud.githubusercontent.com/assets/12381210/7554670/5440e850-f731-11e4-8ebb-68a469ac2e4f.png)

Соодветно можете да започнете нова игра и да се вратите дома за да го променете името на играчот. 

**Пријатна игра !!!**
