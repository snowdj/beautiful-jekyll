---
layout: page
title: Course Info
---

## Who / what / where / when

**Synopsis**: We introduce basic principles and techniques in the fields of data mining and machine learning. These are some of the key tools behind the emerging field of data science and the popularity of the "big data" buzzword. These techniques are now running behind the scenes to discover patterns and make predictions in various applications in our daily lives. We'll focus on many of the core data mining and machine learning technologies, with motivating applications from a variety of disciplines.


**Lectures**: MWF 1-2pm in Hugh Dempster Pavilion (DMP) 110

**Tutorials**:

| Section | Place | Time |
|---------|-------|------|
| T2A     | DMP 101 | M 4-5 pm |
| T2B     | DMP 101 | M 3-4 pm |
| T2C     | DMP 201 | T 2-3pm |

**Office hours**: See the [course calendar](https://ubc-cs.github.io/cpsc340/calendar/).


**Instructor**: [Mike Gelbart](http://www.cs.ubc.ca/~mgelbart/)

**Teaching Assistants**: 

- Ricky Chen
- Ritika Jain
- Issam Laradji
- Bita Nejat
- Wenyi Wang

## Prerequisites

 - Basic algorithms and data structures (CPSC 221, or both of CPSC 260 and EECE 320 as well as one of CPSC 210, EECE 201, or EECE 309).
 - Linear algebra (one of MATH 152, 221, or 223).
 - Probability (one of STAT 200, STAT 203, STAT 241, STAT 251, STAT 302, MATH 302, MATH 318, or BIOL 300).
 - Multivariate calculus (one of MATH 200, 217, 226, 253, or 263).

NOTE: since multivariate calculus is a new prerequisite, for the 2016-17 year only we are allowing MATH 200 (equivalent) to be taken as a co-requisite provided that the average of the other MATH/STAT prerequisites is at least 76%. Other courses that are helpful but not required include scientific computing (CPSC 302), algorithms and complexity (CPSC 320), and statistical inference (STAT 305).

## Registration
Undergraduate and graduate students from any department are welcome to take the class, provided that they satisfy the prerequisites. If you do not satisfy the exact prerequisites but would still like to enroll in the class, there are additional details available [here](https://www.cs.ubc.ca/~schmidtm/Courses/340_prereqs.pdf) and [here](https://www.cs.ubc.ca/students/grad/registration/grads-outside-cs).

The general seats available in this class usually fill up very quickly. Because of this, we have reserved a small number of restricted seats for CPSC graduate students. These seats will turn into general seats at the end of the first week of class.

Once the general seats are taken, the only way to register for the course is to sign up for the waiting list. You should sign up for the waiting list even if it is long; last year we were able to accommodate all students on the waiting list. Signing up for the waiting list also makes it more likely that we will open up extra sessions, expand class sizes, or offer additional courses on these topics. You may also want to consider taking related courses from statistics: [STAT 305](https://courses.students.ubc.ca/cs/main?pname=subjarea&tname=subjareas&req=3&dept=STAT&course=305), [STAT 306](https://courses.students.ubc.ca/cs/main?pname=subjarea&tname=subjareas&req=3&dept=STAT&course=306), [STAT 406](https://courses.students.ubc.ca/cs/main?pname=subjarea&tname=subjareas&req=3&dept=STAT&course=406), [STAT 460](https://courses.students.ubc.ca/cs/main?pname=subjarea&tname=subjareas&req=3&dept=STAT&course=460), [STAT 461](https://courses.students.ubc.ca/cs/main?pname=subjarea&tname=subjareas&req=3&dept=STAT&course=461) (as well as [EOSC 510](https://www.eoas.ubc.ca/courses/eosc510/eosc510.htm)). A discussion of the difference between CPSC 340 and these various STAT classes written by a former student (Geoff Roeder) is available [here](https://www.cs.ubc.ca/~schmidtm/Courses/CPSCvsSTAT.txt).

## Textbook
There is no required textbook for the class. A introductory book that covers many (but not all) the topics we will discuss is the [Artificial Intelligence](http://aima.cs.berkeley.edu/) book of Russell and Norvig (AI:AMA) or the [Artificial Intelligence](http://artint.info/html/ArtInt.html) book of Poole and Mackworth (you may need these for other classes). More advanced books include The [Elements of Statistical Learning](http://statweb.stanford.edu/~tibs/ElemStatLearn/) (ESL) by Hastie et al., Murphy's [Machine Learning: A Probabilistic Perspective](http://www.cs.ubc.ca/~murphyk/MLbook/index.html) (ML:APP) which can be accessed through the library [here](http://site.ebrary.com/lib/ubc/docDetail.action?docID=10597102), and Bishop's [Pattern Recognition and Machine Learning](http://research.microsoft.com/en-us/um/people/cmbishop/prml/) (PRML). For books with a bigger focus on data mining, see [Introduction to Data Mining](http://www-users.cs.umn.edu/~kumar/dmbook/index.php) (IDM) and [Mining of Massive Datasets](http://www.mmds.org/).

Related courses that have online notes

* [Machine Learning and Data Mining](https://www.cs.ubc.ca/~schmidtm/Courses/340-F16/) (UBC 2016W1)
* [Machine Learning and Data Mining](http://www.cs.ubc.ca/~nando/340-2012/) (UBC 2012)
* [Machine Learning](http://cs229.stanford.edu/materials.html) (Stanford)
* [Introduction to Machine Learning](http://webdocs.cs.ualberta.ca/~dale/cmput466/w06/notes.html) (Alberta - Schuurmans)
* [Introduction to Machine Learning](http://webdocs.cs.ualberta.ca/~greiner/C-466/SLIDES/syllabus.html) (Alberta - Greiner)
* [Introduction to Machine Learning](http://www.eecs.berkeley.edu/~russell/classes/cs194/f11/lectures.html#Week4) (Berkeley)
* [Practical Machine Learning](http://people.eecs.berkeley.edu/~jordan/courses/294-fall09/) (Berkeley)
* [Machine Learning](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-867-machine-learning-fall-2006/lecture-notes/) (MIT)
* [Machine Learning](http://www.cs.cmu.edu/~epxing/Class/10701/lecture.html) (CMU)
* [Course in Machine Learning](http://ciml.info/) (Maryland)
* [Principles of Knowledge Discovery in Data](http://webdocs.cs.ualberta.ca/~zaiane/courses/cmput695/F07/695Schedule.html) (Alberta)
* [Mining Massive Data Sets](http://web.stanford.edu/class/cs246/handouts.html) (Stanford)
* [Data Mining](http://www.stat.cmu.edu/~ryantibs/datamining/) (CMU)

## Programming environment

We will be using Python for this course because it is open source and widely used in machine learning and data science. We recommend Python 3.5 because of some minor conveniences: dividing two integers returns a float by default, it has nice syntax like `x@y` for matrix multiplication, etc. However, we recognize that Python 2.7 is still the dominant version (inside and outside machine learning) and therefore we will _try_ to maintain Python 2.7 compatibility in all our materials. You can find more info online; see, for example, [Python 3 in 2016](https://hynek.me/articles/python3-2016/).

We recommend the Anaconda Python distribution because it comes bundled with a bunch of useful libraries (NumPy, SciPy, Jupyter notebook). You can [download Anaconda from their website](https://www.continuum.io/downloads) for free.  

Here are some resources that might help you learn Python. Note that the course staff has not tried out these materials and so we aren't necessarily endorsing them.

- <https://www.codecademy.com/learn/python>
- <https://www.coursera.org/learn/python>
- <https://www.datacamp.com>
- <https://www.udacity.com/course/programming-foundations-with-python--ud036>
- <https://www.coursera.org/learn/python-programming-introduction>
- <https://www.coursera.org/learn/python-data-analysis>
- <https://www.coursera.org/learn/principles-of-computing-1>

## Grading
The grading scheme for the course is as follows:

| Component  | Weight  |
|-------------|-----|
| Assignments | 25% |
| Midterm  | 30%
| Final | 45% |

## Q&A
We will use [Piazza](https://piazza.com/ubc.ca/winterterm22016/cpsc340/home) for course-related questions.

## CPSC 340 vs. CPSC 540

Our department also offers a graduate ML course, CPSC 540:

 - More advanced material.
 - More focus on theory/implementation, less focus on applications.
 - More prerequisites and higher workload.
 - Offered in Term 2 (now)

For almost all students, CPSC 340 is the right class to take:

 - CPSC 340 focuses on the most widely-used methods in practice.
 - CPSC 540 is intended as a continuation of CPSC 340.
 - You’ll miss important topics if you skip CPSC 340.


## Attribution
Most of the content on this page was taken (with permission) from [Mark Schmidt's CPSC 340 course homepage](https://www.cs.ubc.ca/~schmidtm/Courses/340-F16/).
