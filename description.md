# UC approval for *Intro to Computer Science and Coding* at CVHS

## Course Title
Intro to Computer Science and Coding

## Brief Course Description
This course provides a comprehensive introduction to software design concepts through the accessible and powerful language Python.  Students solve problems and design projects spanning topics such as data structures, abstraction, data serialization, search algorithms, encryption, and object oriented design.  Good habits, such as revision control with Git, are also be practiced.  Students present work to their classmates at various points throughout the course.  Students choose a final project to develop.  This course provides a solid foundation for further study in computer science.  Beginners and experienced programmers are welcome.

## Prerequisites
Completion of Algebra I

## Textbook
#### Title
Python Programming in Context
#### Edition
2nd
#### Publication Date
Jan 24, 2013
#### Publisher
Jones & Bartlett Learning
#### Author
Bradley N. Miller and David L. Ranum
#### URL Resource
* https://classroom.github.com/classrooms/31190613-cvhs-cs-cte


## Supplemental Instructional Materials
Custom instructional materials are generated and hosted on GitHub.  All textbook exercises will be hosted in by-chapter repositories on GitHub.  Students will be presented with exercises from each chapter, already compiled in a private repo, with a testing suite in most cases.  https://github.com/KJHS-Coding. Students will work in 20-30 repos throughout the year.  Links to supplemental youtube videos will also be provided.  Students can access online exercises - CodeLab - using an access code from the textbook at www.jblearning.turingscraft.com.  CodeLab will be primarily a remedial tool for students seeking extra practice with syntax and concepts.

## Course Purpose
This course is designed to be an introduction to computer science from a high-level perspective.  The course is taught with Python, a fully-featured high-level language.  Rather than emphasizing low-level skills such as the implementation of data structures, students will use data structures in Python’s standard library to solve more interesting real-world problems.  This will provide a much clearer context for further study in AP Computer science and beyond.

This course also teaches the use of Git and GitHub - popular, modern technologies that are used in the real world.  The learning outcomes of GitHub are manifold.  Students will learn how to manage source code repositories of increasing complexity, gain experience with a command line interface, learn tools that could help them in further study and industry, and learn how to effectively collaborate with other developers.

Students come to view computer science and coding as not only a technical field, but a creative endeavor as well.

## Course Outline
### Semester 1

#### Unit 0
Getting set up with the necessary tools for further work in the course: Python 3, Text Editors, Git, GitHub, and command line execution of programs.  Bare-bones introduction to Python with an emphasis on familiarization with workflow and syntax.  Big concepts are shallowly introduced in anticipation of spiraling; ‘Hello world’, integer and string data types, user input, and functions.  A field trip to a local computer history museum puts computers and technology in a larger context for students.  Students complete a research project on one facet of computer technology, describing how that facet has changed over time.

#### Unit 1
Students learn to work with data types and assignment.  This unit begins with Turtle objects from the Python standard library.  Turtles draw on a canvas window with simple commands such as Turtle.forward(50), Turtle.left(90), etc.  Turtles feature public attributes such as line and fill color.  Students implement scripts, loops, and functions to create sophisticated and colorful drawings.  Programming is experienced as a creative, artistic endeavor in this first major part of the class.  Students also begin using methods (of Turtle objects).

The unit continues with exercises in approximating pi, using various methods.  Using the accumulator pattern in a variety of contexts, students see design patterns for the first time.  Students apply the looping methodologies from their work with Turtle objects to realize the accumulator pattern.  Students work with boolean expressions, returning values from functions, and selection statements.

Students use the math module and the random module from the Python standard library when approximating pi.  Students  approximate pi using the perimeter of n-gons for increasing n, using partial sums of infinite series representations of pi, and using random numbers in a Monte Carlo method.  Tangible code and algorithmic problem solving contextualize abstract mathematical concepts such as limits and probability.


#### Unit 2
In-depth exploration of string methods and text processing through the lens of cryptography.  Students have already worked with the string data type in Unit 0. New concepts include concatenation, repetition, indexing, and slicing of strings.  Students write simple ciphers for encrypting larger strings of text.  Students will create rail fence ciphers, substitution ciphers, and vignere ciphers in this unit.  Thinking about cryptography in the real world, students explore hash algorithms such as md5, sha1, etc., and their application in web security.

Tasks of this unit include reading and writing files for the first time.  This is an example of how difficult concepts can be highly scaffolded through the use of GitHub.  Starter-code pushed to student repos, containing callable functions that read and write files, introduces students to the power of serializing data.  Students use a number of Python's built-in functions to handle reading and writing files for themselves in the next Unit.

Encryption/decryption describes abstract mathematical concepts such as inverse functions from a different perspective.  “Brute-force” algorithms are discussed for cracking a cipher.  “Smarter” approaches are contrasted with brute force to deepen student understanding.

This unit strongly reinforces concepts of abstraction as students write methods that encrypt and decrypt strings of text.  Students also learn many ways to parse text and work with individual characters, including ASCII and the concept of character encoding.  As student work moves more towards writing functions and less towards writing scripts, testing suites are included in students' starter-code to help them progress efficiently through projects.

#### Unit 3
Beginning with an introduction to Python’s high-level data structures, this unit provides a thorough introduction to data analysis with Python.  Students use lists, tuples, and dictionaries to solve various problems in data analysis.  Students learn design patterns using dictionaries to count and sort data sets.  While key-value pairs are easily understood in contrast to array-types such as lists and tuples, their utility in counting/sorting is a much deeper lesson and of high importance in this unit.

Students will be introduced to simple sample statistics - mean and standard deviation - and implement their own methods for calculating them.  The turtle module from Unit 1 will be used to draw histograms from data sets, and students will abstract methods for producing histograms.  This will be a good lesson in which to reflect on the significance of abstraction in making code flexible, reusable, and terse.

The unit continues with concepts of data analysis to delve more in depth into reading and writing files as a way to manage large data sets.  Introducing while loops, exercises include: reading files of data, performing some kind of conversion or analysis by row, and writing results to a file.  Python’s easy-to-use urllib module allows students to access web-apis directly from Python.   Students can access web apis to explore stocks, meteorological data, transit organization data, and social networking data.  Basics of http requests can be introduced, as well as web scraping.  JSON is a widely used format for web data, and students will have already worked with JSON in the last unit.

#### Optional Unit
Students ahead of the class will have an opportunity at this point to explore any topics from chapters 6-8 in the text.  These chapters are optional from the perspective of the text authors, and extend some of the earlier concepts through explorations of image processing, advanced cryptanalysis, and advanced statistics and data mining with cluster analysis.

### Semester 2

#### Unit 4
Beyond factorial functions and fibonacci numbers, this unit provides deep introduction to recursion and functional programming styles.  Students will again use the familiar Turtle objects from Python’s standard library to draw Koch curves and L-systems.  Students will learn about grammars and production rules by using the string-parsing techniques developed in previous units to instruct a Turtle to draw.

Classic recursive exercises include the factorial function, fibonacci numbers, finding the min or max of a list, reversing the characters of a string, and casting arbitrarily-nested lists of strings as integers.  For example, ['1',['2','3'], ['4', ['5']]] is a list of strings that can be cast as integers with a recursive function.

More advanced topics in L-systems are explored.  Having worked in-depth with string parsing in unit 2, students will focus on understanding the concept of production rules.  Drawing the results with a Turtle object makes these exercises tangible and exciting.

Advanced students are supported in drawing fractals arising from Newton’s Method for finding roots of polynomials, as well as the Julia Set and Mandelbrot sets.  To explore these fascinating topics, students need a basic handle on complex numbers.  These more advanced techniques for generating fractals will be strong reinforcement of recursive patterns.  Advanced students also have the opportunity to explore Numpy, a Python library for doing the fast array calculations necessary for generating high resolution fractals, and Matplotlib for creating images.

Students showcase their work at the end of this unit to the rest of the school.  Fibonacci numbers and L-systems closely model natural processes, in an aesthetic way.  Again, creativity and aesthetics show up in computer science, this time in a very technical and algorithmic way.

#### Unit 5
The largest and most consummate of the semester, this unit introduces object oriented programming in Python. Students have been using turtle objects and their methods, as well as string, list, and dictionary methods, up to this point.  The concepts and syntax of using objects will already be firmly established and provide for a highly scaffolded entry into writing classes.  The turtle module will again be used to animate a simulation of orbiting bodies and a simulation of an ecosystem.  The turtle module allows for the import of image files as sprites, adding some fun and variety to animations.

Students will model solar systems with a solar system class and a planet class.  The simulations will assume a fixed sun and Newton’s law of universal gravitation to model orbital behavior.  Through this implementation, students experience a natural introduction to classes as containers for data and the methods that act on that data.  Planets, for example, will have instance variables such as radius, distance from the sun, and mass, with methods for calculating volume, density, gravitational force, etc.

This simulation is of a star with many planets.  Students use the planet class as a template for all of the planets in the simulation.  This makes the reason for using a class apparent.  Through building the solar system class, students see objects as convenient tools for organizing complex programs.  Through experimenting with constructor arguments to set things like mass, radius, or the gravitational constant, students appreciate the level of abstraction a class provides.

The planet and solar system classes will have methods for stepping the simulation in time.  Planet objects have position, velocity, and acceleration properties.  Those are used in an Euler method in the solar system class to step the simulation.  This lays groundwork for the much broader concept of numerically approximating solutions to differential equations (though, students need only an understanding of Algebra, rates of change, and Universal Gravitation to experience full success in this unit).  Through animating the simulation with Turtle objects, students visualize their work.

After modeling solar systems, students do a different kind of simulation which incorporates randomness.  The project involves simulating a simple ecosystem with bears and fish on a world grid.  In each iteration of the program's main loop, every animal object will decide wether to move, eat, reproduce, or do nothing according to some conditions and random number generation.  Students then let the simulation run and observe long term behavior.  While the solar system simulation was very deterministic, classes in this simulation contain much more conditional logic to model nuanced behavior.  Because fish and bear classes contain some overlap, the stage is set for introducing inheritance.

#### Unit 6
Although getters and setters are not a part of Python culture, properties and encapsulation will be taught in this unit.  More advanced object-oriented design concepts are explored, with a particular emphasis on inheritance.  Students explore inheritance through the creation of geometry classes and an associated canvas class for visualizing geometric objects.  The geometry classes begin with the point and line primitives and unfold into various classes of polygons, circles, and ellipses.  All objects inherit from a base class containing attributes of line-thickness and color characteristics that the canvas object interfaces with.  All of this sets students up with an API for drawing on a canvas with lines and geometric shapes - an API built by them.  Advanced students have the option of using tkInter, the cross-platform windowing system in Python's standard library, to create an event-driven GUI drawing program using their code.

As an exercise in this unit, students return to their ecosystem simulation to refactor the code using inheritance.  There are multiple living things beyond bears and fish in the simulation, after students complete the key assignment from unit 5.


## Key assignments

Each unit has at least one major deliverable/software artifact in which students demonstrate their mastery of the skills and concepts developed in that unit.  Many smaller exercises, from the textbook and elsewhere, are assigned in support of these major assessments.

__Unit 0 - Research Project__
Students prepare a slideshow, choosing some aspect of computer hardware or software, and researching how it has changed over time.  Students will present their work in a three-minute lightning talk format.  The purpose of the assignment is to educate peers on an interesting facet of computer history, architecture, or culture.

__Unit 1 - Turtle Doodle__
Students create a drawing using the turtle module.  The drawing should contain multiple colors, fill patterns, several loops, and at least one nested loop.  The assignment is exploratory, and the assessment is of the students ability to handle assignment, iteration, and passing arguments to the Turtle methods.

__Unit 2 - Cootie Catcher__
Students model a cootie catcher, also known as a paper fortune teller.  The program requires a main loop, waiting for user input, interpreting input, and displaying output to the screen.  This project solidifies selection statements, loops, and functions.  To take things a step further, students will make their cootie catchers configurable by loading all of the required data from a JSON file.  Students then swap out, and/or share JSON files for an entirely new cootie catcher.  The program can be animated with text output to the terminal, or with Turtle objects for more ambitious students.

__Unit 2 - Secure Login (advanced/optional)__
Advanced students have the option of writing a program that models the saving of passwords in a database. Instead of working with an actual database, students read and write JSON files.  A website should never save a user's raw password in a database.  Instead, a program hashes the user's password before saving it.  When someone attempts to log in, the password is hashed using the same algorithm and compared against stored hash.  Students must use a common hash algorithm such as md5 or sha1, available in Python's standard library.

__Unit 3 - Sorting__
Students use associative arrays ("dictionaries" in Python) to sort and count data sets.  The project repository can be seen at https://github.com/KJHS-Coding/Sorting.  One part of the assignment involves sorting through and counting 20,000 different colors, each representing a crayon selected from a standard box of 8.  Students then look at the distribution of colors and make a determination as to which color is diminishing from the population of crayons.  Students should use their histogram-drawing abstractions from this unit to do the analysis.

The second part of the project involves parsing text from Isaac Asimov's _The Last Question_.  The repo above contains a raw text version of the story, which is now in the public domain.  Students use a dictionary to sort through all of text and group words by letter-length.  This task also involves parsing text to remove punctuation and capitalization.

These exercises reinforce some common and powerful design patterns/algorithms for sorting data with associative arrays.  Advanced students may be introduced to more "Pythonic" idioms such as defaultdicts and list comprehensions.

__Unit 3 - Web Scraping (advanced/optional)__
Students used urllib from Python's standard library in this unit to gather data from the internet.  In this open-ended project, students explore some basics in web scraping to answer a question or solve a problem that is interesting to them.  Alternatively, students may access a web-api instead of parsing raw html to collect data.  Possible topics include data harvesting and web-crawling.

__Unit 4 - Patterns of Nature__
This art-oriented project uses one or more of the methods for fractal generation covered in this unit.  Students use what they have learned to make an image suitable for an art exposition at school.  Students should reuse abstractions developed while completing exercises in L-systems, Koch curves, and other fractal explorations from the unit.  Students will superimpose their fractals on an image of their code, with guidance from the art department in using Adobe Photoshop, working with color theory, and using the elements and principles of design.

__Unit 5 - Improved Simulations__
The textbook guides students through two major simulations in this unit; a solar-system simulation and a predator-prey simulation.  Students made some simplifying approximations about how gravity works and how animals mate.  The task of this project is to take one or both simulations and add improvements to the model that more closely reflect reality.  For the solar system project, this may include an n-body model instead of a fixed sun at the center.  For the biological model, students can introduce another animal or plant into the simulation, or improve upon the politically correct mating model outlined in the text.


__Unit 6 - Final Project__
Students choose a final project of their own to design and develop.  The requirements of the project are that it uses multiple classes and some form of inheritance to achieve the goal.  Students may choose to develop a simulation, game, utility, piece of art, or anything else that can (should) be achieved through object oriented design.  Students will be assessed on their competence in writing and using classes.

## Instructional Methods and/or Strategies
Course content is presented in the form of lecture, video lecture/demonstration, and readings from the textbook.  All student work for the course happens in private repositories hosted on GitHub.  Student and instructor are able to have private, threaded conversations, referencing specific lines of code and using markdown.  For each project and each chapter from the text, students have a private repository assigned to them with starter code.  The started code will, in many cases, include tests that the students can run to help them develop their software artifacts.  GitHub issue tracking is used by the instructor to open issues as waypoints for students, guiding them in the major steps necessary to complete sophisticated projects.

Most of the exercises from the textbook are completed throughout the course, except for several optional chapters that will be skipped.  Students are provided with private repositories, by chapter, with questions from the text already included as docstrings.  This allows for rapid progression through many exercises.

In some cases, students work in pairs or groups.  GitHub is designed for this kind of collaboration.  Instructors can view contributions of each student, statistics on the number of lines and frequency of their contributions, and a full history of commits.

Documentation is a requirement for all projects.  This means using inline comments, as well as creating README files to accompany artifacts.  See the rubric for projects.  Making documentation a requirement develops academic literacy.  Students think about what they are doing, why, and how to succinctly communicate intent to other people.

## Assessment Methods and/or Tools

### Tools
#### Github
Students produce many software artifacts throughout the course.  All artifacts are handled through GitHub.  Private repositories are created for each student, or team of students in some cases, with the instructor added as a collaborator.  All projects will include boilerplate starter-code written by the instructor. This provides scaffolding for the concepts and a framework for students to test their code.  All repositories will also include a readme file with clear instructions, links, background, and suggestions for further reading.

Students can request assistance through GitHub’s issue tracking.  They can open an issue and have a threaded conversation with the instructor, referencing specific lines of code with GitHub’s built-in features.  Students never have to email code, use a thumb-drive, or be restricted to one machine when working on their projects.  Instructors can also open issues in a project repository as a way to set assignment waypoints.

Git(hub) tracks commits so that the instructor can monitor progress, review history, and have data and statistics on lines contributed when students are working individually or in groups.

Github is a vital assessment tool because it allows for the instructor to rapidly access student code in an annotative and conversant way.  That also makes it a vital teaching tool.  Pushing starter-code for students, and raising issues as waypoints, allows for rapid movement through content and solutions to interesting problems.

### Methods

#### Tests
Students take a multiple choice/free response test every unit assessing understanding of syntax, design, and concepts discussed in class.  Students will predict the output of code and explain syntax errors.  Questions are modeled after AP CS A questions, tailored to the language and content of this course.

#### Projects
The majority of assessments will be in the form of projects.

#### Project Rubrics
* Assessment of projects follows 5-point rubrics in three categories:
    * 50% Content
    * 25% Documentation
    * 25% Commit Practice

* The **Content** category assesses the technical correctness of a student’s program.
    * __5__ All programming tasks were met with correct algorithms applied.  Code is free of errors - programatic and syntactic.  Abstraction makes code efficient and easy to read.
    * __4__ Most programming tasks met with correct algorithms applied.  Or code has one or two programatic errors.  Or code has repetitive blocks and not sensible abstraction.
    * __3__ Not all programming tasks met.  Or code has many programatic errors.  Or code has any syntactical errors (i.e. does not run).  Or code severely lacks abstraction.
    * __2__ A few programming tasks were met with some success.
    * __1__ One or two programming tasks met.

* The **Documentation** category assesses the practice of code documentation.  This includes comments, as well as README files for software artifacts.  Good documentation develops academic literacy.
    * __5__  Code has excellent comments where needed - concise, helpful, and not redundant.  The README file gives clear, grammatically correct instructions for using the code base.
    * __4__  Code has excellent comments.  Redundant comments describe code that is unmistakable in meaning.  Or excessive comments detract from overall clarity.
    * __3__  Code has substantial commenting.  Documentation lacks a critical features that a developer should know about to maintain the code base.  Many redundant or excessive comments.
    * __2__  Code has few comments.  Or multiple key features, complex statements, or other critical parts of the code are not well documented.
    * __1__  Code has almost no comments.

* The **Commit Practice** category assesses the use of Git and code revision.  Commit Practice relates to documentation, in some ways.
    * __5__ Repository contains many commits.  Clear commit messages describe changes or additions to code.  Overall, commits contain running - not breaking - code.  Commits represent logically discrete steps in problem solving.  The practice of branching separates major changes and parallel development - such as when collaborating - in a controlled way.
    * __4__ Repository contains many commits.  Some commit messages lack clarity or meaning.  Or many commits contain code that does not run.
    * __3__ Repository contains fewer, larger commits.  Commits represent large steps of progress.  Or too many smaller commits are made that should be combined.  Or many commits contain code that does not run.
    * __2__ Far too few commits for a large assignment.
    * __1__ One commit.

#### Presentation
Twice per semester, students are required to present a summary of recent work in three-minute slideshow form.  This develops public speaking skills, digital document presentation, and academic literacy.  Presentations are graded on a five-point rubric.
* **Presentations** assess use of academic language and basic public speaking skills.
    * __5__ Presentation lasts between 2:45 and 3:15 minutes.  Work is presented clearly.  Academic language is used appropriately.  Slides are supportive of the overall presentation.  Slides are generally attractive and well-organized.
    * __4__ Most of the requirements for a __5__ are met but presentation is outside the desired time range.  Or presentation leaves out important background information so as to be unclear.  Or academic language used incorrectly.  Or slides are designed poorly.
    * __3__ Topic is clear.  Academic language is absent.  Or presentation is very rushed or unclear.
    * __2__ Presentation lasts for a minute or less.  Or slides do not support presentation in any way.
    * __1__ Presentation is attempted.



#### Assists
Outstanding acts of altruism will be reward with extra credit points on a three-point scale.
* **Rubric**
    * __1__ Help another student to progress in the class.
    * __2__ Help another student, without expectation of reward.
    * __3__ Help another student, without expectation of reward, in a way that teaches them to help themselves.


