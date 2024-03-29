# Structured-programming

## Променливи, оператори, влез-излез
### Аритметички операции
Да се напише програма која ќе ги изведува основните математички операции (+, -, *, /, %) врз два броја кои се читаат од стандарден влез.

### Индекс на телесна маса
Да се напише програма која вчитува од стандарден влез два децимални броја (маса во кг и висина во цм) и пресметува и печати на стандарден излез индекс на телесна маса по формулата:

BMI=masa/(visina∗visina)
Висината претходно треба да се претвори од сантиметри во метри.

### Секунди во време 
Да се напише програма коjа за даден цел броj секунди коj се чита од стандарден влез, ќе ги отпечати на екран соодветните вредности во часови, минути и секунди.

### Просек 
Да се напише програма која пресметува просечна оцена во семестар. Програмата чита 5 цели броја. Треба да се испечати еден реален број на две децимали, просек на прочитаните броеви.

### Банкноти и монети
Да се напише програма која за дадена сума на пари, ќе испечати со колку најмалку банкноти и монети може да се исплати. На влез се чита еден цел број. На излез се печатат 9 редови, по колку банкноти или монети од секој апоен ни се потребни за да ја исплатиме сумата. Пример 1583 денари, најдобро е да се исплати како:

0*5000

1*1000

1*500

0*100

1*50

3*10

0*5

1*2

1*1

## Контролни структури за избор 
### Број палиндром
Да се напише програма која за трицифрен број прочитан од стандарден влез ќе проверува дали е палиндром. Ако бројот е палиндром, на екран треба да се испечати порака "Palindrom", во спротивно - "Ne e palindrom". Доколку внесениот број не е трицифрен треба да се испечати порака "Nevaliden vlez".

### Правоаголник и квадрат
Да се напише програма во која од стандарден влез се читаат два броја што претставуваат должини на страни на правоаголник, како и еден број што претставува должина на страна на квадрат. Програмата треба да испечати "Pravoagolnik" ако правоаголникот има поголем периметар, или "Kvadrat" ако квадратот има поголем периметар. Ако имаат ист периметар да се испечати "Isti se".

### Телефонски претплатник
Да се напише програма во која од стандарден влез се чита мобилен број во следниот формат XXYYYZZZ (пр. 71298486). Програмата треба да го испечати во формат XXX/YYY-ZZZ (пр. 071/298-486). Дополнително, треба да го испечати и името на иницијалниот оператор: - 070/071/072 - T-mobile, - 075/076 - One, - 077/078 - Vip.

## Циклуси
### Благ број 
Благ број е број што е составен само од парни цифри (0, 2, 4, 6, 8). Во зададен опсег (почетокот m и крајот на опегот n се цели броеви чија вредност се внесува од тастатура), да се најде и испечати најмалиот „благ број“. Ако не постои таков број, да се испечати NE.

### Парови цели броеви
Да се напише програма во која од стандарден влез прво се внесува еден позитивен цел број z, а потоа последователно се внесуваат парови цели броеви (a, b). Внесувањето на парови цели броеви треба да заврши кога корисникот ќе го внесе парот (0, 0). Треба да се пресмета колку пати z е еднаков на збирот на секој внесен пар броеви a и b, како и колкав процент од вкупниот број внесени парови (a, b) даваат збир z (ЗАБЕЛЕШКА: парот (0, 0) не се зема во предвид при извршувањето на пресметките!).

### Интересен број
Eден природен e „интересен“ ако неговиот обратен број е делив со неговиот број на цифри. Обратен број е бројот составен од истите цифри, но во обратен редослед (на пример, 653 е обратен број на бројот 356). Од тастатура се внесува природен број n ( n > 9). Да се најде и отпечати најголемиот природен број помал од n кој што е „интересен“. Ако внесениот број не е валиден, да се отпечати соодветна порака (Brojot ne e validen).

### Најди го збирот
Од стандарден влез се читаат знаци се додека не се прочита извичник. Во вака внесениот текст се скриени цели броеви (помали од 100). Да се напише програма што ќе ги прочита сите знаци и на излез ќе го испечати збирот на сите броеви скриени во текстот.

##  Еднодимензионални низи 
### Генерирање низа
Да се напише програма која од два дадени реални броеви генерира низа од N (N < 100) реални броеви. Првите елементи на низата се двата дадени броеви, а останатите елементи од низата се добиваат како половина од збирот на сите претходни елементи од низата. Бројот на елементи од низата и двата почетни елементи се читаат од СВ.

### Циклично поместување
Да се напише програма која извршува циклично поместување на елементите на дадена низа А од N (N < 100) цели броеви, за K-места во лево и во десно. Елементите на низата, нивниот број N и бројот на поместувања K се читаат од СВ.

Забелешка: Ако бројот K е позитивен поместувањето се извршува во десно, а ако е негативен во лево.

### Огледални броеви
Од стандарден влез се чита цел број N. Потоа се вчитуваат N низи од цели броеви (со максимална должина од 100 елементи), при што за секоја прво се внесува должината на низата, а потоа сите елементи на низата.

Да се напише програма која за секоја низа ќе ја отпечати сумата на сите еднакви огледални броеви во низата (огледални броеви се првиот и последниот, вториот и предпоследниот, итн…).

пример влез:
```
3
5 7 2 5 2 8
6 1 2 3 3 1 1
8 8 4 8 3 2 1 4 8
```
излез:
```
4   (2 + 2)
8   (1 + 1 + 3 + 3)
24  (8 + 8 + 4 + 4)
```


## Матрици
### Сума на матрица
Сума на матрица претставува сума од сите елементи на матрицата.

Од стандарден влез се чита матрица (која не мора да биде квадратна). Да се најде сумата на матрицата

### Матрица
Од стандарден влез се читаат димензии на квадратна матрица (макс 100х100) која е составена од целобројни елементи. Во продолжение се читаат сите елементи од матрицата соодветно.

Да се состави нова матрица во која секој елемент од главната дијагонала ќе биде заменет со сумата на сите елементи од истиот ред десно од елементот и елементите кои се во истата колона над елементот.

Исто така, потребно е секој елемент од споредната дијагонала да се замени со сумата на елементи од истиот ред пред елементот и елементите кои се во истата колона под елементот.

Доколку нема соодветни елементи, потребно е елементот да се постави на 0. Доколку некој елемент се наоѓа и на главна и на споредна дијагонала, потребно е двете суми да се сумираат. Елементите кои не се наоѓаат на некоја од дијагоналите не треба да се променат.

Пример:

За дадената матрица Аn,n:<br />
![Screenshot (170)](https://user-images.githubusercontent.com/48455819/82321452-22d9bc00-99d5-11ea-9b4c-a5dc0a33784c.png)<br />

### Соседи
Oд стандарден влез се вчитува матрица со димензии M x N. Да се напише програма која во друга матрица со исти димензии, секој елемент ќе го замени со збирот на неговите соседни елементи (по хоризонтала и вертикала) кои се поголеми од самиот тој елемент. Соседни елементи на еден елемент во матрицата се елементите кои се наоѓаат горе, долу, лево и десно од самиот елемент (ако елементот е дел од првата или последната редица или колона му недостасува некој сосед).

Пример:<br />
![Screenshot (172)](https://user-images.githubusercontent.com/48455819/82321657-7946fa80-99d5-11ea-8b9e-6847a81b3a4d.png)<br />
Во примерот соседи на елементот 4 се 3, 2, додека соседи на елементот 9 се 16, 8, 5, 4. Почетна сума за секој елемент е 0.

## Функции
### Квадрат од знаци
Да се направи функција Kvadrat(), која ќе прима еден аргумент - природен број m и на СИ ќе печати ѕвезден квадрат од ред m - квадрат составен од m * m ѕвездички (функцијата НЕ ТРЕБА да враќа вредност!). Од СВ се чита еден природен број n. Користејќи ја функцијата Kvadrat(), на СИ да се испечатат сите ѕвездени квадрати од ред помал или еднаков на n, во растечки редослед (види пример!).

### Поместување во лево
Направете функција која што како аргументи прима два цели броја n и k (k > 0). Функцијата треба да прави циклично поместување на цифрите на бројот n за k позиции во лево. Од СВ прочитајте еден природен број m, а потоа уште m парови од цели броеви (n, k) и повикајте ја функцијата за секој од овие парови од броеви. Испечатете ги на СИ новодобиените броеви, секој во посебен ред.

### Производ цифри
Да се напише рекурзивна функција која ќе го пресметува производот на цифрите на даден повеќецифрен број. Да се најде односот на производот на цифрите и првобитниот број и да се испечати на екранот.

### Двоен факториел 
Да се напише рекурзивна функција која ќе пресметува двоен факториел (n!!).

Двојниот факториел се пресметува по формулата:

n!!=n(n−2)(n−4)...2∗0!, при што 0!=1 (ако n е парен број)

n!!=n(n−2)(n−4)...3∗1!, при што 1!=1 (ако n е непарен број)

## Покажувачи
### Проверка на тежини
Дадени се две низи со ист број на елементи во чии полиња се сместува злато во килограми. Во првата низа максималната количина на злато што може да се смести во секое поле е 500 килограми, додека во втората е неограничено. Напишете функција која ги заменува килограмите од првата и втората низа (елементите на исти позиции) ако во елементот во првата низа има повеќе од 500 кг., а елементот во втората низа помалку од 500 кг. Ако во двата соодветни елементи има повеќе од 500 кг. тогаш златото во елементот од првата низа се уништува (се запишува нула). Задачата да се реши со покажувачи.

Пример:

За низите 100 501 600 и 200 300 700 треба да се испечатат низите 100 300 0 и 200 501 700.

## Низи од знаци (стрингови) 
### Исти знаци во стрингови
Да се напише програма во која од тастатура се читаат две низи од знаци. Потоа да се направи споредба на знаците на соодветни позиции од двете текстуални низи така што ако соодветните знаци се исти, тогаш тие се заменуваат со знакот * во двете низи, а во спротивно, остануваат непроменети. На крај да се испечати вкупниот број на знаци во кој низите се совпаѓаат. Споредбата да се реализира со посебна функција што на влез ги прима двете низи од знаци, а како резултат го враќа бројот на знаци во кој низите се совпаѓаат. Должината на двете низи може да биде различна. Задачата да се реши со помош на покажувачи.

### Сортирање на зборови
Да се напише програма во која од тастатура се читаат десет збора и се сортираат по азбучен редослед. Зборовите не се подолги од 50 знаци.

Пример: Влез: prolog fortran java perl python php javascript c ruby csharp Излез: c csharp fortran java javascript perl php prolog python ruby

### „Средување“ на стринг
Да се напише програма во која од тастатура се чита текстуална низа. Да се промени низата така што ќе се сортира и од неа ќе се отстранат празните места и знаците што се повторуваат. Промената на низа да се реализира со посебна функција. Да не се прави разлика меѓу мали и големи букви.

## Датотеки
### Цифри и букви
Да се напише програма која од датотеката со име "text.txt" ќе го одреди и отпечати на стандарден излез односот на цифри и букви.

Забелешка: Да не се менува функцијата writeToFile(). Таа служи за креирање и пополнување на влезната датотека со податоците дадени на стандардниот влез.

### Позиција на ред
Да се напише програма која од дадена датотека text.txt ќе ја испечати позицијата на редот кој содржи најголем број на големи букви. Максималната должина на еден ред е 80 знаци. Доколку има повеќе редови со ист максимален број на големи букви, треба да се испечати позицијата на првиот од нив.

Забелешка: Да не се менува функцијата writeToFile(). Таа служи за креирање и пополнување на влезната датотека со податоците дадени на стандардниот влез.
