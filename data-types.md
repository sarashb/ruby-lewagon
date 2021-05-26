## Data types
Everything in Ruby is an object. Objects have built-in methods you can call on them.

### Integers
* To represent whole numbers
* Can do standard arithmetic

```
4. class             # => Integer 
1 + 2               # => 3
2 * 4                # => 8
4 / 2               # => 2
```

* Also has custom methods built-in
```
20.even?              # => true
20.odd?               # => false
```

* You can convert numbers to strings
```
1984.to_s          # => "1984"
```
### Floats

* To represent decimal numbers
```
3.14.class         # => Float
1.23 + 2.1         # => 3.33
```

* Has it’s own built-in methods
```
3.14.round         # => 3
```

### Strings
* To represent text
* Defined with single quotes or double quotes: 'wagon' or "wagon"

```
"wagon".class           # => String
'wagon'.class           # => String
'Hello world!'. class   # => String

"wagon".upcase       # => "WAGON"
"wagon".capitalize   # => "Wagon"
```

* You can convert strings to numbers
```
'1984'.class         # => String
'1984'.to_i          # => 1984
'1984'.to_i.class    # => Integer
```
* You can add two strings using concatenation:
```
"Ruby" + " " + "workshop"      # => "Ruby workshop"
```

* We can inject Ruby code into a string by using interpolation. However this only works in double-quoted strings. If you use single quotes Ruby will just print it out as is:
```
'two: #{1 + 1}'      # => "two: #{1 + 1}"
"two: #{1 + 1}"      # => "two: 2"
```

### Booleans

* To represents something that is true or false:
```
18 < 25              # => true
10 + 5 == 20         # => false
```
