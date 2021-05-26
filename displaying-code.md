# Display our code
**Puts** and **print** are used to display information to the user in the console.
Puts will also print a return line after its content.

**gets.chomp** is used to get input from the user, which we can store in a variable. The .chomp enables us to remove empty spaces or characters added by the user, by pressing enter for instance.

```
print 'Hey, '
puts "what's your name?"
name = gets.chomp
puts "Welcome #{name}!"
```

results in:
```
Hey, what’s your name?
```
The user enters his name, ‘John’ and presses enter. The program will store the name and greets the user:
```
Welcome John!
```
