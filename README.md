# Andreys_QA

Just some tips of mine for tests you should do in your code.

## INDEX

- [1.KNOW YOUR CODE]()   
- [2.LOGICAL TESTS]()   
    - [2.1.BASIC]()   
    - [2.2.ADVANCED]()
    - [2.3.FINISH IT]()   
- [3.PROGRAMER FRIENDS]()   

### 1.KNOW YOUR CODE   

At first this may look/sound _stupid_, but is more common to a programmer **not** know what it program does after some time, so take a time to read and keep notes about the functions/methods that your program call, this will be important in the future (One thing that might help is to keep the **ONLY** good part of the clean code).   
> "A name should tell you why it exists, what it does, and how it is used. If a name requires a comment, then the name does not reveal its intent."   
OK, so now that you know what your program does lets go to the most important part of this text.   

### 2.LOGICAL TESTS   

> "I don't know how to test my code."   
It's a phrase that I heard a lot, which really strikes me, is actually so much simple to test any code, if you know what it's suppose to do.   
If you followed the first part ([click me]()) you know how your program works, but if you are testing a program that isn't your, ask the person how's suppose to work.   
Remember to take notes of the tests, why it failed? What similar tests broke? Is a function/method call problem? Is a 

#### 2.1.BASIC   

Start with basic tests, if the program work with numbers try common numbers like: 1, 2, 3, 5, 7 10, 50, 100 and etc.   
If the program work with strings try common string like: "foo", "bar", "abc", "xyz", "hello", "world".   

#### 2.2.ADVANCED   

If the program passed the basic tests we can try advanced things, for numbers we can hit hard on negatives: -1, -2, -3, -5, -7, -10, -50, -100 and etc.   
If the program work with strings we can pass invalid strings or big strings like: NULL, "", "Hello World! Today is a beautiful day! I am curious about how big the string can be until the program brokens... Well I will hit enter............. NOW!" and etc.   

#### 2.3.FINISH IT   

OK... now we gonna hit the program **REALLY** hard for strings let go with something **BIG**:   
"Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam dui quam, laoreet ac augue nec, sagittis                           laoreet est. Aliquam dictum, lacus a congue blandit, mauris mi pharetra nulla, non fringilla lorem neque a mi. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae;                                        Etiam lacinia ullamcorper ligula, sit amet condimentum lectus tincidunt eu. Sed non neque eu nibh consectetur varius nec et tellus. Fusce lobortis dignissim enim, ut eleifend libero vestibulum ut. Aliquam fermentum pretium blandit. Sed luctus tempus purus, quis pharetra diam fermentum vel. Nunc facilisis nunc id nulla volutpat condimentum. Donec quis erat aliquam urna viverra tristique in tincidunt purus. Ut et hendrerit ante. Pellentesque non vestibulum justo. Quisque sit amet felis nec mi faucibus ullamcorper quis a arcu. Mauris volutpat, dolor vitae luctus scelerisque, ligula justo dignissim metus, sit amet laoreet quam sem vitae lectus. Vivamus pellentesque leo vel dui iaculis, in mollis dolor sagittis. Sed faucibus dignissim ipsum lobortis semper.".   
... YES, this is **ONE** string... if you like to go even futher you can try a bigger [lorem ipsum](https://lipsum.com).   
We also have a string like "     I may b      e simp      le but     did you                    see ho      w m an          y                 white                                                                                                  spaces                                             i h     a v     e   ~'@#$&\*()\_-+=789456123,,,,,??|/\\;:><..!                                          ".   
Now numbers... well we are not going too far just: -0, -2147483648, 2147483647, 2147483648, -2147483649, -9999999999999999999999, 99999999999999999999999999 and etc.   
If your program failed in any of the tests that's expected, the idea of the tests, is to try simple cases that you may think of then go to harder cases that can cause some headache, otherwise go drink some coffe, tea, Monster™️ or whatever you want, the important is to have a time to relax.   

### 3.PROGRAMMER FRIENDS   

I call they friends... but for some people they can be enemies.   
First we have our memory leak detector, [Valgrind](https://valgrind.org) ([a good video to see some basics of valgrind](https://www.youtube.com/watch?v=DyqstSE470s)).   
Next the debugger frined [GDB](https://sourceware.org/gdb) ([another video for learning some basics](https://www.youtube.com/watch?v=gFCQ37jVN3g)).   

<p align="center">
    Made with 🧠 by @<a href="https://github.com/andreyvdl">andreyvdl</a>
</p>
