# Programming Basics questions

## Computer science

### Data structures

#### What is the purpose of a list (array in some programming languages) data structure? Name some methods of it!
- Depending on the language, array types may overlap (or be identified with) other data types that describe aggregates of values, such as lists and strings. Array types are often implemented by array data structures, but sometimes by other means, such as hash tables, linked lists, or search trees.[2] In Python, the built-in array data structure is a list.
#### What is the difference between a list/array and a set?
- List is an ordered sequence of elements whereas Set is a distinct list of elements which is unordered.
#### What is the purpose and methods of a dictionary/map data structure?
-

### Algorithms

#### Fibonacci sequences. Write a method (or pseudo code), that generates the Fibonacci sequences.
-
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
-
#### What is “Stack overflow”?
- 
#### What are the main parts of a function?
-

### Programming languages - Python  
#### How do you use a dictionary in Python?
- Kapcsos zarojellel / "{}"
#### What does it mean that an object is immutable in Python?
- Create the object and assign some value to it, you can't modify that value.
#### What is conditional expression in Python?
- 
#### What are different types of arguments in Python?
- default arguments.
- keyword arguments.
- positional arguments.
- arbitrary positional arguments.
- arbitrary keyword arguments.
#### What is variable shadowing? (context: variable scope)
- When a variable "hides" another variable with the same name. 
#### What can happen if you try to delete/drop/add an item from a List, while you are iterating over it in Python?
- 
#### What is the "golden rule" of variable scoping in Python (context: LEGB)? What is the lifetime of variables?
- Understandable names. 
#### If you need to access the iterator variable after a for loop, how would you do it in Python?
- 
#### What type of elements can a list contain in Python?
-
#### What is slice operator in Python and how to use?
-
#### What arithmetic operators (+,*,-,/) can be used on lists in Python? What do they do?
-
#### What is the purpose of the in and not in membership operators in Python?
-
#### What does the + operator mean when used with strings in Python?
-
#### Explain f strings in Python?
-
#### Name 4 iterable types in Python!
-
#### What is the difference between list/set/dictionary comprehension and a generator expression in Python?
-
#### Does the order of the function definitions matter in Python? Why?
-
#### What does unpacking mean in Python?
-
#### What happens when you try to assign the result of a function which has no return statement to a variable in Python?
-

## Software engineering

### Debugging

#### What techniques can you use while debugging a program in Python?
#### What does step over, step into and step out mean while using the debugger?
#### How can you start to debug a program from a certain line using the debugger?

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
#### What are the basics of exception handling in Python?
#### In which case should we catch an exception? Why?
#### What can/should we do with an exception in the ‘except’ block?
#### What does the else and finally statement do in a try-except block in Python?

## Software Development Methodologies

#### What is the main goal of a retrospective meeting?
- A Retrospective is a ceremony held at the end of each iteration in an agile project. The general purpose is to allow the team, as a group, to evaluate its past working cycle. In addition, it's an important moment to gather feedback on what went well and what did not.

## Programming environment

### Unix

#### What is UNIX and what is Linux?
#### What do we call the shell in Linux?
#### What does root means in a Linux environment?
#### How do you access your personal files in Linux?
#### How can you install an application in Linux?
#### What is package management in Linux, what are repositories?
#### How do you navigate in the filesystem with the command line?
#### What does the following commands do: mkdir, rm, cat, cp, touch?
#### How can you look up what does a command do in Linux if you have no internet connection?
#### What does the following commands do: head, tail, more, less?
#### How do you download a file from internet using the terminal?
