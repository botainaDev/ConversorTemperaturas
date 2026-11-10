# 🌡️ Conversor de Temperaturas

A simple application to convert temperatures between **Celsius (°C)**, **Fahrenheit (°F)** and **Kelvin (K)**.

## 📋 Features

- Convert between Celsius, Fahrenheit and Kelvin
- Input validation (numbers only, no values below absolute zero)
- Simple text menu
- Results rounded to 2 decimals

## 🧮 Formulas Used

| Conversion            | Formula              |
|-----------------------|----------------------|
| Celsius → Fahrenheit  | `F = C × 9/5 + 32`   |
| Fahrenheit → Celsius  | `C = (F − 32) × 5/9` |
| Celsius → Kelvin      | `K = C + 273.15`     |
| Kelvin → Celsius      | `C = K − 273.15`     |
| Fahrenheit → Kelvin   | `K = (F − 32) × 5/9 + 273.15` |
| Kelvin → Fahrenheit   | `F = (K − 273.15) × 9/5 + 32` |

## 🛠️ Requirements

- Java JDK 17 or higher
- (Optional) An IDE such as Eclipse or IntelliJ IDEA

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/conversor-temperaturas.git
   cd conversor-temperaturas
   ```
2. Compile:
   ```bash
   javac src/ConversorTemperaturas.java
   ```
3. Run:
   ```bash
   java -cp src ConversorTemperaturas
   ```

## 💻 Example Usage

```
=== CONVERSOR DE TEMPERATURAS ===
1. Celsius a Fahrenheit
2. Fahrenheit a Celsius
3. Celsius a Kelvin
4. Kelvin a Celsius
5. Salir

Elige una opción: 1
Introduce la temperatura en °C: 25
Resultado: 25.00 °C = 77.00 °F
```



## 🧪 Test Cases

| Input   | Conversion | Expected Output |
|---------|------------|-----------------|
| 0 °C    | → °F       | 32.00 °F        |
| 100 °C  | → °F       | 212.00 °F       |
| 32 °F   | → °C       | 0.00 °C         |
| 0 °C    | → K        | 273.15 K        |
| −300 °C | → K        | Error: below absolute zero |

## 🔮 Future Improvements

- Graphical interface (Swing / JavaFX)
- Conversion history
- Support for Rankine and Réaumur scales

## 👤 Author

**Your Name**  
[GitHub](https://github.com/your-username)

