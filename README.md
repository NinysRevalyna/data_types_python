# PYTHON GUIDE #1
## Python Data Types
In computer programming, data types specify the type of data that can be stored inside a variable.

### Number
Number is a Python data type that stores numeric values. Number is an immutable data type. 

There are 3 numeric types in Python :
* Integer or int is a whole number, positive or negative, with no decimals, and unlimited length

  ![image](https://github.com/NinysRevalyna/data_types_python/assets/72516143/38598090-b3d8-4a38-b1b7-d6189f2bfc0a)

* Float is a number, positive or negative, that contains one or more decimal places.

  ![image](https://github.com/NinysRevalyna/data_types_python/assets/72516143/34607989-5900-49b2-a9b2-46fddc897404)

* Complex numbers are represented as a+bi or a+bj, where a is the real part and b is the imaginary part.

  ![image](https://github.com/NinysRevalyna/data_types_python/assets/72516143/7335b0ec-75d7-40c4-9f64-c2803fc8089b)


Use the type() function to find out which class a variable or value belongs to.

### String
A string is a data type that represents a sequence of characters, numbers, or symbols, and is always considered text. String are _"Immutable"_ which means they cannot be changed once they are created.

__1. Escape Character__
* To insert characters that are illegal in a string, use an escape character.
* An escape character is a backslash `\` followed by the character you want to insert.

  Escape characters used in Python:
  * `\n` used for new line

  ![image](https://github.com/NinysRevalyna/data_types_python/assets/72516143/291c2ddc-53ff-4a57-b086-5e5bc953b57f)

__2. Slicing String__
  * Because strings are similar to lists, the slicing operator [] can also be used on strings to retrieve their contents or even substrings.

    ![image](https://github.com/NinysRevalyna/data_types_python/assets/72516143/7884781e-762d-4a35-92f0-e4167fd9b780)

### List
* Lists are used to store multiple items in a single variable.
* To declare a list, brackets `[]` are used and each member is separated by a comma.
* List items are indexed, the index start form 0
* List items are ordered, changeable, and allow duplicate values
* Lists can contain members of the same or different types

__1. Python List Method__
* The `del` keyword is used to delete an object or an element in an object

  
* The `len()` method will return the sum of the total items in an object. on a string, this function will return the number of characters
* The `append()` method is used to add an item at the end of an object
* The `extend()` method adds all elements of the iterable to the end of the list
* The `del()` method del is used to delete objects.
* The `insert()` method inserts an element into the object according to the index specified in the parameter
* The `remove()` method removes the first element whose content is equal to the parameter value
* The `pop()` method removes the item according to the index in the parameter and returns the deleted value
* The `index()` method returns the index according to the value written in the parameter
* The `count()` method returns the number of elements in the object that have the same value in the parameter
* The `sort()` method sorts the list items in ascending order by default
* The `reverse()` method will return list from tail index to head

### Boolean
* It's often used for returned value on comparison an expression
* Has a `True` or a `False` value

  ![image](https://github.com/NinysRevalyna/data_types_python/assets/72516143/b64900f0-c75b-445c-9d7a-df9dae3dde8c)


### Tuple
* A tuple is a collection which is ordered, allow duplicate values and unchangeable.
* Tuples are written with round brackets `()`
* Tuples are used to store multiple items in a single variable
* Tuple items can be of any data type

  ![image](https://github.com/NinysRevalyna/data_types_python/assets/72516143/5b69772c-be52-49d4-a9a3-2179998170f8)


### Set
* A set is a collection which is unordered, unchangeable, and unindexed.
* Sets are written with curly brackets `{}`
* Sets are used to store multiple items in a single variable and must be unique
* Set items can be of any data type

__1. Set Method__
* The `union()` method is returned a set that contains all items from the original set, and all items from the specified set(s)

  ![image](https://github.com/NinysRevalyna/data_types_python/assets/72516143/befae301-33e8-4961-bee1-54879bb0855b)


* The `intersection()` method is returned set contains only items that exist in both sets, or in all sets if the comparison is done with more than two sets

  ![image](https://github.com/NinysRevalyna/data_types_python/assets/72516143/46883e18-38dd-4035-b2dd-26770f840af1)


### Dictionary
* A dictionary is a collection that is unordered, changeable, and do not allow duplicates
* Dictionaries are written with curly brackets `{}`
* Dictionary items are presented in key-value pairs, and can be referred to by using the key name

  ![image](https://github.com/NinysRevalyna/data_types_python/assets/72516143/5914db81-3f56-483a-939b-28625fbf6420)

### Conditional Expression
  ### If
  If is used to anticipate conditions that will occur during the program and determine what actions will be taken according to the conditions.
  * The `if` condition is used to execute code if the condition evaluates to `True`.
  * If the condition evaluates to `False` then the statement/condition `if` will not be executed.
   
    ![image](https://github.com/NinysRevalyna/data_types_python/assets/72516143/9f884547-c8b8-43f5-a42c-38dae31abf8c)

  ### Else
  * The `else` condition is if the condition is `True` then it will be executed in if, but if it is `False` then the code will be executed in `else`.

    ![image](https://github.com/NinysRevalyna/data_types_python/assets/72516143/37dd287f-51b8-4f95-a79a-a7e2925b8efd)

  ### Elif
  * If the condition for if is `False`, it checks the condition of the next `elif` block and so on.
  * If it is `False` the body of `else` is executed. Only one block among the several `if`... `elif`... `else` block is executed according to the condition.
  * In other words, we can say that `elif` is python way of sating "if the previous conditions were not true, then try this condition

    ![image](https://github.com/NinysRevalyna/data_types_python/assets/72516143/668f657a-21e7-4c35-8977-955586ee0298)

### Loop
In computer programming, loops are used to repeat a block of code.

There are types of loops in Python:

__1. For Loop__
  * `for` is a function that can loop over each type of variable in the form of a collection or sequence.
  * The variable in question can be a `list`, `string`, or `range`.
  * If a `list` or sequence contains an expression, it will be evaluated first.
  * Then the first item in the sequence/list will be assigned as the iterating_var variable.
  * Afterwards, the block of statements will be executed, continuing to the next item, repeating itself, until the entire sequence is completed.
    
    * __Loop Through a String__

      ![image](https://github.com/NinysRevalyna/data_types_python/assets/72516143/bbe53797-f5fa-4de0-a5fd-11a3bbb93d64)

    * __For Loop with Python range()__

      ![image](https://github.com/NinysRevalyna/data_types_python/assets/72516143/a14d2656-d926-4c70-a2c2-c56addce32af)

    * __Nested Loops__
   
      A nested loop is a `loop` inside a `loop`.

      ![image](https://github.com/NinysRevalyna/data_types_python/assets/72516143/e599e27d-76fb-4b2f-98f3-cde3797917bf)

















