<h1>
  <span class="headline">Python Conditionals</span>
  <span class="subhead">Comparison Operators</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to tktk

| Lesson               | Duration |
| -------------------- | -------- |
| Comparison Operators | 25 min   |

## Comparison Operators

First, we’ll need **_comparison operators_** — a set of operators that give you the ability to compare values and return a Boolean result (true or false).

| **Comparison Operator** | **Meaning**              |
| ----------------------- | ------------------------ |
| `>`                     | Greater than             |
| `>=`                    | Greater than or equal to |
| `<`                     | Less than                |
| `<=`                    | Less than or equal to    |
| `==`                    | Equality                 |
| `!=`                    | Inequality               |

> 🍎 Computers can only make decisions based on specific operators. For example, ! means "not." You'll see this in future lessons.

> When you make comparisons in code, they always result in a Boolean value—either true or false. This helps us make decisions in our programs.

## Conditional Statements

Conditionals use a Boolean value to decide whether or not to do something.

```python
if value_one == value_two:
    print("The values are equal!")
    print(value_one)
```

Note the **code block** defined by indenting lines after a colon. This code block executes if the Boolean provided is `true`.

- Emphasize the importance of indentation when it comes to making a conditional work properly and starting a code block.
- Any code block is ended by providing a new line that's un-indented, which can be very easy to miss.
- This should be a review of what students saw in the pre-work.

## `else` Statements

You will often want to have an **`else` statement** immediately after the `if` statement. This will trigger when the `if` comparison turns out to be `false`.

```python
if value_one == value_two:
    print("The values are equal!")
else:
    print("The values are not equal!")
```

## Multiple Conditions

```python
if player_one_score == player_two_score:
    print("We have a tie")
elif player_one_score > player_two_score:
    print("Player one is victorious!")
else:
    print("Player two has triumphed!")
```

`elif` allows for conditional chaining, letting us check many possibilities back to back. Once one comparison evaluates as `true`, the chain exits.

### Discussion: What Happens in This Code?

```python
temperature = 0;
if temperature == 100:
    print("Leave your pets indoors for safety")
else:
    print("The weather is OK")
```

tktk image

### Careful! Equals Aren’t All Equal...

When you use `=`, that is an **assignment operator**.
If you try to use `=` instead of `==` in a comparison statement, you will get a syntax error!

Be sure to use the **equality operator** instead:

```python
temperature = 0;
if temperature == 100:
    print("Leave your pets indoors for safety")
```

## Partner Exercise: 3.1 Price Conditions 15 min TKTK

Now that our programs are able to make some decisions, it's time to test out our conditional logic with some price-based questions in **Section 3.1** of the workbook.

tktk image