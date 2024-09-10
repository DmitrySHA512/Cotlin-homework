Tutorial Kotlin
----------------
Типы данных:

Целочисленные типы:
Byte: хранит целое число от -128 до 127 и занимает 1 байт.
UByte: хранит целое число от 0 до 255 и занимает 1 байт.

fun main(){
 
    val a: Byte = -10
    println(a) // -10
}

fun main(){

    val a: UByte = 10U
    println(a) // 10
}

Short: хранит целое число от -32 768 до 32 767 и занимает 2 байта.
UShort: хранит целое число от 0 до 65 535 и занимает 2 байта.

fun main(){

    val b: Short = 45
    println(b) // 45
}

fun main(){
 
    val b: UShort = 45U
    println(b) // 45
}

Int: хранит целое число от -2 147 483 648 (-2^31) до 2 147 483 647 (2^31 - 1) и занимает 4 байта.
UInt: хранит целое число от 0 до 2^32 - 1 и занимает 4 байта.

fun main(){
 
    val c: Int = -250
    println(c) // -250
}

fun main(){
 
    val c: UInt = 250U
    println(c) // 250
}

Long: хранит целое число от –9 223 372 036 854 775 808 (-2^63) до 9 223 372 036 854 775 807 (2^63 - 1) и занимает 8 байт.
ULong: хранит целое число от 0 до 2^64 - 1 и занимает 8 байт.

fun main(){
 
    val d: Long = 30000
    println(d) // 30000
}

fun main(){
 
    val d: ULong = 30000U
    println(d) // 30000
}

Float: хранит число с плавающей точкой от -3.4*10^38 до 3.4*10^38 и занимает 4 байта.

fun mian(){

val pi: Float = 3.14F

println(pi)         // 3.14

}

Double: хранит число с плавающей точкой от ±5.0*10^-324 до ±1.7*10^308 и занимает 8 байта.

fun main() {

val height: Double = 1.78

println(height)      // 1.78

}

Тип Double поддерживает экспоненциальную запись:

fun main() {

val d: Double = 23e3
println(d)      // 23 000

val g: Double = 23e-3
println(g)      // 0.023
}

