# Developing and contributing to fredhutch.io courses

## Requirements for fredhutch.io courses

- Course Types
  - Technical/skills-based classes: Class time includes 1) short explanations of main concepts, 2) live demos of technical skills, during which learners follow along (when applicable), 3) challenge/practice exercises (I do, we do, you do)
  - Concepts-based courses: Class time includes 1) Lecture and/or discussion on foundational understanding of concepts, 2) example applications of concepts

- Timing and scheduling
  - Concepts courses: four one hour sessions, one to two sessions per week
  - Technical courses: four two hour sessions (ten minute break in the middle), one to two sessions per week

- Learning objectives: each course has a well-articulated, specific audience and clear learning objectives, with associated objectives for each lesson

- Courses should be reproducible, in that instructors can pick up the material and teach with little additional preparation needed, with course content available in a GitHub repository in the fredhutchio organization and listings on our website
  - Slides are included where applicable (especially for concepts courses), but instructors should also feel free to show images from the GitHub materials
  - instrutor notes are available in each repo, as well as the [Instructor notes](https://github.com/fredhutchio/instructors) repo


## Developing new course content

Developing content for fredhutch.io courses is different than developing material for a formal class,
because short-form professional development courses don't need to include formal assessment and other requirements associated with university credit.
In particular,
short courses (especially those related to coding skills) should generally focus on:
- applied skills, rather than concepts,
that aim toward tasks likely to be encountered in research
- minimized jargon and technical details (these are not computer science classes!)
- emphasizing resiliency and an ability to troubleshoot (e.g., finding help when code isn't working)

Given these considerations,
the following sections should help you think about how to tackle course development.

### What is the goal of the course?

The title of a course is not always very informative about what participants will learn.
For example,
ask five people for their top five topics to include in an introduction to Python programming course,
and you'll likely end up with a list of about twenty different topics.

This means learning objectives are very important to help participants decide whether the course is a good fit for them.
Sometimes objectives are framed as a list of topics.
For the example above,
introductory Python may include:
Jupyter notebooks, Python syntax, data structures, functions.
While this generally makes sense,
it's better to represent learning objectives as a completion of the following sentence:
"By the end of this course,
you should be able to..."

We can translate the previous topics using this framework:

By the end of this course,
you should be able to:
- work in a Jupyter notebook to run and record Python code
- understand basic Python syntax to use functions and assign variables
- create basic data structures (sequences and dictionaries)
- define functions

This makes it much easier for participants to understand their goals.
For example,
*using* functions is a separate objective from *defining* custom functions.

For multi-class courses,
both the entire course *and* each individual class should have 3-5 learning objectives each.
The class learning objectives should roughly map to the course objectives.
It helps to think about learning objectives as forming a united narrative leading participants to a specific point at the end of the course.

### What is the course format?

Course scheduling,
including frequency and duration of courses,
can have a huge impact on the ability of participants to work through all course material.

Short-form courses have more freedom in scheduling than formal courses for credit,
because we can decide our own schedule separate from a university.
Additionally, the specific activities during class can affect how long participants can stay engaged.

Sometimes course development becomes a bit of a puzzle,
attempting to fit material into chunks that make sense in the context of the class schedule.
Some ways to manage this include:
- thinking about different ways to conceptually fit concepts together
(e.g., is there a brief concept we can introduce at the end of one class that will come in handy during the next class?)
- using challenge exercises to touch on useful, 
but perhaps out-of-scope,
ideas