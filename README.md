# Homework-HW1-CH1-

#Simple1
```go
fun main() {
    print("歡迎使用Java!")
    print("開始使用Java吧!")
}
```
#Simple2
```go
fun main() {
    print("歡迎使用Java!")
    print("開始使用Java吧!")
}
```
#Simple3
```go
fun main() {
    println('A')
    println("歡迎使用Java!")
    println(123)
}
```
#Simple4
```go
fun main() {
    println("顯示出反斜線:\\")
    println("顯示出單引號:'")
}
```
#Simple5
```go
fun main() {
    println("八進位數101的字元是" + 101.toString(8).toInt(8).toChar())
    println("十六進位數0061的字元是" + '\u0061')
}
```
#Simple7
```go
fun main() {
    var num = 3

    println("變數num的值是$num")
}
```
#Simple8
```go
fun main() {
    var num = 3

    println("變數num的值是$num")

    num = 5

    println("更新變數num的值")
    println("變數num更新後的值是$num")
}
```
#Simple9
```go
fun main() {
    val num1 = 3

    println("變數num1的值是:$num1")

    val num2 = num1

    println("將變數num1指定到變數num2之中")
    println("變數num2的值是:$num2")
}
```
#Simple10
```go
fun main() {
    println("請輸入一個整數")

    val num = readLine()!!.toInt()

    println("您輸入的數字是:$num")

    println("請輸入字串")

    val str = readLine()!!

    println("剛剛輸入的字串是:$str")
}
```
#Simple11
```go
fun main() {
    println("1+2等於" + (1 + 2))
    println("3*4等於" + (3 * 4))

    var num1 = 2
    val num2 = 3
    val sum = num1 + num2

    println("變數num1的值是$num1")
    println("變數num2的值是$num2")
    println("num1+num2的值是$sum")

    num1 = num1 + 1

    println("變數num1的值加1之後是$num1")
}
```
#Simple12
```go
fun main() {
    val num1 = 10
    val num2 = 5

    println("num1和num2的各種運算:")
    println("num1+num2等於" + (num1 + num2))
    println("num1-num2等於" + (num1 - num2))
    println("num1*num2等於" + (num1 * num2))
    println("num1/num2等於" + (num1 / num2))
    println("num1%num2等於" + (num1 % num2))

    var a = 0
    var b = 0
    var c = 0

    b = a++
    c = ++a

    println("因為是在指定值之後才遞增，所以b的值為$b")
    println("因為是在遞增之後才指定值，所以c的值為$c")
}
```
#Simple13
```go
fun main() {
    val dnum = 160.5

    println("身高是${dnum}公分")

    println("指定給int型態的變數")

    val inum = dnum.toInt()

    println("身高是${inum}公分")
}
```
#Simple14
```go
fun main() {
    val d = 2
    val pi = 3.14

    println("直徑是$d公分的圓")
    println("其圓周為${d * pi}公分")

    val num1 = 5
    val num2 = 4

    val div1 = num1 / num2
    val div2 = num1.toDouble() / num2.toDouble()

    println("5/4等於$div1")
    println("5/4等於$div2")
}
```