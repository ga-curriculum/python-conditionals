<h1>
  <span class="headline">Python Conditionals</span>
  <span class="subhead">Logic Operators</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to tktk

| Lesson          | Duration |
| --------------- | -------- |
| Logic Operators | 60 min   |

## Nesting Conditionals

You can include a conditional **inside of another** if you want to check multiple conditions:

```python
product_is_good = True
bank_account = 500

if product_is_good == True:
    if bank_account > 100:
        print("Let's buy this product!")
```

> 🍎 This way, we only check the “bank_account” variable IF our first condition is also met. However, this can get a bit messy; for this simple situation, it isn't worth having more indented blocks just to add one condition. So, what's the alternative?

## Multiple Conditions, One Statement

You can check to see if two conditions are met in one statement with a **logic operator**:

```python
product_is_good = True
bank_account = 500

if product_is_good == True and bank_account > 100:
    print("Let's buy this product!")
```

## Logic Operators

**Logic operators** allow us to combine multiple conditions together. For very complex conditionals, you can put several conditions in parentheses to evaluate them as a single expression.

| **Operator** | **Description**                                               |
| ------------ | ------------------------------------------------------------- |
| `and`        | Evaluates to `true` only if all combined values are `true`.   |
| `or`         | Evaluates to `true` if any of the combined values are `true`. |
| `not` / `!`  | Reverses the Boolean result of whatever follows it.           |

## Pro Tip: Condensing Conditionals

Like we saw in the previous section, not all conditionals need a comparison statement — especially if the values being tested are already Booleans.

Thus, you will rarely see a comparison with `== true` or `!= false`. Instead, you can use the following pattern:

```python
if product_is_good and not product_is_too_expensive:
    # do something
```

## True or False?

1. `15 > 10 and 25 > 30`

2. `len("apples") > 5 or len("orange") < 2`

3. `(5 > 10 and 10 > 15) or "orange" == "orange"`

4. `"bananas" not in ["oranges", "apples"] and len("bananas") < 10`

5. `2 + 2 != 4 and 2 + 2 == 5`

<details>
<summary>✅ Click to see the answer: </summary>
<hr>

1. False
2. True
3. True
4. True
5. False

<hr>
</details>

## Making Conditionals Easier

`print()` is your friend.

- Leave yourself messages to figure out what path was taken by a conditional.

- If a conditional gives you mysterious results, log the values and data types.

- You can also print the Boolean result of a comparison as a sanity check.

Avoid chains that are far too long for one line.

- You can nest conditionals within other conditions for complex logic.

> 🍎 If you're checking the value of three different variables, for instance, and have different operations you want to perform for each of the combinations, it's better to nest the conditions instead of having nine extremely long statements in an “if...elif...elif...elif...” situation.

## Solo Exercise : 3.2 Complex Conditions 60 min TKTK

Some complex conditional challenges await you in Section 3.2 of the Jupyter Notebook. You will need to use our new friends, logical operators, to complete these challenges.

tktk image

- Expect these challenges to be a bit complex. Take your time working through them.

- You will have 10–15 minutes to complete each challenge. Afterward, we'll review each one together to make sure everyone understands before moving on.

- If you finish early and feel confident, you can try an extra challenge by incorporating more complex data structures, like storing your data in a dictionary or list.

- We may also use this time to review material from the previous lesson, focusing on lists and dictionaries to reinforce your understanding.
