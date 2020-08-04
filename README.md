# Lesson 6: Quick maths
Last lesson we introduced a new variable type `Scanner`\
We'll cover new variable types that can help us with challenging problems like 1 + 1 + 3

### `int` & `double`: vanilla & chocolate
  - [x] An `int` stands is an `int`eger
  - [x] A double stands for ~~`double`think~~ nothing
    - A double is simply a number with a decimal point
    - It is more precise than an integer (i.e. 3.14159...)
  - [x] `int` & `double` allow us to perform math operations

### &nbsp;:hand: Recall
In order to use variables in Java we must do two things
  1. declare
  2. initialize
Declaring looks like this: `int myInt;`\
Initializing looks like this: `myInt = 1;`\
You can declare many varibles at once like this: `int age, favoriteNumber;`\
You can also combine declaration and initialization like this: `int age = 1;`


### Which maths?
Java supports these basic operations &nbsp; :arrow_down:
  - [x] `+` : add
  - [x] `-` : subtract
  - [x] `*` : multiply
  - [x] `/` : divide
  - [x] `%` : modulo (i.e. find the remainder)

### Putting it together: Some example operations
```
  // declaring & init'ing 
  
  int myInt = 12;
  double myDouble = 1.1;
  int otherInt;
  otherInt = 1;
  
  // use
  int intResult = myInt + otherInt;
  int interestingResult = myInt * myDouble;
  int intQuotient = myInt / otherInt;
  int intMod = myInt % otherInt;
  
```

### &nbsp;:hand: Stop!
I urge you to open IntelliJ and try to run these lines of code.\
Then watch [this](https://youtube.com)

### Takeaways & extra `bits`
   - [x] Always match your variable types _or_ explicitly cast variable types
   - [x] `final` allows you to create an 'un-changeable' number à la `final myPermanInt = 100;`
    - `myPermanInt` now cannot have a value other than 100 & attempting to change will cause an error
    
### C'est fini
Exit ticket [here]()
   
 
 
