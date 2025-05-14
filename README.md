Lua (Luau) Programming Tutorials: From Beginner to pro
## Lesson 1: Introduction to Lua (Luau):
### What is Lua (Luau)?!:
Lua is a lightweight, fast scripting language designed for embedding in larger applications. Luau is a modified version of Lua developed by Roblox for game development on their platform.  

### Why Learn Lua (Luau)?!:
- Easy to learn for beginners
- High Performance 
- Supports Object-Oriented Programming (OOP)
- Used in games like roblox

### Setting up Lua (Luau):
- For Lua: Download the interpreter from https://lua.org/
- For Luau: Use **Roblox Studio**

## Lesson 2: Writing Your First Program
### Basic Syntax: print()
The clasic "Hello, World!" program:
```lua
print("Hello, World!")
```

# Explanation:
- `print()`: Outputs text to the console
- Text must be inside "" or '',

### Comments in Lua:
```lua
-- Single-line comments
--[[
   Multi-line
   Comments
]]
```

## Lesson 3: Variables and data types:
### Basic Data Types:

1. Numbers:
```lua
local num = 10
local float = 3.14
```

2. Strings:
```lua
local name = "Mahmoud"
local message = 'Hello'
```

3. Booleans:
```lua
local isTrue = true
local isfalse = false
```

4. Tables: (More details later)

### Variables:
- `local`: Declares a local variable
- Without `local` Global Variable (not recommended)
```lua 
local age = 20
name = "Mahmoud" -- Global Variable
```

## Lesson 4: Operators (Math & Logic)
### Math Operators:
```lua
local a = 10
local b = 5

print(a + b) -- 15 (Addition)
print(a - b) -- 5 (Subtraction)
print(a * b) -- 50 (Multiplication)
print(a / b) -- 2 (Division)
print(a % b) -- 0 (Modulus)
print(a ^ b) -- 100000 (Exponent)
```

### Logical Operators:
```lua
local x = true
local y = false

print(x and y) -- false (AND)
print(x or y) -- true (OR)
print(not x) -- false (NOT)
```

### Comparison Operators:
```lua
print(5 == 5) -- true
print(5 ~= 3) -- true (~= means "not equal")
print(10 > 5) -- true
