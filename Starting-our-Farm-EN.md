---
title: Starting our Farm
description: Create simple algorithms using function calls requiring strings as arguments to control a farming robot. Practice computational thinking through different examples.
---

# Preparation

The Farmbot will need to prepare the soil for planting. Use the command `prepare_soil()`.

## ---Tasks---

- Add the command `prepare_soil` into the editor and press run to see what happens.

## ---Files---

```py title="solution.py"
prepare_soil()
```

## ---Tags---

- Introduced: `prepare_soil()`, `return_home()`, `plant()`, What are functions, Calling Functions, Passing Arguments, Algorithm

---

# Prepare the soil

## ---Tasks---

- Prepare soil, move forward and then prepare more soil

## ---Files---

```py title="solution.py"
prepare_soil()
move_forward()
prepare_soil()
```

## ---Tags---

- Use: `prepare_soil()`, `move_forward()`, `prepare_soil()`, `return_home()`, `plant()`

---

# Ready a row

## ---Tasks---

- Prepare three patches of soil in a row, then return home

## ---Files---

```py title="student.py"
prepare_soil()
move_forward()
prepare_soil()
move_forward()
prepare_soil()
return_home()
```

## ---Tags---

- Use: `move_forward()`, `prepare_soil()`, return_home()

---

# Planting

The Farmbot can plant crops using the command `plant()`

## ---Tasks---

- Add the plant function to the code, and press run. Can you figure out how it works?

## ---Files---

```py title="solution.py"
prepare_soil()
plant("tomato")
```

## ---Tags---

- (Introduced): plant()
- (Observed): prepare_soil()

---

# Functions

`prepare_soil`, `move_forward` and `plant` are examples of functions.
**Function**: A Function is a command that performs a specific action when called.
**Function Call**: A Function Call tells the computer to run a function, using open and closing brackets ( ) after the name of the function: `move_forward()`, prepare_soil() are both function calls.

## ---Tags---

- (Introduced): What are functions, Calling Functions

---

# Which of these are function calls?

- [x] `prepare_soil()`
- [x] `move_forward()`
- [ ] `"tomato"`
- [ ] `prepare_soil`

## ---Tags---

- (Identify): Calling Functions, `prepare_soil()`, move_forward()
- Understand: Calling Functions, What are functions, Algorithm

---

# Arguments

A function may need extra information when it is called, this can be provided by using an argument.

Below, `“tomato”` and `“aubergine”` are arguments given to the function `plant()`.
**Argument**: An argument is a value that goes between the brackets after the function name. This may change what the function does.

## ---Tasks---

- Add the arguments to the plant functions to plant an aubergine and a tomato.

## ---Files---

```py title="solution.py"
plant("aubergine")
move_forward()
plant("tomato")
return_home()
```

## ---Tags---

- (Introduced): Passing Arguments
- Use: plant()
- (Observed): `move_forward()`, return_home()

---

# Prepare and plant

## ---Tasks---

- Prepare the soil and plant a tomato

## ---Files---

```py title="solution.py"
prepare_soil()
plant("tomato")
```

## ---Tags---

- Use: `plant()`, prepare_soil()

---

# What is a function?

- [x] A Function is a command that performs a specific action when called.
- [ ] Functions are commands that allow you to convert your code from one language to another
- [ ] Functions are words that always have brackets after them
- [ ] Functions are commands that have quotes around them and can be put between brackets

## ---Tags---

- (Recall): What are functions, `move_forward()`, Algorithm
- Understand: What are functions

---

# Which function call moves the Farmbot forward?

- [x] move_forward()
- [ ] moveForward()
- [ ] Move_Forward()
- [ ] move_forward

## ---Tags---

- (Recall): move_forward()

---

# A row of potatoes

## ---Tasks---

- Plant three potatoes in a row. Remember to prepare the soil first.
- Return to the home plate.

## ---Files---

```py title="student.py"
prepare_soil()
plant("potato")
move_forward()
prepare_soil()
plant("potato")
move_forward()
prepare_soil()
plant("potato")
return_home()
```

## ---Tags---

- Use: `prepare_soil()`, `plant()`, `return_home()`, move_forward()

---

# Algorithms

You have been writing in Python to program the Farmbot. In the last example, you created an **algorithm** to plant a row of potatoes.
**Algorithm**: An algorithm is a set of commands used to perform a particular task.

## ---Tags---

- (Introduced): Algorithm

---

# What is an algorithm?

- [x] An algorithm is a set of commands used to perform a particular task.
- [ ] An algorithm is a set of instructions that are to be repeated more than once
- [ ] An algorithm is any computer program
- [ ] An algorithm is a command created by Mr. Algo Rhythm

## ---Tags---

- (Recall): Algorithm
- Understand: Algorithm

---

# Summary

**Functions**: are commands that allow you to perform a specific action without having to write lots of code
**Function Call**: tells the computer to run a function, using open and closing brackets ( ) after the name of the function
**Argument**: is a value that goes between the brackets after the function name
**Algorithm**: is a set of commands used to perform a particular task
**prepare_soil()**: is a function that tells the Farmbot to prepare the soil
**plant()**: is a function that takes a single argument such as “potato” and plants the specified crop
**Sequential Programming**: Programming in sequence

## ---Tags---

- (Remind): What are functions, Calling Functions, Passing Arguments, Algorithm, `prepare_soil()`, `move_forward()`, move_forward()
