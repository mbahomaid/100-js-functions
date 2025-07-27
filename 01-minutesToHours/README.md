Here’s a simple and clear `README.md` for the `minutesToHours` problem:

---

# 📘 minutesToHours

## 🧩 Problem Description

The `minutesToHours` function is designed to convert a time duration given in **minutes** into its equivalent in **hours**.

## ✅ Function Signature

```javascript
function minutesToHours(minutes: number): number
```

## 🔧 Parameters

- `minutes` (`number`): A number representing a duration of time in **minutes**.

## 🎯 Returns

- `number`: The equivalent time in **hours**. This may be a fractional number.

## 💡 Example

### Example 1

**Input:**

```js
minutesToHours(150);
```

**Output:**

```js
2.5;
```

**Explanation:**
150 minutes equals 2.5 hours because 150 ÷ 60 = 2.5.

## 🚀 Goal

The goal of this problem is to understand basic unit conversions using simple arithmetic and to return accurate floating-point results.

## 🛠️ Implementation Tip

To convert minutes to hours, divide the input by `60`, since there are 60 minutes in an hour.
