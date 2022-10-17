# Blackjack
This deck describes optimal strategy for a popular game with 4-8 decks where dealer hits on soft 17.

Strategy was calculated with:
* https://wizardofodds.com/games/blackjack/strategy/calculator/

### Legend
* 🥊 - Hit
* ✋ - Stand
* 💵 - Double
* 👯 - Split
* 🐔 - Surrender

### Hard
A hard total is any hand that does not start with an ace in it, or it has been dealt an ace that can only be counted as 1 instead of 11.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
| 8|🥊|🥊|🥊|🥊|🥊|🥊|🥊|🥊|🥊|🥊|
| 9|🥊|💵|💵|💵|💵|🥊|🥊|🥊|🥊|🥊|
|10|💵|💵|💵|💵|💵|💵|💵|💵|🥊|🥊|
|11|💵|💵|💵|💵|💵|💵|💵|💵|💵|💵|
|12|🥊|🥊|✋|✋|✋|🥊|🥊|🥊|🥊|🥊|
|13|✋|✋|✋|✋|✋|🥊|🥊|🥊|🥊|🥊|
|14|✋|✋|✋|✋|✋|🥊|🥊|🥊|🥊|🥊|
|15|✋|✋|✋|✋|✋|🥊|🥊|🥊|🐔|🐔|
|16|✋|✋|✋|✋|✋|🥊|🥊|🐔|🐔|🐔|
|17|✋|✋|✋|✋|✋|✋|✋|✋|✋|🐔|
|18|✋|✋|✋|✋|✋|✋|✋|✋|✋|✋|
|19|✋|✋|✋|✋|✋|✋|✋|✋|✋|✋|
|20|✋|✋|✋|✋|✋|✋|✋|✋|✋|✋|


### Soft
A soft total is any hand that has an Ace as one of the first two cards, the ace counts as 11 to start.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|13 (A)|🥊|🥊|🥊|💵|💵|🥊|🥊|🥊|🥊|🥊|
|14 (A)|🥊|🥊|🥊|💵|💵|🥊|🥊|🥊|🥊|🥊|
|15 (A)|🥊|🥊|💵|💵|💵|🥊|🥊|🥊|🥊|🥊|
|16 (A)|🥊|🥊|💵|💵|💵|🥊|🥊|🥊|🥊|🥊|
|17 (A)|🥊|💵|💵|💵|💵|🥊|🥊|🥊|🥊|🥊|
|18 (A)|💵|💵|💵|💵|💵|✋|✋|🥊|🥊|🥊|
|19 (A)|✋|✋|✋|✋|💵|✋|✋|✋|✋|✋|
|20 (A)|✋|✋|✋|✋|✋|✋|✋|✋|✋|✋|

### Pairs
||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|2,2|👯|👯|👯|👯|👯|👯|🥊|🥊|🥊|🥊|
|3,3|👯|👯|👯|👯|👯|👯|🥊|🥊|🥊|🥊|
|4,4|🥊|🥊|🥊|👯|👯|🥊|🥊|🥊|🥊|🥊|
|5,5|💵|💵|💵|💵|💵|💵|💵|💵|🥊|🥊|
|6,6|👯|👯|👯|👯|👯|🥊|🥊|🥊|🥊|🥊|
|7,7|👯|👯|👯|👯|👯|👯|🥊|🥊|🥊|🥊|
|8,8|👯|👯|👯|👯|👯|👯|👯|👯|👯|👯|
|9,9|👯|👯|👯|👯|👯|✋|👯|👯|✋|✋|
|10,10|✋|✋|✋|✋|✋|✋|✋|✋|✋|✋|
|A,A|👯|👯|👯|👯|👯|👯|👯|👯|👯|👯|

### Deck
________________________________________________________________________________
A,A

?

Always split aces.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|A,A|👯|👯|👯|👯|👯|👯|👯|👯|👯|👯|
________________________________________________________________________________
10,10

?

Never split tens.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|10,10|✋|✋|✋|✋|✋|✋|✋|✋|✋|✋|
________________________________________________________________________________
9,9

? 

Split against dealer 2 through 9, except for 7, otherwise stand.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|9,9|👯|👯|👯|👯|👯|✋|👯|👯|✋|✋|
________________________________________________________________________________
8,8

?

Always split 8's

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|8,8|👯|👯|👯|👯|👯|👯|👯|👯|👯|👯|
________________________________________________________________________________
7,7

?

Split against dealer 2 through 7, otherwise hit.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|7,7|👯|👯|👯|👯|👯|👯|🥊|🥊|🥊|🥊|
________________________________________________________________________________
6,6

? 

Split against dealer 2 through 6, otherwise hit.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|6,6|👯|👯|👯|👯|👯|🥊|🥊|🥊|🥊|🥊|
________________________________________________________________________________
5,5

?

Double against dealer 2 through 9 otherwise hit.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|5,5|💵|💵|💵|💵|💵|💵|💵|💵|🥊|🥊|
________________________________________________________________________________
4,4

?

Split against dealer 5 and 6 , otherwise hit.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|4,4|🥊|🥊|🥊|👯|👯|🥊|🥊|🥊|🥊|🥊|
________________________________________________________________________________
3,3

?

Split against dealer 2 through 7, otherwise hit.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|3,3|👯|👯|👯|👯|👯|👯|🥊|🥊|🥊|🥊|
________________________________________________________________________________
2,2

?

Split against dealer 2 through 7, otherwise hit.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|2,2|👯|👯|👯|👯|👯|👯|🥊|🥊|🥊|🥊|
________________________________________________________________________________
20 (A)

?

Always stands

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|20 (A)|✋|✋|✋|✋|✋|✋|✋|✋|✋|✋|
________________________________________________________________________________
19 (A)

?

Double against dealer 6, otherwise stand.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|19 (A)|✋|✋|✋|✋|💵|✋|✋|✋|✋|✋|
________________________________________________________________________________
18 (A)

?

Double against dealer 2 through 6, and hits against 9 through A, otherwise stand.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|18 (A)|💵|💵|💵|💵|💵|✋|✋|🥊|🥊|🥊|
________________________________________________________________________________
17 (A)

?

Double against dealer 3 through 6, otherwise hit.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|17 (A)|🥊|💵|💵|💵|💵|🥊|🥊|🥊|🥊|🥊|
________________________________________________________________________________
16 (A)

?

Double against dealer 4 through 6, otherwise hit.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|16 (A)|🥊|🥊|💵|💵|💵|🥊|🥊|🥊|🥊|🥊|
________________________________________________________________________________
15 (A)

?

Double against dealer 4 through 6, otherwise hit.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|15 (A)|🥊|🥊|💵|💵|💵|🥊|🥊|🥊|🥊|🥊|
________________________________________________________________________________
14 (A)

?

Double against dealer 5 through 6, otherwise hit.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|14 (A)|🥊|🥊|🥊|💵|💵|🥊|🥊|🥊|🥊|🥊|
________________________________________________________________________________
13 (A)

?

Double against dealer 5 through 6, otherwise hit.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|13 (A)|🥊|🥊|🥊|💵|💵|🥊|🥊|🥊|🥊|🥊|
________________________________________________________________________________
20

?

Always stand on 20.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|20|✋|✋|✋|✋|✋|✋|✋|✋|✋|✋|
________________________________________________________________________________
19

?

Always stand on 19.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|19|✋|✋|✋|✋|✋|✋|✋|✋|✋|✋|
________________________________________________________________________________
18

?

Always stand on 18.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|18|✋|✋|✋|✋|✋|✋|✋|✋|✋|✋|
________________________________________________________________________________
17

?

Always stand on 17.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|17|✋|✋|✋|✋|✋|✋|✋|✋|✋|🐔|

________________________________________________________________________________
16

?

Stand against dealer 2 through 6, surrender against 9 through A, otherwise hit.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|16|✋|✋|✋|✋|✋|🥊|🥊|🐔|🐔|🐔|
________________________________________________________________________________
15

?

Stand against dealer 2 through 6, surrender at 10 and A, otherwise hit.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|15|✋|✋|✋|✋|✋|🥊|🥊|🥊|🐔|🐔|
________________________________________________________________________________
14

?

Stand against dealer 2 through 6, otherwise hit.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|14|✋|✋|✋|✋|✋|🥊|🥊|🥊|🥊|🥊|
________________________________________________________________________________
13

?

Stand against dealer 2 through 6, otherwise hit.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|13|✋|✋|✋|✋|✋|🥊|🥊|🥊|🥊|🥊|
________________________________________________________________________________
12

?

Stand against dealer 4 through 6, otherwise hit.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|12|🥊|🥊|✋|✋|✋|🥊|🥊|🥊|🥊|🥊|
________________________________________________________________________________
11

?

Always double.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|11|💵|💵|💵|💵|💵|💵|💵|💵|💵|💵|
________________________________________________________________________________
10

?

Double against dealer 2 through 9 otherwise hit.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
|10|💵|💵|💵|💵|💵|💵|💵|💵|🥊|🥊|
________________________________________________________________________________
9

?

Double against dealer 3 through 6 otherwise hit.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
| 9|🥊|💵|💵|💵|💵|🥊|🥊|🥊|🥊|🥊|
________________________________________________________________________________
8

?

Always hit on 8.

||2|3|4|5|6|7|8|9|10|A|
|-|-|-|-|-|-|-|-|-|-|-|
| 8|🥊|🥊|🥊|🥊|🥊|🥊|🥊|🥊|🥊|🥊|