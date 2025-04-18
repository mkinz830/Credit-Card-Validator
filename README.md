# 💳 Credit Card Validator (Luhn Algorithm)

This Python script validates a credit card number using the **Luhn algorithm**, a common checksum formula used to verify identification numbers such as credit card numbers.

---

## 🚀 How It Works

The program performs the following steps:

1. **Input Handling**  
   Accepts a credit card number from the user (spaces and dashes are removed for flexibility).

2. **Reverse the Number**  
   The number is reversed to align with the Luhn algorithm's processing order.

3. **Sum Odd-Indexed Digits**  
   Every other digit (starting from the first digit in the reversed string) is added directly.

4. **Process Even-Indexed Digits**  
   Every other digit (starting from the second digit in the reversed string) is doubled:
   - If the result is two digits (i.e., 10 or greater), those digits are added together.
   - The sum is added to the running total.

5. **Validate**  
   If the final total is divisible by 10, the credit card number is **valid**; otherwise, it’s **invalid**.

---

## 🧪 Example

Input: 4539 1488 0343 6467
Output: Valid



---

## 🧠 Why This Matters

The Luhn algorithm is used by:
- Credit card companies (Visa, MasterCard, etc.)
- IMEI numbers for mobile devices
- Government ID systems

This project is a great hands-on demonstration of real-world algorithm implementation.

---

## 📂 How to Use

1. Copy the script into a `.py` file.
2. Run it in a Python environment.
3. Enter a credit card number when prompted.

```bash
