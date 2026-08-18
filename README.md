# 🧮 Math Class Examples

This repository demonstrates several methods from Java's built-in `Math` class, including absolute value, square root, power, max, random number generation, and rounding.

---

## 🟡 MathExamples.java

**Description**
This program demonstrates common `Math` class methods: `abs`, `sqrt`, `pow`, `max`, `random`, and `ceil`. It also includes a note on how to convert degrees to radians for trig functions. There are no user inputs; each method is called with hardcoded values to show its behavior. The outputs are the results of each `Math` method printed to the console.

**Tech Stack**
- Language: Java
- Tool/Library: Eclipse

<details>
<summary>💻 Show code</summary>

```java
package exam1problems;

public class MathExamples {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		System.out.println("Absolute: "      + Math.abs(-10)); //finding the absolute value of an int

        System.out.println("Square Root: "   + Math.sqrt(25)); //finding the square root of an int

        System.out.println("Power: "         + Math.pow(3, 4)); //this is three to the power of 4

        System.out.println("Max: "           + Math.max(8, 15)); //set a max

        System.out.println("Random (0-1): "  + Math.random()); //generate a random number

        System.out.println("Ceil: " + Math.ceil(2.5)); //rounds up, FLOOR ROUNDS DOWN

        //Remember for trig it is like these formats and that numbers must be in radians

        //IN ORDER TO GET RADIAN DO THIS EQUATION
        //radians = degrees * (Math.PI / 180)
	}

}
```

</details>

**Usage**
Example output (the random value will differ each run):

<details>
<summary>💻 Show expected output</summary>

```java
Absolute: 10
Square Root: 5.0
Power: 81.0
Max: 15
Random (0-1): 0.7284915638271026
Ceil: 3.0
```

</details>

---

## 📚 What I Learned

The `Math` class and its built-in methods (`abs`, `sqrt`, `pow`, `max`, `random`, `ceil`), and how to convert degrees to radians for trig calculations.


