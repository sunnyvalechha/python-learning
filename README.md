# python-learning

* High Level Language: Humans interact in languages called as high level language.

* Low Level Language: Computer only understand binary language or digital signal called as Low level language.

* Complier: A compiler convert a code from high level to low level but a compiler convert all the code in one go. Ex: If 5 lines are written in a code, so compiler will try to read the code in  all together and throws error if any.

* Interpreter: An interpreter does the same thing, convert a code from high level to low level but interpreter check the code line by line and show us the error in specific line only.

**Python Execution Environment**

![image](https://github.com/sunnyvalechha/python-learning/assets/59471885/edc57540-3aa1-41fb-996c-4f0ab697144f)

* Take file.py as a source code which is a High level language
* This code goes to python compiler but this is interpreter, this just have a name compiler but in actual this works as a interpreter.
* After checking code line by line, convert this code into byte code often called as intermediate code. In C language we called byte code as object code. Here pyc is referred to python compiled version.
* This code convert at execution phase called as Python virtual machine (PVM) or Just in time (JIT) compiler. Inside the PVM the interpreter resides and works.
* At the end, PVM reads line by line of Byte code and converted into Machine understandable byte code and it is read by OS and processor gives result.

========================================================================================================

# Datatype in python

Anything we provide as input to the programming language, datatype is allocating memory space to these inputs these inputs are objects like int, float, boolean.

Data type memory Allocation:

1 Byte = 8 Bits
              DOS       UNIX
* Int    -    2 Bytes  4 Bytes
* Float  -    4 Bytes  8 Bytes
* Double -    8 Bytes  16 Bytes
* Char   -    1 Byte   1 Byte

Because of above memory allocation we cannot run a code of DOS OS to another OS like UNIX. This is why C and C++ language is platform dependent.

In Java programming memory allocation is same for all data types means Java is plaform independent.

# Python is Dynamically typed High level Programming language.

Generally we have 2 types of programming language.

1. Statically typed
2. Dynamically type

In Statically typed Programming language, It is mandatory to specify the data type otherwise we will get compile time error.

Example: In C language we have to declare the variable type before specifying the value.

![image](https://github.com/sunnyvalechha/python-learning/assets/59471885/23aaca87-322b-4192-a5df-59b17182bd46)

Where as in Python there is no need to declare the variable type. It is intelligent enough to understand the data type automatically. *Python is dynamically typed programming langugage*

![image](https://github.com/sunnyvalechha/python-learning/assets/59471885/4a83abdc-c2dc-4101-8076-31c7019eacd2)

# Data Representation in Python

* Literal - Input values passing to the program, like Numeric, String, Boolean.

  All literals are stored in a main memory, by allocating sufficient amount of memory by the help of data types.

* In python we have to specify distinct value of variable so the system will not get confuse between the value. Ex: If we provide the same variable even with different value so the system will confuse.
* Those distinct value we called as identifiers also called as **Variables**

**Data Type in Python**

![image](https://github.com/sunnyvalechha/python-learning/assets/59471885/a9717e88-d370-49cf-8e21-d5e009c38368)





