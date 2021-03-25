# swift-from-scratch-
learning pr language SWIFT from scratch. also attach code and study history. #tvm

import UIKit

var str = "Hello, playground"

let y = 10

var x = y + 10

for i in 1.. <10 {
    print("i равен \(i)")
}
let label

var str = "Hello World"
let str1 = "Hey Steve"

 Character, String, Int, Double Float, Bool

let x: Character = "q"
let y: String = "Russian"
let z: Double = 1.5342  // 15 знаков после запятой
let w: Float = 1.64396434643  // 6 знаков после запятой
let d: Int = 123
let v: Bool = true // false логическое значение

let r = false
let f = Int(123.123)
let a = Float(224.32434123)

var simpleString = "What do we say to the god of death?"
simpleString = "Not today"


// оператор присваивания =
let a = "Hello"

// артифметический оператор
let b = 1 + 33
let c = 12/2
let l = 12*323

//оператор остатка %
let f = 100 % 3

// составные операторы += -= /= *=
let h = 23
var u = 30
//var k = h + u
//or
u += h

 Scratch Swift / Константы и переменные

let greetings = "Hello World"
greetings = "Hello Swifter"

direction

var direction = "Left"
var helloHowAreYouImfineTh = "Fine"
//var xx2 = 10
direction = "Right"

print(greetings)
//var direction = "Left"

/*
 многострочный комментарий
 */

// Типы данных

var number: Int = 10

var a = 35
var b = -45


// ----- / Число с плавающей точкой

var x = 5.44
var m = -300.456

var sum2 = Int(x) + Int(m)
var float: Double = 1.45 // 15 знаков после точки

// String /Строка

var greetings = "Hello World"

var t = "Hello"
var y = "Swifter"
var sum = t + y
//интстапаляция строк

print("Hello \(y)")

var iareYouHappy = true //false
if iareYouHappy {
    print("Good")
}
else{
    print("Bad")
}

 Базовые операторы

 Унарные: -a, !b, постфиксные c!
 Бинарные: 1 + 2  - инфексные
 Тернарные: a ? b : c

 Оператор присваивания =
let a = 12

var b = 5
b = a

 Арфиметические опреаторы +, -, *, /, %

let x = 134
let o = 7

x + o
x - o
x * o
x / o


let i = "Hello"
let p = "Swift"
 var y = i + p
 i + p

x % o
 134/ (133/7) + 1

Составные операторы присваивания +=, -+

var c = 1
c += 2
c -= 1

var count = 0
count += 1

Операторы сравнения ==, !=, >, <, >=, <=

let t = 14
let z = 16
t == z
t != z
t > z
t < z
t >= z
t <= z

let name = "World"
if name != "world" {
    print("Hello World")
} else {
    print("Something went wrong")
}

 Тернарный условный оператор
 выражение ? действие 1 : действие 2


/*
 if выражение {
    действие 1
 
 } else {
 действие 2
 
 }
 */

let firstProject = 11
let secondProject = 10

if firstProject != secondProject {
    print("Projects are the same")
} else {
    print("Projects are different")
}

 or

firstProject != secondProject ? print("Projects are the same TVM") :
    print("Projects are different TVM")


 Операторы замкнутого / закрытого диапозона(a..b), полуоткрытого или полузакрытого диапозона(a..<b)

 Логические операторы !a, &&, ||

let areYouHappy = true
if !areYouHappy {
    print("Good for you")
} else {
    print("What can i do for you?")
}

let isTheWeatherGood = false
if areYouHappy && isTheWeatherGood {
    print("Go outside")

} else {
    print("Stay home")
}

let isItAwesome = false
if isItAwesome || isTheWeatherGood  {
    print("Come on on the walk")
} else {
    ("Plz stay home and read books")
}


 Условия

let firstCard  = 12
let secondCard = 20

if firstCard + secondCard == 35 {
    print("You are winner")
} else if (firstCard + secondCard) > 10 && (firstCard + secondCard) < 35 {
    print("Awesome Cards")
} else {
    print("Regular Cards")
}


let age1 = 90
let age2 = 21

if age1 > 18 && age2 > 18 {
    print("Bot are over 18")
}

if age1 > 18 || age2 > 18 {
    print("At least one over 18c")
}

/*
 switch значение для сопоставления {
 case значение 1:
 инструкция для значения 1
 case значение 2:
 инструкция для значения 2
 case значение 3:
 инструкция для значения 3
 default:
 инструкция, если совпадений с шаблонами не имеется
 }
 */
 

let weather = "sunny"
switch weather {
case "rain":
    print ("Bring an umbrella")
case "snow":
    print("dress warmly")
case "sunny":
    print("breathe deeply and enjoy the weather")
    fallthrough
default:
    print("Enjoy your day")
}

switch age1 {
case 0...10:
    print("You are too young")
case 13..<20:
    print("You are teenager")
case 20...60:
    print("You are grown man")
case 80...:
    print("You are old man")
default:
    print("Don't worry about that")
    print("How old are you")
}


 Циклы

 for in / while / repeat-while

let count = 1...10

for number in count {
    print("Number is \(number)")
}

for _ in 1...5 {
    print("Hello")
}

for index in 0...9 {
    print("\(index) умножить на 3 равно \(index * 3)")
}


/*
 while условие {
 инструкция
 }
 */

var number = 1
while number <= 20 {
    print(number)/
    number += 1
}
print("Start!")


/*
 
 repat {
 
 инструкция
 
 } while условие
 
 /*
 
 
