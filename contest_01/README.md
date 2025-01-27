## Task № 1
### A. Математика спешит на помощь

Начинающий математик Ксения учится в третьем классе. Сейчас в школе она проходит операцию сложения.

Учитель записал на доске сумму нескольких чисел, которую требуется посчитать. Чтобы было проще считать, в сумме используются только числа 1, 2 и 3. Но и этого Ксении мало. Ксения только учится считать, и поэтому она может посчитать сумму, только если слагаемые в сумме идут в порядке неубывания. Например, сумму 1+3+2+1 она посчитать не может, а суммы 1+1+2 и 3+3 может.

Вам задана сумма, которая записана на доске. Переставьте слагаемые и выведите ее в виде, в котором Ксения сможет посчитать сумму.

Входные данные
В первой строке записана непустая строка s — сумма, которую нужно посчитать Ксении. Строка s не содержит пробелов, состоит только из цифр и знаков «+» и является корректной суммой чисел 1, 2 и 3. Длина строки s не более 100 символов.

Выходные данные
Выведите новую сумму, которую сможет посчитать Ксения. 

Примеры:  

входные данные:  
3+2+1  
выходные данные:  
1+2+3  

входные данные:  
1+1+3+1+3  
выходные данные:  
1+1+1+3+3  

входные данные:  
2  
выходные данные:  
2  

## Task № 2
### Капитализация слова

Капитализация — это запись слова, в которой первая буква слова записывается как прописная буква. Ваша задача, вывести капитализацию заданного слова.

Обратите внимание, что в капитализации все буквы слова кроме первой остаются не измененными.

Входные данные
В первой строке записано непустое слово. Слово состоит из строчных и прописных букв латинского алфавита. Длина заданного слова не превосходит 103 букв.

Выходные данные
Выведите капитализацию слова.

Примеры:  

входные данные:  
ApPLe  
выходные данные:  
ApPLe  

входные данные:  
konjac  
выходные данные:  
Konjac  

## Task № 3
### C. Камни на столе

На столе в ряд выложены n камней, каждый из которых может быть красного, зеленого или синего цвета. Посчитайте, какое минимальное количество камней нужно убрать со стола, чтобы любые два соседних камня имели разные цвета. Камни в ряду считаются соседними, если между ними нет других камней.

Входные данные
В первой строке задано целое число n (1 ≤ n ≤ 50) — количество камней на столе.

В следующей строке задана строка s, обозначающая цвета камней. Будем считать, что камни в ряду пронумерованы целыми числами от 1 до n слева направо. Тогда i-ый символ s равен «R», если i-ый камень красного цвета, «G» — если он зеленого цвета, и «B» — если он синего цвета.

Выходные данные
Выведите единственное целое число — ответ на задачу.

Примеры:  

входные данные:  
3  
RRG  
выходные данные:  
1  

входные данные:  
5  
RRRRR  
выходные данные:  
4  

входные данные:  
4  
BRBG  
выходные данные:  
0  

## Task № 4
### D. Девушка или Юноша
 
В наши дни очень много парней ставят себе фотографии красивых девушек на аватарки на форумах. Из-за этого очень часто сложно определить пол пользователя на форуме. В прошлом году наш герой пообщался в чате на форуме с одной красоткой (как он думал). После этого наш герой и предполагаемая красотка стали общаться еще чаще и в конце концов стали парой в сети.

Но вчера наш герой захотел увидеть свою красотку в реальной жизни и, каково же было его удивление, когда красоткой оказался здоровенный мужчина! Наш герой очень расстроился и теперь он, наверное, никогда больше не сможет полюбить. Сейчас к нему пришла в голову идея, как по имени пользователя определить его пол.

Вот его метод: если количество различных символов в имени пользователя нечетное, тогда пользователь мужского пола, иначе — женского. Вам дана строка, обозначающая имя пользователя, помогите нашему герою определить по ней пол пользователя по описанному методу.

Входные данные
В первой строке записана непустая строка, состоящая только из строчных букв латинского алфавита — имя пользователя. Эта строка состоит из не более чем 100 букв.

Выходные данные
Если пользователь оказался женского пола по методу нашего героя, выведите «CHAT WITH HER!» (без кавычек), иначе, выведите «IGNORE HIM!» (без кавычек).

Примеры:

входные данные:  
wjmzbmr  
выходные данные:  
CHAT WITH HER!  

входные данные:  
xiaodao  
выходные данные:  
IGNORE HIM!  

входные данные:  
sevenkplus  
выходные данные:  
CHAT WITH HER!  

## Task № 5
### E. Мишка и старший брат

Мишка Лимак хочет стать самым большим медведем, ну, или хотя бы стать больше своего старшего брата Боба.

Сейчас вес Лимака равен a, а вес Боба равен b. Гарантируется, что вес Лимака меньше или равен весу Боба.

Лимак ест много, и его вес утраивается каждый год, а вес Боба удваивается каждый год.

Через сколько целых лет Лимак станет строго больше (т. е. будет весить строго больше) Боба?

Входные данные
В единственной строке находятся два целых числа a и b (1 ≤ a ≤ b ≤ 10) — веса Лимака и Боба соответственно.

Выходные данные
Выведите одно целое число — через сколько целых лет Лимак станет строго больше Боба.

Примеры:  

входные данные:  
4 7  
выходные данные:  
2  

входные данные:  
4 9  
выходные данные:  
3  

входные данные:  
1 1  
выходные данные:  
1  

Примечание:
В первом примере изначально вес Лимака равен 4, а вес Боба — 7. Через год их веса равны 4·3 = 12 и 7·2 = 14 соответственно (один вес утроился, а второй удвоился). Лимак все еще не больше Боба. Через два года их веса равны 36 и 28, то есть вес Лимака больше, чем вес Боба. Лимак стал больше Боба через два года, поэтому вы должны вывести 2.

Во втором примере веса Лимака и Боба в последующие года равны: 12 и 18, затем 36 и 36, и наконец 108 и 72 (через три года). Ответ равен 3. Помните, что Лимак хочет стать строго больше Боба, и его не устроят равные веса.

В третьем примере Лимак станет больше Боба через один год, их веса будут равны 3 и 2 соответственно.

## Task № 6
### F. Юный физик

В одной школе в 11 классе учится мальчик Вася. Как-то раз Вася решил посмотреть матч своей любимой хоккейной команды. А поскольку мальчик очень любит хоккей, даже больше, чем физику, он забыл сделать уроки. В частности, забыл сделать задачки по физике. На следующий день учитель очень разозлился на Васю, и решил его проучить. Он дал нерадивому ученику, казалось бы, простую задачку: дано покоящееся тело в пространстве, и даны силы, действующие на него. Тело можно считать материальной точкой с координатами (0; 0; 0). Васе нужно было ответить, находится ли оно в равновесии. «Ерунда!» — подумал Вася, нужно лишь проверить, что сумма всех векторов равна 0, и принялся решать задачу. Но впоследствии оказалось, что этих сил может быть очень-очень много, и Вася не справится без вашей помощи. Помогите ему. Напишите программу, которая определяет по заданным векторам сил, покоится тело или движется.

Входные данные
В первой строке задано натуральное число n (1 ≤ n ≤ 100), далее следует n строк по три целых числа в каждой: координата xi, координата yi и координата zi вектора силы, приложенной к телу ( - 100 ≤ xi, yi, zi ≤ 100).

Выходные данные
Выведите слово "YES" если тело находится в равновесии, или слово "NO" если не находится.

Примеры:  
  
входные данные:  
3  
4 1 7  
-2 4 -1  
1 -5 -3  
выходные данные:  
NO  

входные данные:  
3  
3 -1 7  
-5 2 -4  
2 -1 -3  
выходные данные:  
YES  

## Task № 7
### G. Футбол

Петя очень любит футбол. Однажды, глядя футбольный матч, он записывал на листе бумаги текущее положение игроков. Для простоты он изобразил ситуацию в виде строки из нулей и единиц. Ноль соответствует игрокам одной команды, единица — игрокам другой команды. Если есть как минимум 7 игроков некоторой команды, стоящих подряд, то эта ситуация считается опасной. Например, ситуация 00100110111111101 — опасная, а 11110111011101 — нет. Вам задана текущая ситуация. Определите, является ли она опасной.

Входные данные
В первой строке ввода задана непустая строка из символов «0» и «1», обозначающих игроков. Длина строки не превышает 100 символов. От каждой команды на поле присутствует хотя бы один игрок.

Выходные данные
Выведите «YES» если ситуация опасная. В противном случае выведите «NO».

Примеры:

входные данные:  
001001  
выходные данные:  
NO  

входные данные:  
1000000001  
выходные данные:  
YES  

## Task № 8
### H. Слоник

Слоник решил сходить в гости к другу. Оказалось, что дом слоника находится в точке 0, а дом его друга в точке x(x > 0) координатной прямой. За один шаг слоник может переместиться на 1, 2, 3, 4 или 5 позиций вперёд. Помогите ему определить, за какое минимальное количество шагов он может добраться до дома друга.

Входные данные
В первой строке входных данных записано одно целое число x (1 ≤ x ≤ 1 000 000) — координата дома друга слоника.

Выходные данные
Выведите минимальное количество шагов, которые необходимо сделать слонику, чтобы попасть из точки 0 в точку x.

Примеры:  

входные данные:  
5  
выходные данные:  
1  
входные данные:  
12  
выходные данные:  
3  

Примечание
В первом примере слоник может за один шаг передвинуться на 5 позиций и достигнуть точки x.

Во втором примере слоник может попасть в точку x, сходив на 3, 5 и 4 позиции. Есть и другие способы получить оптимальный ответ, но слоник не может достичь x быстрее, чем за 3 шага.


## Task № 9
### I. Неправильное вычитание
ограничение по времени на тест1 секунда
ограничение по памяти на тест256 мегабайт
Маленькая девочка Таня учится уменьшать числа на единицу, но она делает это неправильно с числами, состоящими из нескольких цифр. Таня вычитает единицу из числа по следующему алгоритму:

если последняя цифра числа не равна нулю, она уменьшает число на единицу;
если последняя цифра числа равна нулю, она делит число на 10 (то есть удаляет его последнюю цифру).
Вам задано целое число n
. Таня хочет вычесть из него единицу k
 раз. Ваша задача вывести результат после всех k
 вычитаний.

Гарантируется, что ответ будет являться целым положительным числом.

Входные данные
Первая строка входных данных содержит два целых числа n
 и k
 (2≤n≤109
, 1≤k≤50
) — число, из которого Таня хочет вычитать единицу и количество вычитаний соответственно.

Выходные данные
Выведите одно целое число — результат вычитания из n
 единицы k
 раз.

Гарантируется, что ответ будет являться целым положительным числом.

Примеры:  

входные данные:   
512 4
выходные данные:  
50
входные данные:  
1000000000 9
выходные данные:  
1

Примечание
В первом тестовом примере последовательность преобразований будет выглядеть так: 512→511→510→51→50



## Task № 10
### J. Слово

Васю очень огорчает, что многие люди в интернете смешивают маленькие и большие буквы в одном слове. Поэтому он решил разработать расширение для своего любимого браузера, которое меняет регистр букв в каждом слове так, чтобы оно либо состояло только из маленьких букв, либо, наоборот, только из больших. При этом в слове должно измениться как можно меньше букв. Например, слово HoUse должно замениться на house, а слово ViP — на VIP. В случае, если в слове содержится одинаковое количество маленьких и больших букв, нужно заменить все буквы на маленькие. Например, maTRIx нужно заменить на matrix. Ваша задача — обработать указанным способом одно заданное слово.

Входные данные
В первой строке записано слово s — оно состоит из больших и маленьких латинских букв и имеет длину от 1 до 100.

Выходные данные
Выведите исправленное слово s. Если в заданном слове s строго больше заглавных букв, приведите его к верхнему регистру, иначе — к нижнему.

Примеры:  

входные данные:  
HoUse
выходные данные:  
house

входные данные:  
ViP
выходные данные:  
VIP

входные данные:  
maTRIx
выходные данные:  
matrix

