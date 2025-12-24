# Java User Input Demo

This project is a simple Java application designed to demonstrate how to capture and display different types of user data using the `Scanner` class.

---

## 🛠️ Concepts Covered

### Method Signatures & I/O
* **`public static void`**: The keyword `void` indicates that the method performs an action but **does not return** a value.
* **`Scanner`**: A utility class from `java.util` used to read input from the console (`System.in`).
* **`System.out.print()`**: Used to show output on the **same line**, which is perfect for user prompts.
* **`System.out.println()`**: Shows output and moves the cursor to the **next line**.
* **`scan.close()`**: Closes the scanner to clear the "buffer" (temporary storage) and release system resources.

### Input Methods Used
* **`nextLine()`**: Captures a full line of text (**String**).
* **`nextInt()`**: Captures whole numbers (**int**).
* **`nextDouble()`**: Captures decimal numbers (**double**).
* **`nextBoolean()`**: Captures **true** or **false** values.

---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/your-repo-name.git](https://github.com/yourusername/your-repo-name.git)```

2. **Compile the code:**

Bash

javac Main.java

3. **Run as an Application:**

Bash

java Main


## 📝 Example Output

Enter your username: Alex

Enter your age: 20

Enter your gpa: 3.8

Are you a student? (true/false): true


Output:

Hello Alex

You are 20 years old

Your gpa is 3.8

true

You are enrolled as a Student!
