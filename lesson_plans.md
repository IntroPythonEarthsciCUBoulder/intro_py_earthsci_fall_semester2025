# Lesson plans for GEOL 3600, fall 2025

## Class 1: introduction and overview

### Main topics

- Introduction to course
- Basics of computers: bits and bytes
- Programming languages, and Python
- How to log onto JupyterHub
- Basics of notebooks: markdown, code, LaTeX
- Quick overview of earth history (for coming exercise)

### LP

- Initial hello, ask them about temperature outside, age of earth, speed of tectonic plate; point out nature as numbers; slide with 3 examples
- Introduction of instructors (optional: ask students about their motivation to be here, ask about coding experience) (5 min)
- Mini-lecture on computing in geoscience (10 min)
- Intro to course and syllabus (10)
- Intro to notebooks (5)
- Ex: log on to lab computers, then onto J-hub; sort out any issues (5)
- Overview of the Lab environment: file browser, tools, tabs window (5)
- Overview of J notebooks (5)
- Open daily notebook and do exercise of name, date, note to self about the Python print() function, and hello world (5)
  - Directions: make a new notebook, give it a name that includes today's date.
  - Make a text cell that has a 1st-level heading "Getting started", name, and date
  - Make a new text cell, give it a 2nd-level heading "The Python print() function", then write a note to your future self about what the function does.
  - Make a new code cell with a print("Hello, world!") and run it
- Live guided exercise on LaTeX math, with inline ($g=9.8$ meters per second squared) ($\pi$), own line ($$A_c = \pi r^2$$, $$A_s = 4 \pi r^2$$) (10)
  - Make a new text cell with the 2nd-level header "LaTeX math"
  - Write some expressions or equations, including at least one subscript, one superscript, and Greek symbol, one fraction, and one square root. Include at least one example of an inline equation, and one example of an equation on a line by itself.
- Optional: mini-lecture on geologic time by powers of ten (10)
- Wrap up and recap (5)

POST-NOTES:
- only got up to initial markdown experimentation, and a very quick hello-world


## Class 2: operators

### Main topics / goals

#### Computing


- Use **operators** to do mathematical calculations
- Understand how computer data are organized using **files** and **folders**
- Navigate among folders using a **UNIX shell** (otherwise known as a *terminal*)
- Learn how computers represent numerical data

#### Geoscience

- Define solar irradiance and albedo
- Identify the Stefan-Boltzmann law
- Use the Stefan-Boltzmann law to calculate the effective radiating temperature of earth given irradiance and albedo


#### POST NOTES

- only got up to showing the equilibrium T equation; didn't have time for them to calculate solutions, or to cover shell commands


# Class 3: variables and data types, part 1

Main goal is to introduce variables and types, dynamic typing, and the type() function.

Introduce int, float, str, and bool. If time, get people familiar with string indexing and slicing.

Starting the planetary props ex near top of hour, ie, 55 min in

Got up to, barely, booleans, and didn't cover comparison ops except briefly ==

I did show them %whos and how to restart kernel

When we did the ops warmup, lots of mistakes with parens - many are just starting to get the idea.

I thought they would recognize the Te equation from GEOL 2001, but got mostly blank looks. Do they still cover that? Did they just forget?

I kind of sense that precise thinking comes naturally (?) to a few, but most are kind of shooting in the dark.

Overall, this group feels bright and engaged, but I have to remember that they are still young and learning; even things that I might have taken for granted that they knew, like whether Mars is closer or farther from Earth, they don't necessarily know.

I sense they need more practice, and probably less time listening to me... though I suspect a few get it right away and are ready for harder material. Having "extra credit" extensions on assignments, and generally optional extensions on in-class work, would be good for those folks. Like have a "If you have more time" section for the in-class exercises.

A check-in wouldn't be a bad idea, like a mentimeter anonymous question on pace is too slow, too fast, or about right.



# Class 4: more vars and types

- finishing comparisons at t+15
- I set them loose on the first Calwood exercise at 10:10, and that's where we ended at 10:20



# Class 5: Working with modules and functions; getting help

This was to have been the first of two sessions on functions, plus we ran out of time Monday and so still need to cover list indexing and dicts. (And tuples and sets.) So instead of working on in-class notebook number 5, we had them work on and turn in a notebook of basic exercises that Jo wrote, and then they worked on Code Paper #1. I flipped this class and recorded the material.

Lesson Plan:
- 5 min intro / review
- 20 min exercises that Jo is making
- 5 min intro to code paper; remind about llms
- 40 min work on paper (turned out to be more like 30 min)
- 5 min regroup

Recorded for them view before Monday:

- list indexing and slicing
- dicts
- tuples and sets
- working with functions (using 05_working_with_functions)
- importing modules (same notebook)

People here today: 11 out of 16



# Class 6

Post-notes:
- About 10 people there
- Walked through a notebook on functions, with alternating presentation and hands-on exercises
- A fair amount of confusion / uncertainty over syntax, plus the usual notebook "hidden state" issues (like redefining the print() function as a variable)
- Got up through docstrings, but not the in-class exercise with them




Class #7: branching

- General questions on coding paper?
- Work through notebook on branching, pausing to do in-class exercises
- Reserve at least 20 min at end to have them work on paper

post-notes:
- got up to but not including the gaging station stuff
- spent a while going over the concept and math behind question 3 on the current code paper, where b and c ask them to find greenhouse magnitude or albedo such that Tsurface remains at the freezing point. They were confused about how to set this up.
- there's still some confusion about functions, and in particular about passing in arguments: why does the parameter have a different name from the input?
- syntax is still a challenge for some people
- generally the branching stuff seemed to go ok
- people want more practice time
- I did cover "not" (in response to a question)
- Did not cover nested ifs, one-line ifs, or pass

Assignment 1:
- Biggest point of confusion is around 3b and c, which deal with finding either a dT or albedo such that early earth T ~ 0C


Class #8: loops

Once again, WAY slower than I'd planned. I had meant to have this schedule:

0-15 min introduce for loops
15-30 min practice for loops
30-45 min introduce while loops
45-60 min practice while loops
60-75 min introduce background for next assignment

Instead, I found I was still talking at :30 past the start. We let them loose on the for loop exercises, and there was a lot of confusion about setup and syntax, i.e., this was not an easy one for everyone. Then Jo gave an impromptu presentation on using a loop and a function together. Then I went back and showed a solution to the first practice problem, and we were out of time.


Class #9: practice session, while loops, and very quick intro to numpy

...to be supplemented by videos...

- Ice cores and next assignment quick overview (as motivation)
- Jo's practice NB
- While loops and one quick exercise
- Work on 1st problem on paper
- 10 min intro to numpy with videos to follow


During/post notes:
- dang, I really do tend to go slowly: Jo is starting at :25 past the top, instead of the 10-15 I intended!
- plus I forgot to point them to today's notebook name on canvas
- Jo is showing how to use the debugger, and then a review notebook.
- From their work on the review NB, it's clear there's still a lot of confusion about how to write and use functions. Maybe they didn't watch the video... that's the downside of videos
- Maybe better in future to do IF and loops before covering functions


Class #10: Numpy and matplotlib

- about 1/3 of the class is on field trips this week...
- so, whatever notebook we do should be comprehensive

LP:
- housekeeping: extension


Class #11: reading data from text files

- Two Python package presentations
- Questions on current code assignment?
- Go through in-class notebook #11

- post-notes: this topic is BIG. Either have to scale back or spread over 2 classes.
- one idea would be to very quickly introduce read(), readline(), and readlines(), don't bother with split(), and then get right to loadtxt() and savetxt()

- there's still a lot of confusion over syntax, and just a need to get accustomed to "thinking in python"

- also, i forgot to record the class for the field trippers

- and when i use external files, those files have to be accessible to the students


Class 12: introduction to Pandas

- started with showing how to run code in python console, and through a .py file
- did some impromptu q&a around the current assignment
- got through the "manipulating data in a dataframe" bit of the notebook, but not beyond (and this was with no breaks for do-it-yourself exercises)


Class 13, 8 Oct: more on pandas

- because we didn't get that far last time, I used this class to carry on with pandas, using notebook "12b"


Class 14, 13 Oct: gridded data

- jumped to notebook "14" on gridded data with DEMs as an example
- as usual, didn't get to the end
- got up through the in-class practice on writing a function to calc and return slope and using it to plot a slope map for the Boulder 1x1 degree NASADEM box.


Class 15, 15 Oct:

notebook 15_ImageAnalysis.ipynb

Lesson plan:
- go over assignment 2, showing solution to #5
- discuss CO2 measurements
- questions on current assignment?
- pass by value vs. reference
- contouring and hillshade
- intro to RGB images
- quick overview of next assignment


Post-notes:
- basically got through it all, but had to rush on the "do it yourself" bits
- didn't have time to have them work on the next assignment in class, or even to do much by way of introducing it

Couple people are going to GSA, so I told them to just do the notebooks when they can (I'm going to, leaving after class Monday; Jo will do some practice with functions and such next Wed)

In general, I get nervous and talk too much - need to slow down and allow time for hands-on practice.


Class 16: 20 Oct

LP:
- Plan for the day
- Garrett Py package? (somehow missed Wed)
- Q's on current assignment?
- Quick look at type hints
- OOP
- if time, work on assignment


Class 16b: 22 Oct

Jo did a review and practice session to help people improve their understanding of syntax and especially of functions.



Class 17: 27 Oct - numerical modeling part 1

This ended up being entirely taken up by me showing them how to derive an ODE using mass balance, with the example of a lake. We didn't get to any coding, and only briefly touched on numerics (finite difference) at the end.


Class 18: 29 Oct - modeling part 2

- We looked at the steady solution to the lake problem, and I had them write a code with numpy to calculate and plot how steady lake surface area varies with evaporation rate, all else being equal. They spent a few minutes but then I brought them back and we did it together.
- I gave what I hope was an intuitive intro to finite differencing, starting with the idea of extrapolating a rate out to 10 years (not very accurate) ...
- ... then extrapolating for just one day (more accurate but not very useful) ...
- ... then day-by-day for a full week (reasonably accurate but still not all that useful) ...
- ... ultimately to the idea of going day-by-day for 10 years
- Then I reviewed the "math-y" expression of finite differencing, and we sketched out a brief pseudo-code.
- then ran outta time, so didn't get to code it up.


Class 19: modeling 3

I walked them through how to turn the finite-difference expression for lake volume into a code, starting with pseudo-code and fleshing it out from there.

Only got the 2d problem in the last 10 minutes, and that was only enough to set up the idea of grid boxes and flows of soil between them.

Judging from their answers in class, there's still a lot to learn about using arrays and such to solve problems like this. There were crickets even when I asked the basic question about for-loop syntax... maybe they're just shy.


Class 20:

I gave them and me a slight break today, and showed them some Landlab stuff and let them play with a simple LEM. Tried at the end to catch up on the diffusion FTCS but there really wasn't enough time. Only half the class was there anyway. Attendance has been gradually dropping...


Class 21:

Time to coordinate on final projects:
- It would probably help if I can give them some examples of past projects
- Go around the room and have them describe what they're thinking of
- Would be good to post an announcement on canvas to remind them this is coming up; though actually that might lead people to skip class! Maybe better to just jump in and ask them to come up with something on this spot.
- Would be icing on the cake if I could provide some "canned" projects for those having a hard time deciding

Topics from 2023:
- processing DAS data D
- quantifying baseflow upper Co D
- animating a drill pathway T
- navigating the CU campus I
- calculating slope stability on a volcano I
- exploring isostatic uplift with landlab M
- exploring and animating crater saturation on a planetary surface M
- analyzing Boulder air quality over time D
- analyzing Coulomb stress change on faults M
- analyzing air quality and health outcomes D
- exploring and interpreting ice core isotopic data D
- modeling particle trajectories in vector fields M
- processing dems from historic air photos D
- identifying grains in a thin section I
- identifying stability and instability in numerical models M
- measuring glacier retreat distance from images D
- analyzing flood frequency of front range rivers D
- coding and exploring a 1d valley glacier model M
- using pandas to analyze stream discharge D
- exploring the Seaborn package P
- visualizing C isotopic data D
- analyzing CO2 emissions D


General categories of things:
D - Pick a data set, and do some analysis, visualization, and interpretation
M - Write and explore a (simple) simulation model
I - Write a tool or model that generates new information from an existing data source
T - Write a notebook that uses animations and/or other graphics to teach a scientific concept
P - Demonstrate the capabilities of a scientific Python package









If each person takes 5 minutes, that would be the full class period if everyone was there. But lately we've had only about half the class show up. So 5 x 8 = 40 minutes, which leaves an extra 35. I better have some other stuff planned.

I could just do it as a work session for the current assignment (#5).

And/or as a way to bring up some tips and tricks:














