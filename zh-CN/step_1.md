JavaScript 中的比较运算符用于比较两个值并返回布尔结果（`true` 或 `false`）。 以下是一些常用的比较运算符：

### 等于 (==)

检查两个值是否相等，如果不同，则将数据类型转换为相同。

## --- code ---

language: js
filename: script.js
line_numbers: true
-------------------------------------------------------

```
var num1 = 5;
var num2 = "5";
console.log(num1 == num2); // 输出: true
```

\--- /code ---

- 在这个例子中，num1 和 num2 被认为是相等的，因为数据类型转换后的值是相同的。

### 严格相等（===）

检查两个值是否相等，而不将它们转换为相同的数据类型。 它还检查数据类型是否相同。

## --- code ---

language: js
filename: script.js
line_numbers: true
-------------------------------------------------------

```
var num1 = 5;
var num2 = "5";
console.log(num1 === num2); // 输出: false
```

\--- /code ---

- 在这个例子中，num1 和 num2 并不严格相等，因为它们的数据类型不同

### 不等于 (!=)

检查两个值是否不相等，如果不同则将它们转换为相同的数据类型。

## --- code ---

language: js
filename: script.js
line_numbers: true
-------------------------------------------------------

```
var num1 = 5;
var num2 = "5";
console.log(num1 != num2); // 输出：false
```

\--- /code ---

- 在这个例子中，数据类型转换后，num1和num2相等。 它将返回 false。

### 严格不等于（!==）

检查两个值是否不相等，而不将它们转换为相同的数据类型。 它还检查数据类型是否不同。

## --- code ---

language: js
filename: script.js
line_numbers: true
-------------------------------------------------------

```
var num1 = 5;
var num2 = "5";
console.log(num1 !== num2); // 输出：true
```

\--- /code ---

- 在这个例子中，num1 和 num2 具有不同的数据类型。 因此它将返回 true。

### 大于 (>)

检查左边的值是否大于右边的值。

## --- code ---

language: js
filename: script.js
line_numbers: true
-------------------------------------------------------

```
var num1 = 10;
var num2 = 5;
console.log(num1 > num2); // 输出：true
```

\--- /code ---

- 在这个例子中，num1 大于 num2，所以它将返回 true。

### 小于 (<)

检查左侧的值是否小于右侧的值。

## --- code ---

language: js
filename: script.js
line_numbers: true
-------------------------------------------------------

```
var num1 = 10;
var num2 = 15;
console.log(num1 < num2); // 输出：true
```

\--- /code ---

- 在这个例子中，num1 小于 num2，所以它将返回 true。