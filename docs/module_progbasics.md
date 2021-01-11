# Programming Basics questions

## Computer science

### Data structures

#### What is the purpose of a list (array in some programming languages) data structure? Name some methods of it!
- Depending on the language, array types may overlap (or be identified with) other data types that describe aggregates of values, such as lists and strings. Array types are often implemented by array data structures, but sometimes by other means, such as hash tables, linked lists, or search trees.[2] In Python, the built-in array data structure is a list.
#### What is the difference between a list/array and a set?
- List is an ordered sequence of elements whereas Set is a distinct list of elements which is unordered.
#### What is the purpose and methods of a dictionary/map data structure?
- Dictionary is a data structure that supports
lookups and updates efficiently
- Map is a relation between set of keys and set of
values

### Algorithms

#### Fibonacci sequences. Write a method (or pseudo code), that generates the Fibonacci sequences.
- Fibonacci(n-1)+Fibonacci(n-2)
#### How do you find a max value in a list/array if you can’t use any built-in functions?
-  def maximum(items, default=None):
    iterator = iter(items)
    m = next(iterator)
    for item in iterator:
        if item > m:
            m = item
    return m
#### How do you find the average of values in a list/array if you can’t use any built-in functions?
- print sum(l) / float(len(l))
#### What do we call an *in-place* sort?
- Sort in place means to sort an existing list by modifying the element order directly within the list. The opposite is leaving the original list as is and create a new list with the elements in order.
#### Explain an algorithm which sorts a list!
- 

### Programming paradigms - procedural

#### What is the call stack?
- a stack data structure that stores information about the active subroutines of a computer program.
#### What is “Stack overflow”?
-  betelt a stack (elore meghatarozott mennyiseg[atmeneti tarolo])
#### What are the main parts of a function?
- The input.
- The relationship.
- The output.

### Programming languages - Python

#### How do you use a dictionary in Python?
- Kapcsos zarojellel / "{}"
#### What does it mean that an object is immutable in Python?
- Create the object and assign some value to it, you can't modify that value.
#### What is conditional expression in Python?
- if, elif, else, False/True
#### What are different types of arguments in Python?
- default arguments.
- keyword arguments.
- positional arguments.
- arbitrary positional arguments.
- arbitrary keyword arguments.
#### What is variable shadowing? (context: variable scope)
- When a variable "hides" another variable with the same name. 
#### What can happen if you try to delete/drop/add an item from a List, while you are iterating over it in Python?
- we remove the item at index 0, and the item at index 1 becomes the item at index 0. Our next time through the loop, we remove the item at index 1 which was previously the item at index 2
#### What is the "golden rule" of variable scoping in Python (context: LEGB)? What is the lifetime of variables?
- Understandable names. 
#### If you need to access the iterator variable after a for loop, how would you do it in Python?
- return
#### What type of elements can a list contain in Python?
- integer, string
#### What is slice operator in Python and how to use?
- [i:j] mettol meddig valo nyomtatas 
#### What arithmetic operators (+,*,-,/) can be used on lists in Python? What do they do?
- +, * +: osszeadja, *: annyiszor nyomtatja ki(hajtja vegre)
#### What is the purpose of the in and not in membership operators in Python?
- They are used to test whether a value or variable is found in a sequence (string, list, tuple, set and dictionary).
#### What does the + operator mean when used with strings in Python?
- Joining of two or more strings into a single one is called concatenation.
#### Explain f strings in Python?
-  f-strings are string literals that have an f at the beginning and curly braces containing expressions that will be replaced with their values.
#### Name 4 iterable types in Python!
- list, tuple, dict, set
#### What is the difference between list/set/dictionary comprehension and a generator expression in Python?
- The generator yields one item at a time and generates item only when in demand. Whereas, in a list comprehension, Python reserves memory for the whole list.
#### Does the order of the function definitions matter in Python? Why?
- The only thing that Python cares about is that the name is defined when it is actually looked up. That's all.
#### What does unpacking mean in Python?
- Unpack will assign the different values of the right argument inside the different left arguments.
#### What happens when you try to assign the result of a function which has no return statement to a variable in Python?
- return None is added to the end of a function.

## Software engineering

### Debugging

#### What techniques can you use while debugging a program in Python?
- program and press F7 (Debug->Run). 
- Visual studio code
#### What does step over, step into and step out mean while using the debugger?
- step over : lepes atugrasa (lefut, de nem vizsgaljuk)
- step into: belepes az adott lepesbe es annak minden fazisanak a megvizsgalasa
- step out: kilepes a lepesbol (megtalaltuk a hibat/ nem ott van hiba)
#### How can you start to debug a program from a certain line using the debugger?
- visual studio code : break point

### Version control

#### What are the advantages of using a version control system?
- Allow you to compare files, identify differences, and merge the changes if needed prior to committing any code.
#### What is the difference between the working directory, the staging area and the repository in git?
- Working directory: You can access the commit history with the Git log.
  Staging Area: contains the proposed next commit.
  Repository: repository tracks all changes made to files in your project, building a history over time.
#### What are remote repositories in git?
- Remote repositories are versions of your project that are hosted on the Internet or network somewhere.
#### Why does a merge conflict occur?
- Two separate branches have made edits to the same line in a file, or when a file has been deleted in one branch but edited in the other.
#### Through what series of commands could you put a new file into a remote repository connected to your existing local repository?
- In the Command prompt, add the URL for the remote repository where your local repository will be pushed.
  *git remote add origin remote repository URL
  *git remote -v
#### What does it mean atomic commits and descriptive commit messages?
- Short b ut full of information to ourself.
#### What’s the difference between git and GitHub?
- Git is a version control system that lets you manage and keep track of your source code history. GitHub is a cloud-based hosting service that lets you manage Git repositories.

## Software design

### Clean code

#### What does clean code mean?
- Clean code is code that is easy to understand and easy to change.
#### What steps do we usually do during a clean code refactoring?
- Understand the code, change it to do the same before refactoring. Shorter but understandable.

### Error handling

#### What is exception handling?
- 
#### What are the basics of exception handling in Python?
- exceptions can be handled using a try statement. can raise an exception is placed inside the try clause. 
#### In which case should we catch an exception? Why?
- When that error occurs, Python generates an exception during the execution and that can be handled, which avoids your program to interrupt.
#### What can/should we do with an exception in the ‘except’ block?
- find a solution for the error
#### What does the else and finally statement do in a try-except block in Python?
- Else: If there is not any exception then this block will be executed. 
- Finally: Finally block always executed either exception generating or not

## Software Development Methodologies

#### What is the main goal of a retrospective meeting?
- A Retrospective is a ceremony held at the end of each iteration in an agile project. The general purpose is to allow the team, as a group, to evaluate its past working cycle. In addition, it's an important moment to gather feedback on what went well and what did not.

## Programming environment

### Unix

#### What is UNIX and what is Linux?
- Linux refers to the kernel of the GNU/Linux operating system.
- Unix refers to the original operating system developed by AT&T.
#### What do we call the shell in Linux?
- shell: alap parancsok ertelmezi, in root what are there, gep kommunikacio
#### What does root means in a Linux environment?
- Root is the superuser account in Unix and Linux.
#### How do you access your personal files in Linux?
- /home/username
#### How can you install an application in Linux?
- sudo apt install app_name
#### What is package management in Linux, what are repositories?
- pm: a method of installing and maintaining
- repo:  repositories includes many thousand of packages, each specially built and maintained for the distribution.
#### How do you navigate in the filesystem with the command line?
- cd (change directory)
#### What does the following commands do: mkdir, rm, cat, cp, touch?
- touch: Create a new file or update its timestamp.
- cat: Concatenate files and print to stdout.
- cp: Copy files
- mkdir: Make directory
- rm: Remove files and directories
#### How can you look up what does a command do in Linux if you have no internet connection?
- The help command shows a short list of the commands built into the Bash shell itself.
#### What does the following commands do: head, tail, more, less?
- less: lockfile -> last 10 line write out (less -n "file")
    head: 
#### How do you download a file from internet using the terminal?
- wget http://.....
