# Intro to Programming for Data Science (with Python)
16wk
don't underestimate students but also don't waste their time
16wks is plenty to learn a ton of skills and get pretty good if taught well



### Things to cover

 - how to navigate a file system and write simple code like a programmer
 - how to write new code (how to read code documentation, how to google code, how to apply others code to your 
own work, how to prompt language models like GPT for code and how to use that)
 - how to use git for version control, collaboration, sharing, finding useful code, documenting, and as a 
portfolio
 - 



 - download: python, git
 - why to use a folder for every project
 - how to use git, git init, commit, push, clone
 - how to navigate file structures
 - what are numbers in memory, what is a float
 - why is it relevant? quantization is extremely important for the future of models which the basics comes 
from how numbers are stored in memory
 



lessons are emphasized on interactivity, students can read the content or watch videos on their own, i will 
not be reading off powerpoint slides or reading off notes, students will have the structure for the entire 
course beforehand and are welcome to create their own slides or notes, but note.

"reverse classroom" where content is learned at home and practicality is learning in class.  normal class 
rooms teachers read off notes, slides, lecture and then send you home to do the work where you go home and 
spend hours trying to figure out the system or debug simple code that you could have easily learned from an 
expert or professor.  idealy students can do the bare minimum and read a good article or watch a good youtube 
video that takes ~30min and that gives them some context to be able to do basic practicle things in class.

weekly debugging office hour session. instead of students coming one at a time for office hour questions.  
any students, with or without questions, can come and learn how to fix the various bugs that students have run 
into and they themselves are likely to run into at some point.  

it can be tempting to teach what an expert would consider "basics" but should be cautious to waste time on 
"basics" that won't make any sense until much further down the line.  should not spend the first 8 weeks 
learning theory or concepts and then start appling them towards the end of the semester, should start 
applying as soon as possible.  the more time spent writing code provides more opportunity to run into the 
early problems and bugs.  it also makes both the content and code easier to relate because as you learn more 
advanced content you can see how it comes together, literally in the building of the code.  

when you start dtypes seem unimportant 
and trivial when their importance becomes clear later.  if i tried to learn dtypes, floats, fp16, earlier it 
wouldn't have made any sense because nothing to relate to, learning about them now is easy and rather 
enjoyable because i understand the value of learning the underlying details.  

lesson 1: 
 - how the class works, "reverse classroom" instead of learning content in class and trying homework; learn 
content on own for homework and learn how to apply the concepts in class
 - the expectation is to write code in every single class
 - recommended reading and/or video content will be provided and act as homework
 - open class format, curriculum, content, everything will be kept in a git repository and can be read at any 
point
 - all students work will be posted to their individual git account, students will fork each assignment, 
complete the work, and submit a pull request once completed; lots of school notes lost in old notebooks or 
files; using a git repo makes it extremely easy to refer to at any point in the future
 - 2 assigments per week, one content focused and one practical focused
 - 1-2 weekly code review sessions during office hours; group session for students to come and show bugs they 
ran into to get help fixing, nearly every bug will be seen by every programmer at different points, so instead 
of going to individual office hours and getting the answer to 1 bug you can go and get the answer to 5 bugs 
you didn't even know could happen




example lesson 2: what is in your computer, navigating your file system from terminal
 - everyone creates a folder on their desktop called 'python_data science' and any work done throughout the 
class should be in the folder, including notes, code, assignments, 
 - everyone open terminal
 - your entire computer is a big file system that can be quickly navigated through your terminal
 - pwd / cd / ls / mkdir / cd - / cd ~
 - - cd ls cd ls cd ls
 - navigate to your class folder and git clone https://classrepo.github.com/
 - - will go over how to use git in more detail later
 - might seem backward to teach venv before teaching python but as long as they know how to env they can go 
crazy with installs and trying whatever they want out without breaking their computer
 - python3 -m venv env
 - - how to create a env in your project folder
 - - how to start your env everytime you go to your project folder
 - - why you want to install your dependencies in env
 - - i learned the hard way, breaking my computer with bad installs until i just buy a new computer, you don't 
have to do this
 - requirements.txt for all projects
 - what is markdown, how you can use .md to write notes for this or any class



example lesson 3: 
 - every class should be started with student opening terminal, pwd, ls, cd desktop, ls,  cd 
python_data_science, ls, source env/bin/activate(env/Scripts/activate)
 - ways to write python code
 - - python straight from the terminal 
 - - write hello_world in notepad
 - - nano hello_world - good for writing scripts or programs quickly and for simplicity
 - - vim - mention only. 'hardcore' programming, very steep learning curve but high returns for people who 
write a lot of code
 - - jupyter notebook - most common for data scientist, best for doing processes one at a time, or creating 
plots
 - - vscode 
 - - - vscode is what most will use, pros are lots of functionality for programming, cons so much 
functionality leads to more problems you can come across, for the sake of learning python we will mostly use 
nano for writing files or a notebook 


example homework1: 
 - open your terminal
 - on a piece of paper, write down the initial pwd of your terminal
 - on the piece of paper write the minimum number of lines to get from terminal open, write hello world file, 
and print hello world in your terminal. hints: ls/pwd don't count towards the total lines but every other 
line you enter in both the terminal and the python file count. starting with mkdir. the new dir should be a 
folder like 'week 1' within your 'python data science' folder   

answer:
1. mkdir week1
2. cd week1
3. nano hello_world.py
4. print("hello world")
5. python3 hello_world.py

example lession 4 (week2):
 - source env/bin/activate 
 - pip install numpy pandas
 - python basics, you can + - * / ^
 - variable assignments, create a set of numbers and do some math
 - example list: 60 students grades, highest/lowest grades, average, apply a curve
 - how to do calculus: derivatives
 - how to do linear algebra: matrix multiplication
 - how to apply calculations to a set of numbers with for loop


example lesson 5 (week2):
 - at this point have a habit of creating code files, using a virtual environment,  
 - how to write harder code, which requires being good at reading code
 - how to read code, enough to understand the basics of someone elses code
 - basics of functions and classes
 - how to read documentation
 - create a map of function calling, example, whenever you np.array, look in the numpy documentation and read 
the array function and what it does





 - if data science is to statistics, then machine learning is to calculus
 - rate of change = slope = gradient
 - data science teaches you regression is done through averaging(in simplistic terms)
 - machine learning teaches you regression is done through  gradient descent
 - the biggest differentiators between data scientists and machine learning engineers are terminology and 
coding ability




 - how to get your data
 - what is wget
 - - read csv
 - - pd.read_csv
 - basic processing, isnan, repeating, simple statistics
 - how to split data into train/test or train/val/test
