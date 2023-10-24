## Understanding Variables and Data Types in Python

### A Simple Variable Declaration
First things first, what is a variable? In Python and in other programming languages, a variable is simply a placeholder for some value such as your name `your_name = John`

Here we define my name as
` my_name = "Sabrina"`

So anywhere I would want to say my name, I can just use the variable name `my_name` for example : 
instead of 
`print("Sabrina")`
> Sabrina

I can write: 
`print(my_name)`
> Sabrina 

Now, lets break down the declaration of `my_name = "Sabrina"`

The first part of this variable declaration is `my_name`, this is the name of the variable. It could be almost anything you want as long as there are no spaces and except for a handful of reserved names that python uses (see list here)[linkhere]. 

Now the `=  ` is used to tell the program what the variable `my_name` refers to, think of the equal sign `=` as a verb so that the above delcaration of `my_name = "Sabrina"` you could read as "my name IS "Sabrina"

Finally, I tell the program what the variable `my_name` should be, in this case we refer a series of charaters as a "string." In this case, the string is "Sabrina", but it could easily be anything else such as `"John"` or even nonsense `"fjasjflksdjflf"`

### Data Types

Now this brings us to the topic of datatypes, programs very rarely exclusively use the `string` data type, programs tend to need to use numbers, true or false values, or other more complex data types. 

While python makes using different data types a bit easier than other langauges. Because we don't have to explictly tell the program, "okay we now want a string variable", we can just write `my_var = "something"`. 

So when writing your python program you can simply declare `a_number = 1` and Python infers that you want to use a number and will figure out the rest

Now there are a lot of different datatypes in programming languages. The major ones are listed below 

1. Strings
    a String is delcared whenever you place a symbol in quotations such as `"apple"` or numbers `"123"` or even symbols `"!!!!!"`. Python doesn't care, as long as its in quotations, python infers those values as strings. 
2. Integers
    Integers are basically any whole numbers such as `my_int_example = 1` or `my_additon_example = 1+2` notice when we dont use the quotations python reads those values as numbers, so python figures out the results of basic mathimatical expressions

    `print(my_int_example)`
    > 1
    `print(my_addition_example = 1+2)`
    > 3 
3. Doubles, Floats etc. 
 While other number data types are needed to be more explictly defined in other langugages, Python also uses numbers that aren't integers such as `pi = 3.14` or `my_double = 1222.111111111`. In python, you can add integers and doubles together to get another double, but once you add an integer to any other numerical datatype, you forever convert that value into that more complex numerical datatypes. 

 4. Booleans
  Booleans are simply the values `true` and `false`, such as `my_truth = True` and `my_false = False`
  Not again, the values `True` and `False` are not strings but built in data types that python knows how to use. Additionally booleans in pPython adhere to Boolean logic [link here](example), which simply simplifys boolean values into a single `True` or `False` value. 
  
  For example:
  `my_and = True and False`
  > `print(my_and)`
  > False

  `my_or = True or False`
  > `print(my_or)`
  > True


  ### Final notes
  While there are other edge cases and caveats to python variables and datatypes, the above information will get you started. Because it can be easy to get stuck in small minutae of programming languages. 
  
  So if your python program behaves unexcpectly don't be afraid to Google or ask someone. 