# Diego Orellana - CoreCode Bootcamp 🚀
## Week 2
### Monday Challenges
- [Logic Problems](https://github.com/DiegoMGE/core-code-from-scratch-readme-week-2/edit/main/README.md#logic-problem)
- [Cereal vs Milk](https://github.com/DiegoMGE/core-code-from-scratch-readme-week-2/edit/main/README.md#cereal-vs-milk)

## Logic Problem 😵‍💫🧠
If Alice is telling the truth, nobody studied including her, if not, she studied, but doesn't make sense what she said, is illogical.

If Bob is telling the truth, only one person studied and might be him, if not, he doesn't studied and doesn't know if someone did it or not.

If Charlie is telling the truth, only two people studied, but if he's lying, Dan and Eva are lying too, since there are different numbers in "one person" or "3 people", because at least two people are telling the truth and can't be true at the same time two answer with different numbers like those.

So, probably only Bob is telling the truth!

## Cereal vs Milk 🌽🥛
```
Start;
Check if there is cereal, liquid milk and sugar;
    if not;
        buy;
Add liquid milk in a glass;
Add 1 spoon with sugar to the milk glass;
Mix milk and sugar in glass and save it into a variable named mixed;
Place a bowl in table;
Add cereal to bowl;
Add mixed to bowl;
Enjoy with a movie;
End;
```
![flowchart](https://i.imgur.com/2W8BmcU.png)

### Tuesday Challenges
- [Print my name](https://github.com/DiegoMGE/core-code-from-scratch-readme-week-2/blob/main/README.md#print-my-name)
- [Print my name and age](https://github.com/DiegoMGE/core-code-from-scratch-readme-week-2/blob/main/README.md#print-my-name--age)
## Print my name
```
Algoritmo myName
	name <- 'Diego Orellana'
	Imprimir name
FinAlgoritmo
```

## Print my name & age
```
Algoritmo myNameAndAge
	name <- 'Diego Orellana'
	age <- 27
	Imprimir 'Mi nombre es ' name ' y tengo ' age ' años!'
FinAlgoritmo
```

### Wednesday Challenges
- [Algorithm Game](https://github.com/DiegoMGE/core-code-from-scratch-readme-week-2/blob/main/README.md#algorithm-game)
- [Mod](https://github.com/DiegoMGE/core-code-from-scratch-readme-week-2/blob/main/README.md#mod)
- [Register form](https://github.com/DiegoMGE/core-code-from-scratch-readme-week-2/blob/main/README.md#register-form)

## Algorithm Game
![image](https://user-images.githubusercontent.com/88050715/204935143-177bda70-3259-4f64-8c3b-0ec4a2011f76.png)

## Mod
```
Algoritmo evenOdd
	mod <- 2
	Leer userNum
	result <- userNum % mod
	Imprimir result
FinAlgoritmo
```

## Register Form
```
Algoritmo userForm
	Imprimir '======= USER DATA ======='
	Imprimir 'First name '
	Leer Firstname
	Imprimir 'Last name '
	Leer lastName
	Imprimir 'Age '
	Leer age 
	Imprimir 'Email '
	Leer email
	Imprimir 'Address '
	Leer address
	Imprimir '======= USER DATA ======='
	Imprimir 'Full Name: ' Firstname ' ' lastName
	Imprimir 'Age: ' age
	Imprimir 'email: ' email
	Imprimir 'Address: ' address
	Imprimir '========================='
FinAlgoritmo
```
### Thursday Challenges
- [Truth tables](https://github.com/DiegoMGE/core-code-from-scratch-readme-week-2/blob/main/README.md#truth-tables)
- [Boolean results](https://github.com/DiegoMGE/core-code-from-scratch-readme-week-2/blob/main/README.md#boolean-results)
- [Identify odd and even numbers](https://github.com/DiegoMGE/core-code-from-scratch-readme-week-2/blob/main/README.md#identify-odd-and-even-numbers)

## Truth tables
1. T & T = T ✅
2. T & F = F ✅
3. F & T = T ❌
4. F & F = F ❌ 
5. T | T = T ✅
6. T | F = F ✅
7. F | T = T ✅
8. F | F = F ✅
9. ~T = T ❌
10. ~F = T ✅
11. (T & F) | (~F) = T ✅
12. (T | F ) & (F | F) = T ❌
13. ~((T | F ) & (F | F)) & F = T ❌
14. ~((T | F ) & (F | F)) & T = F ❌


## Boolean results
```
Algoritmo boolean
	a <- 5 == 3
	// 5 is equal to 3
	b <- 4 <> 3
	// 4 is different from 3
	c <- 7 > 7
	// 7 is greater than 7
	d <- 4 < 4
	// 4 is less than 4
	e <- 100 <= 90
	// 100 is less or equal to 90
	f <- 40 >= 40
	// 40 is greater or equal than 40
FinAlgoritmo
```

## Identify odd and even numbers


.
