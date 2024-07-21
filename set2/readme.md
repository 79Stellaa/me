TODO: Reflect on what you learned this week and what is still unclear.
MC Hammer. I don’t know why I am going to dquote, and I asked Google and control+C to leave.

cd ..\course                       # changes directory to the course directory
git pull                           # pulls the latest code down
pip install -r .\requirements.txt  # Installs the latest python modules
cd ..\me                           # puts you back into your me directory

Boolean-answer to a logical question(true or false)
String-text, or things to be treated as text("hello world" or "450")

There should be a space before and after assignment operators, arithmetic operators, comparison operators, and logical operators. 
Special case: When different operators have different precedences, sometimes not adding spaces can improve the clarity of the expression 
x = a*2 + b*3


Features                     Tuple                           List                    Set
Definition:             Ordered,immutable              Ordered, mutable         Unordered, mutable
Syntax:                       ()                              []                      {}
Modification:             Unmodifiable                      Modifiable              Modifiable
Element access:       Accessible by index             Accessible by index       Not accessible by index
Duplicates allowed:         Allowed                         Allowed               Not allowed
Purpose:               Immutable data set             Mutable data set           Unique data set


()
1. Function call: greet()
2. Defining Tuples: my_tuple = (1, 2, 3)
3. Control Operator Order
4. Generator expressions: gen_expr = (x * x for x in range(10))
   The same type of brackets can appear at the same time
[]
1. Definition List: my_list = [1, 2, 3]
2. Data access of lists, dictionaries, tuples, etc.: my_list = [1, 2, 3]   
                                                     print(my_list[2])
3. List comprehension: squares = [x * x for x in range(10)]
{}
1. Definition dictionary: my_dict = {"name": "Stella", "age": 20}
2. Defining a Collection: my_set = {1, 2, 3}
3. Dictionary comprehensions and set comprehensions: my_dict = {x: x * x for x in range(5)}
                                                     my_set = {x * x for x in range(5)}
4. String formatting (f-string): name = "Stella"
                                 greeting = f"Hello, {name}!"





range(5) is from 0 to 4