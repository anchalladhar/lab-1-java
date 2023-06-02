import java.util.Scanner

fun main() {
    val scanner = Scanner(System.`in`)
    
    // Collect numeric value from the user
    print("Enter the numeric value: ")
    val value = scanner.nextDouble()
    
    // Collect current unit of measurement
    print("Enter the current unit of measurement: ")
    val currentUnit = scanner.next()
    
    // Determine the appropriate conversion and display the result
    val result = when (currentUnit) {
        "km" -> value * 0.62 // km to mi
        "mi" -> value * 1.61 // mi to km
        "cm" -> value * 0.39 // cm to in
        "in" -> value * 2.54 // in to cm
        "kg" -> value * 2.2  // kg to lb
        "lb" -> value * 0.45 // lb to kg
        "g" -> value * 0.04  // g to oz
        "oz" -> value * 28.35 // oz to g
        "C" -> (value * (9/5)) + 32 // Celsius to Fahrenheit
        "F" -> ((value - 32) * (5/9)) // Fahrenheit to Celsius
        "L" -> value * 4.17 // L to cups
        "cup" -> value * 0.24 // cups to L
        else -> {
            println("Invalid unit of measurement.")
            return
        }
    }
    
    println("Result: $result")
}
