# Python

## Basics of Python

    print("Hello World")  # Hello World
    print(1 + 2)  # 3
    print(7 + 6)  # 13
    print()  # space
    print("The End")  # The End
    print("python string's are easy to use")  # python string's are easy to use
    print('we can include "quotes" in strings')  # we can include "quotes" in strings
    print("hello " + "world")  # hello world
    
    # variables
    
    greeting = "hello"
    name = "Arun"
    
    print(greeting + ' ' + name)  # hello Arun

output of program is as below

    Hello World
    3
    13
    
    The End
    python string's are easy to use
    we can include "quotes" in strings
    hello world
    hello Arun


## Functions of Strings

    # use of \n moves the string to next line
    splitString = "This is Arun\nWorking hard\nTo get a full time job"
    print(splitString)
    
    # o/p will be as below
    
    # This is Arun
    # Working hard
    # To get a full time job
    
    
    # use of tab
    
    tabbedNumbers = "1\t2\t3\t4"
    print(tabbedNumbers)
    
    # o/p will be
    # 1    2	3	4
    
    # special characters
    
    print("His car\'s tyres are flat")
    
    # His car's tyres are flat
    
    print('His car\'s tyres are flat')
    
    # His car's tyres are flat
    
    # to continue string over several lines, use """  ....   """
    
    splitStringOverSeveralLines = """This is
    Arun 
    working 
    hard"""
    
    print(splitStringOverSeveralLines)
    
    # o/p will be as below
    #
    # This is
    # Arun
    # working
    # hard
