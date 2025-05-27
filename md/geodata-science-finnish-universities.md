---
date created: 2025-05-22 11:56
last modified: 2025-05-22 11:56
theme: serif
width: 1920
height: 1080
---

## **Geodata science education at Finnish universities**: What we teach, how we do it, and what we have learned in the process

<br/>

**David Whipp**, Department of Geosciences and Geography, University of Helsinki, Finland

_with contributions from_ 

**Henrikki Tenkanen** (Aalto University) and **Vuokko Heikinheimo** (Finnish Environment Institute)

---

<!-- slide template="[[slide-big-left-small-right]]" -->

::: title
## A few things about the University of Helsinki
:::

::: left
- **University of Helsinki**: Finland’s largest university (~31,000 students, ~4700 staff)

- **Faculty of Science**: Largest of the university’s 11 faculties (~6000 students, ~1350 staff)

- **Department of Geosciences and Geography**: 22 professors, 20+ other teaching staff, >60* postdocs and PhD students
:::

::: right
![[img/physicum-winter-tall.jpg]]
:::

::: source
Photo: Jani Närhi
:::

--

## A few things about Finland and Finns

<grid  drag="100 40" drop="top" flow="row" align="bottom">
![[sauna.jpg]]
![[lake.png]]
</grid>

<grid drag="100 40" drop="bottom" flow="row" align="bottom">
![[bus-stop.png]]
![[bucket.png]]
</grid>

<grid drag="100 20" drop="3 -30">
<p style="font-size: large;">
https://www.reddit.com/r/Finland/comments/z0w2my/finns_waiting_for_the_bus_again/
</p>
</grid>

--
<!-- slide template="[[slide-big-left-small-right]]" -->

::: title
## Why am I here?
:::

::: left
- I am currently on sabbatical visiting CU until June 17th<br/>
- I am hoping to connect with researchers and educators here to share ideas and help develop geodata science teaching *materials*, *methods*, and *learning environments*<br/>
- Please **ask questions** as they come up and **interrupt me as you like**
:::

::: right
![[slides-qr-code.png]]
View or share these slides
:::

::: source
Slides source: https://github.com/davewhipp/geodata-science-education-in-finland
:::

---

## Overview

**Goal today**: Provide an overview of the courses and teaching approaches we have developed to provide a quantitative foundation for bachelor's and master's students in *geology* and *geography*

**Topics** <!-- element class="fragment" data-fragment-index="1" -->

+ Learning goals and sources of inspiration
+ Courses we have developed
+ Our learning tools and environment
+ Lessons we have learned, challenges that persist

---

# Learning goals and sources of inspiration

--
<!-- slide template="[[slide-big-left-small-right]]" -->

::: title
## The ideal scenario
:::

::: left
Our aim is to support our students in learning *essential computing skills* including:

1) Basic programming (in Python)
2) Good coding practices (e.g., using Git)
3) Batch processing
4) Modern tools used by data scientists (e.g., GitHub)
:::

::: right
![](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2F66.media.tumblr.com%2F75e78a6a35b2f4c53dedb22b6eacb2b2%2Ftumblr_n17v3ty2dp1sfgmmzo1_500.gif&f=1&nofb=1&ipt=0a36e8b151f39ededcaf4cadc001d0ce252cc41ea67893fa9f6e060a38ddfbbb)
Vibing to computing goodness
:::

::: source
Image: [https://www.tumblr.com/](https://www.tumblr.com/)
:::

--

<!-- slide template="[[slide-big-left-small-right]]" -->

::: title
## Sources of inspiration 
:::

::: left
Like many natural scientists, we are self-taught programmers<br/>

This means that we only learned important skills for *open, reproducible science* rather late, including:

- Version control
- Unit testing
- Good coding practices (e.g., PEP 8)
- Effective debugging<br/>

**[Software Carpentry](https://carpentries.org/)** is an excellent, and inspiring resource for these topics
:::

::: right
![[software-carpentry.png]]
:::

::: source
Image: Some [Software Carpentry](https://carpentries.org/lessons/) lessons
:::

--

<!-- slide template="[[slide-small-left-big-right]]" -->

::: title
## Sources of inspiration 
:::

::: left
The learning resources from **GitHub** have also proved to be excellent, especially since we utilize Git and GitHub in many of our courses
:::

::: right
![[github-lessons.png]]
:::

::: source
Source: [https://docs.github.com/](https://docs.github.com/en/get-started/start-your-journey/git-and-github-learning-resources)
:::

--

<!-- slide template="[[slide-big-left-small-right]]" -->

::: title
## Sources of inspiration 
:::

::: left
Essential textbooks have also been a valuable resource and example of how to approach teaching certain topics<br/>

McKinney's book **Python for Data Analysis**, for example, provides an excellent overview of the **pandas** library, which is heavily used in our course materials
:::

::: right
![](https://wesmckinney.com/book/images/cover.png)
Wes McKinney's **pandas** book
:::

::: source
Source: https://wesmckinney.com/book/
:::

--

<!-- slide template="[[slide-big-left-small-right]]" -->

::: title
## Sources of inspiration 
:::

::: left
And of course, we try to keep up with what is happening in the *broader educational community* and with *new developments in Python and other related tools we teach and use*<br/>

This includes following what the education team here at Earth Lab has been working on :smile:
:::

::: right
![](https://earthlab.colorado.edu/sites/default/files/styles/square_med/public/media/image/Untitled%20design.png?itok=dOEdyAQ9)
We've been watching you...
:::

::: source
Image: https://earthlab.colorado.edu/
:::

---

# Courses we have developed

--

<!-- slide template="[[slide-big-left-small-right]]" -->

::: title
## Python for geo-people
:::

::: left
**Python for geo-people** was our first Python-based course, where we:

- Introduced students to the Python programming language
- Developed basic programming skills
- Introduced the use of Git and GitHub classroom<br/>

**Target audience**: BSc and MSc students in *geology* and *geography*<br/>

Everything in this course was done using the Spyder IDE or a Python interpreter via remote desktop connections to cloud servers
:::

::: right
![[python-for-geo-people.png]]
:::

::: source
Source: https://github.com/Python-for-geo-people/Course-information
:::

--

<grid drag="100 20" drop="top" justify-content="center">
## Geo-Python (and its evolution)
</grid>

<grid drag="30 100" drop="left" justify-content="center">
![[python-for-geo-people.png]]
2016
</grid>

<grid drag="30 100" drop="center" justify-content="center">
![[geo-python-2017.png]]
2017
</grid>

<grid drag="30 100" drop="right" justify-content="center">
![[geo-python-2024.png]]
2024
</grid>

<grid drag="100 15" drop="bottom" justify-content="center">
**Geo-Python** is our current introductory Python programming course. In it we introduce Python, basic programming concepts, good programming practices, and modern tools for computational scientists
</grid>

--

<!-- slide template="[[slide-big-left-small-right]]" -->

::: title
## Geo-Python
:::

::: left
The **Geo-Python** course runs for 7 weeks, with 1 weekly 3-hour lecture period and 2 (*optional*) weekly exercise help sessions<br/>

The course covers:

- Python basics
- Loops and conditional statements
- Functions and script files
- Data analysis with **pandas**
- Data visualization<br/>

Because the students are a mix of geologists and geographers, we use *climate data* for our example datasets
:::

::: right
![](https://geo-python-site.readthedocs.io/en/latest/_images/yle-summer-2024.png)
Example lesson motivation (https://yle.fi/a/74-20109657)
:::

::: source
Geo-Python website: https://geo-python.github.io
:::

--

<!-- slide template="[[slide-small-left-big-right]]" -->

::: title
## Geo-Python
:::

::: left
Students are assessed using **weekly computing / data analysis exercises** (60% of course grade) and a **final exercise** (40% of course grade)<br/>

Exercises have 2–4 problems, each with several parts<br/>

Students *normally* work on exercises for 4–8 hours per week
:::

::: right
![[temp-classifier-exercise.png]]
Example exercise problem
:::

::: source

:::

--

<!-- slide template="[[slide-small-left-big-right]]" -->

::: title
## Geo-Python
:::

::: left
We also **record videos** of each lesson and post them on YouTube. About half of the students turn up in person.<br/>

The course enrollment is ~80–100 students each autumn, and our current teaching team comprises 2 instructors and 4 teaching assistants
:::

::: right
![[geo-python-youtube.png]]
Geo-Python YouTube videos
:::

::: source
Geo-Python YouTube channel: http://www.youtube.com/@geo-python
:::

--

<!-- slide template="[[slide-big-left-small-right]]" -->

::: title
## Automating GIS processes (II)
:::

::: left
The **Automating GIS processes** (AutoGIS) course is the *geography* students' follow-up course to Geo-Python<br/>

This course applies and broadens the students' Python skillset through lessons on:

1. Shapely and geometry objects
2. Managing spatial data with GeoPandas
3. Geocoding and spatial queries
4. Reclassifying data, overlay analysis
5. Visualization: static and interactive maps
6. OpenStreetMap data and network analysis
7. Working with raster data
:::

::: right
![](https://autogis-site.readthedocs.io/en/latest/_static/AutoGIS.PNG)
:::

::: source
AutoGIS website: https://autogis.github.io
:::

--

<!-- slide template="[[slide-small-left-big-right]]" -->

::: title
## Automating GIS processes (II)
:::

::: left
The AutoGIS learning environment is *very similar to Geo-Python*, and students also have weekly exercises and a final project<br/>

We also record videos of course lessons and share them on YouTube
:::

::: right
![[autogis-map.png]]
Interactive map of train/metro stations in Helsinki
:::

::: source
AutoGIS YouTube channel: https://www.youtube.com/@AutomatingGISprocesses
:::

--

<!-- slide template="[[slide-big-left-small-right]]" -->

::: title
## Introduction to Quantitative Geology
:::

::: left
The **Introduction to Quantitative Geology** (IntroQG) course is the *geology* students' follow-up course to Geo-Python<br/>

Course students develop their Python skills by studying:

1. Basic geostatistics
2. Comparing predictions to observations
3. The diffusion equation
4. The advection/wave equation
5. Viscous flow equations
6. Building a numerical model
7. Quantitative thermochronology
:::

::: right
\begin{align}
A &= \frac{\sum{x^{2}} \sum{y} - \sum{x} \sum{xy}}{\Delta} \\\\
\\\\
B &= \frac{N \sum{xy} - \sum{x} \sum {y}}{\Delta} \\\\
\\\\
\Delta &= N \sum{x^{2}} - \left( \sum{x} \right)^{2}
\end{align}
Linear regression equations
:::

::: source
IntroQG website: https://introqg.github.io
:::

--

<!-- slide template="[[slide-small-left-big-right]]" -->

::: title
## Introduction to Quantitative Geology
:::

::: left
Again, the IntroQG learning environment and structure is *similar to Geo-Python and AutoGIS*<br/>

Students have weekly exercises, a final report, and *shorter* lesson videos are posted on YouTube (www.youtube.com/@introqg)
:::

::: right
![](https://introqg-site.readthedocs.io/en/latest/_images/Allen_fig_4-12b.png)
Viscous flow down an inclined plane
:::

::: source
Source: *Earth Surface Processes*, P. Allen, 1997.
:::

--

## Other courses/sites

We offer several courses with online content that might be of interest:
<br/>

### Courses

- **Introduction to Spatial Data Analysis** — https://introsda.readthedocs.io/
- **Spatial Data Science for Sustainable Development** — https://sustainability-gis.readthedocs.io/
- **Spatial Data Science for Sustainable Mobility** — https://sumogis.readthedocs.io/
<br/>

### Sites

- **Spatial Data Science with High Performance Computing** — https://geohpc.readthedocs.io/
- **Geospatial Challenge Camp** — https://challenge-camp.geoportti.fi/

---

# Our learning tools and environment

--

<!-- slide template="[[slide-big-left-small-right]]" -->

::: title
## Learning tools
:::

::: left
Our course learning tools have been selected to be *complementary* and *in line with modern applications in academia and industry*
<br/>

We don't expect every student to become a professional programmer, but introduce essential tools and concepts to help them better *understand* and *interact* with software developers
<br/>

The number of tools can cause some confusion for the students, but they generally learn to use them within a couple weeks
:::

::: right
![](https://www.clipartbest.com/cliparts/nTB/Xgx/nTBXgxEkc.png)
:::

::: source
Image: https://www.clipartbest.com/clipart-nTBXgxEkc
:::

--

<!-- slide template="[[slide-small-left-big-right]]" -->

::: title
## Jupyter notebooks and JupyterLab
:::

::: left
Almost all of our course learning materials and exercises are based in **Jupyter Notebooks** using **JupyterLab**<br/>

The combination of *rich text* for descriptive texts and *code cells* for programming is ideal not only for new programmers, but also for documenting data science workflows
:::

::: right
![[jupyterlab.png]]
A Jupyter Notebook in JupyterLab
:::

::: source

:::

--

<!-- slide template="[[slide-big-left-small-right]]" -->

::: title
## Noppe and Binder
:::

::: left
One challenge with learning using Jupyter Notebooks is that a server is (generally) required to make the notebooks interactive
<br/>

We are fortunate to have the Finnish CSC – IT Center for Science (https://csc.fi/en/), who hosts the **Noppe platform** for running Jupyter Notebooks
<br/>

Noppe allows teachers to create custom Python environments and offers persistent storage and shared storage for students/teachers
:::

::: right
![](https://csc.fi/app/uploads/2024/01/CSC_2012_LOGO.png)
CSC resources are free to use for all Finnish university students and researchers/teachers
:::

::: source
More info on Noppe: https://research.csc.fi/service/noppe/
:::

--

<!-- slide template="[[slide-big-left-small-right]]" -->

::: title
## Noppe and Binder
:::

::: left
However, as we make all of our course learning materials freely available online, we also support the use of Binder for learners not affiliated with a Finnish university
<br/>

**Binder** is a free cloud-computing service that can be used to make Jupyter Notebooks interactive
<br/>

However, it *does not provide persistent storage*, and Binder resources can sometimes be *limiting with larger datasets*
:::

::: right
<img src="https://mybinder.org/static/logo.svg" width=800>
:::

::: source
More info on Binder: https://mybinder.readthedocs.io/en/latest/index.html
:::

--

<!-- slide template="[[slide-big-left-small-right]]" -->

::: title
## Git, GitHub, and GitHub Classroom
:::

::: left
The Geo-Python course introduces **version control using Git**, as well as how to use GitHub and GitHub Classroom<br/>

We introduce Git in order to support students learning the process of making *incremental* and *documented* changes to their programs<br/>

This not only helps with *debugging their code*, but builds an understanding of Git to later help with *collaborative code development*
:::

::: right
![](https://imgs.xkcd.com/comics/git_2x.png)
:::

::: source
Image: https://xkcd.com/1597
:::

--

<!-- slide template="[[slide-small-left-big-right]]" -->

::: title
## Git, GitHub, and GitHub Classroom
:::

::: left
**GitHub** is used in our courses as the site where student exercises are cloned and stored<br/>

Students learn how to *clone* their exercises, *push* changes, and *collaborate* using GitHub<br/>

We use the **JupyterLab Git extension** so students can commit changes while working in JupyterLab
:::

::: right
![[github-exercise.png]]
An exercise template copy (private)
:::

::: source
More about JupyterLab Git: https://github.com/jupyterlab/jupyterlab-git
:::

--

<!-- slide template="[[slide-small-left-big-right]]" -->

::: title
## Git, GitHub, and GitHub Classroom
:::

::: left
Finally, we use **GitHub Classroom** to distribute exercises to the students and manage their submissions
<br/>

Templates of the exercise are created from which students can *make private copies* using exercise links on the course website
:::

::: right
![[github-classroom.png]]
The Geo-Python 2024 GitHub Classroom
:::

::: source

:::

--

<!-- slide template="[[slide-small-left-big-right]]" -->

::: title
## Course communication
:::

::: left
We encourage students to communicate with us and each other using team communication platforms<br/>

Currently, we are using **Discord** for all class communication, where students chat with one another about course materials and exercise questions<br/>

Earlier we have used **Slack**
:::

::: right
![[discord.png]]
The Geo-Python 2024 GitHub Classroom
:::

::: source

:::

--

<!-- slide template="[[slide-small-left-big-right]]" -->

::: title
## Course interaction
:::

::: left
In the Geo-Python course we utilize **Presemo** for interactive questions during the lesson<br/>

We start class with Presemo questions about the previous week's material while students settle in<br/>

We also have occasional questions during lessons to pause and reflect on new material
:::

::: right
![[presemo.png]]
An example Presemo poll question
:::

::: source
More about Presemo: http://presemo.com/docs/userguide.en.html
:::

--

<!-- slide template="[[slide-small-left-big-right]]" -->

::: title
## Course grading
:::

::: left
We have been using **nbgrader** to create our exercises<br/>

**nbgrader** makes it easy *create* student exercise templates from instructor master copies (that include solutions) and automatically or manually *grade* the problems<br/>

*However...*
:::

::: right
<img src="https://nbgrader.readthedocs.io/en/stable/_images/creating_assignment.gif" width=1600>
The <b>nbgrader</b> instructor interface
:::

::: source
More about **nbgrader**: https://nbgrader.readthedocs.io/
:::

--

<!-- slide template="[[slide-small-left-big-right]]" -->

::: title
## Course grading
:::

::: left
As we are using GitHub Classroom to distribute assignments, students *are not able to validate their solutions* to automatically graded problems<br/>

Thus, we are in the process of migrating to using tests in **pytest**, which can be run automatically whenever students push changes
:::

::: right
<img src="https://nbgrader.readthedocs.io/en/stable/_images/student_assignment.gif" width=1600>
The <b>nbgrader</b> student interface
:::

::: source
More about **nbgrader**: https://nbgrader.readthedocs.io/
:::

--

<!-- slide template="[[slide-big-left-small-right]]" -->

::: title
## Teaching philosophy - LLMs OK
:::

::: left
Teaching basic programming skills in the time of **generative text tools** (based on large language models - LLMs) is challenging<br/>

Yet, we want our students to know how to *write good prompts to produce, test, and understand code*<br/>

Thus, we introduce how to generate code using ChatGPT and indicate places where the use of similar tools is OK with the text "LLMs OK"
:::

::: right
![[chatgpt.png]]
The OpenAI logo
:::

::: source

:::

--

<!-- slide template="[[slide-small-left-big-right]]" -->

::: title
## Teaching philosophy - Pair programming
:::

::: left
We also *pair students up* in the Geo-Python course to encourage them to learn together<br/>

We use a pre-course survey to pair more experienced students with new programmers<br/>

And following the pair programming philosophy, one student is the "*driver*" and the other "*navigates*"
:::

::: right
<p align="right">
<img src="https://www.pngmart.com/files/13/Adventure-Time-Jake-And-Finn-Transparent-PNG.png"></p>
:::

::: source
Image: https://www.pngmart.com/image/208129
:::

---

# Lessons learned and ongoing challenges

--

<!-- slide template="[[slide-big-left-small-right]]" -->

::: title
## Lessons learned
:::

::: left
+ Students **apply what they learn!**<br/>
+ Students **enjoy having a programming partner** (most of them, at least)!<br/>
+ It can be hard to find the correct balance between **challenging new programmers and still engaging more experienced students**
:::

::: right
![](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fi.pinimg.com%2Foriginals%2Fe8%2Fed%2Fba%2Fe8edbac9b244fb0524c5f0a23393d65a.png&f=1&nofb=1&ipt=15330524d63d373d7e1609c3a4257efa116bc4708754a805fc4d5e56cc3a67cd)
:::

::: source
Image: https://www.vrogue.co/
:::

--

<!-- slide template="[[slide-big-left-small-right]]" -->

::: title
## Ongoing challenges
:::

::: left
+ We get regular requests for issuing certificates to students outside of Finnish universities, but **lack resources to assess their exercises, etc.**<br/>
+ Automated grading is super helpful, but designing *good tests* and providing feedback while students work **takes time** (see resource issue...)
:::

::: right
![](https://www.pngmart.com/files/13/Adventure-Time-Lumpy-PNG-Photo.png)
:::

::: source
Image: https://www.pngmart.com/image/207673
:::

--

<!-- slide template="[[slide-big-left-small-right]]" -->

::: title
## Ongoing challenges
:::

::: left
+ Generative text tools *can be* great for helping students learn, but can also **interfere with them developing the skills to understand whether code they produce is sensible**<br/>
+ Structured exercises are good for teachers to make sure students do tasks in a preferred order, and also good for automating grading. However, having **too much structure can limit student's ability to be creative and come up with their own approach to problem solving**.
:::

::: right
![](https://www.pngmart.com/files/13/Adventure-Time-Lumpy-PNG-Photo.png)
:::

::: source
Image: https://www.pngmart.com/image/207673
:::

---

<!-- slide template="[[slide-big-left-small-right]]" -->

::: title
## End of our adventure, acknowledgements
:::

::: left
### Current and former Geo-Python teachers <!-- element class="fragment" data-fragment-index="1" -->

Håvard Aagesen Christoph Fink, Kamyar Hasanzadeh, Yijun Wang <!-- element class="fragment" data-fragment-index="1" -->
<br/>

### Current and former course assistants <!-- element class="fragment" data-fragment-index="2" -->

<p align="left">
Nino Chkhartishvili, Emil Ehnström, Antti Kallanranta, Mikko Kangasmaa, Sonja Koivisto, Sanni Laaksonen, Hertta Lehvävirta, Samuli Massinen, Oyelowo Oyedayo, Justus Poutanen, Aleksi Rantanen, Vili Rauhala, Sakari Sarjakoski, Aino Schulz, Jorina Schütt, Veeti Sihvola, Sara Todorovic, Leevi Tuikka, Bryan Vallejo, Annarosa Whitman, Lotta Ylä-Mella</p> <!-- element class="fragment" data-fragment-index="2" -->
:::

::: right
![](http://dl9fvu4r30qs1.cloudfront.net/48/2c/d2d51b2f4559b7641be11c128bea/adventure-time.jpg) <!-- element class="fragment" data-fragment-index="1" -->
:::

::: source
Image: <!-- element class="fragment" data-fragment-index="1" --> https://www.indiewire.com/ <!-- element class="fragment" data-fragment-index="1" -->
:::

--

<!-- slide template="[[slide-big-left-small-right]]" -->

::: title
## Thank you!
:::

::: left
Thanks for your attention, questions are welcome!
<br/>

And as a last note, we're working on a textbook titled ***Introduction to Python for Geographic Data Analysis*** that is freely available online and about 75% complete (should be finished this year - hard copies will be available from CRC Press)
<br/>

The book is a combination of the Geo-Python and Automating GIS processes courses, with a few additional case studies
:::

::: right
![[pythongis-qr-code.png]]
Check out the book draft
:::

::: source

:::