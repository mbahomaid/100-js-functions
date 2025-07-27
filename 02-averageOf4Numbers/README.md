# 📘 averageOf4Numbers

## 🧩 Problem Description

The `averageOf4Numbers` function is designed to compute the **mathematical average** of four given numbers.

## ✅ Function Signature

```javascript
function averageOf4Numbers(nr1: number, nr2: number, nr3: number, nr4: number): number
```

## 🔧 Parameters

* `nr1` (`number`): The first number.
* `nr2` (`number`): The second number.
* `nr3` (`number`): The third number.
* `nr4` (`number`): The fourth number.

## 🎯 Returns

* `number`: The **average** of the four numbers. This may be a fractional number.

## 💡 Example

### Example 1

**Input:**

```js
averageOf4Numbers(11, 9, 33, 28);
```

**Output:**

```js
20.25;
```

**Explanation:**
The sum of the numbers is `11 + 9 + 33 + 28 = 81`.
The average is `81 ÷ 4 = 20.25`.

## 🚀 Goal

The goal of this problem is to reinforce basic arithmetic operations and working with multiple function parameters.

## 🛠️ Implementation Tip

To find the average, sum all four numbers and divide the total by `4`.
