# Elements of Computing II

<a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" alt="Creative Commons License" /></a>
<a href="https://github.com/kwaldenphd/">Katherine Walden</a> has licensed this content under a <a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

## Table of Contents

- [Description and Goals](#description-and-goals)
- [Textbook](#textbook)
- [Technology](#technology)
- [Course Overview](#course-overview)
- [Assignments](#assignments)
- [Grading](#grading)
- [Accessibility and Inclusion](#accessibility-and-inclusion)
- [Honesty and Intellectual Integrity](#honesty-and-intellectual-integrity)
- [Schedule](#schedule)

## Acknowledgements

This syllabus and all course materials have been prepared in conversation with and adapted from the example of many generous colleagues, including but not limited to: those who taught prior iterations of this course as well as CSC 105 at Grinnell College, Dr. Corey Pennycuff, Dr. Peter Bui, Dr. Jerod Weinman, Dr. Samuel A. Rebelsky, Dr. Ursula Wolz, Dr. Janet Davis, Dr. Liz Rodrigues, Dr. Lindsay K. Mattock, Dr. Anelise Hanson-Shrout, Dr. Dave Eichmann, Megan Adams, Julia Bauder, and Jarren Santos.

# Description and Goals

![Marshmallow Peeps help familiarize students with data visualizations and analysis, Photo: Gissoo Doroudian, from Jim Casey, “Taste the Data!” Princeton Center for Digital Humanities, 15 May 2019](https://cdh.princeton.edu/media/images/peeps_img_7254.max-1536x2158.jpg)

*Marshmallow Peeps help familiarize students with data visualizations and analysis (Photo: Gissoo Doroudian) from Jim Casey, “[Taste the Data!](https://cdh.princeton.edu/updates/2019/05/15/taste-data/)” Princeton Center for Digital Humanities (15 May 2019).*

This course covers intermediate level programming in Python, building on concepts covered in Elements of Computing I. Topics we will cover include data structures; relational database systems; and data manipulation, analysis, and communication in a Python programming environment. Along the way, we will be considering how data can be used to create communities, advance research, and expose injustice. But data can also be used to discriminate, marginalize, and surveil. This course will equip you to work with data in a programming environment while also considering larger questions around data and its social and cultural impact.

Our major learning objectives for this course include:
- Continue developing intermediate proficiency in a Python programming environment
  * Navigate command-line based environments and Python documentation
  * Trace code execution, recognize errors, and correct bugs.
  * Employ code reuse and modularity principles to build and organize complex programs
  * Use third-party libraries to analyze and visualize data in a Python programming environment
- Gain self-efficacy in working with structured data in a programming environment
  * Understand the basic elements of data structures and relational database systems
  * Work with a variety of data structures and data sources in a Python programming environment
- Identify and describe the broader social and cultural context for data-driven technology systems and research projects

To be successful in this course you must: tinker, play, build, make, tweak, experiment, hack, and break things. You will push your boundaries and the boundaries of the technology, ask many questions of yourself and your peers, be confused and/or frustrated and/or lost, dig yourself out of those traps and think deeply about the digital tools that are part of digital and computing technology. 

# Textbook

There are no required texts that must be purchased for this course. All assigned materials are available through Hesburgh Libraries and/or posted as an accessible PDF on Canvas. Links to Hesburgh Library resources are included in the “Course Schedule” of the syllabus and also posted on Canvas. 

A number of additional resources on the Python programming language are available online. These resources are useful for troubleshooting or exploring specific topics more deeply.
- [Link to Google Doc](https://bit.ly/walden-python-resources) with general Python resources

# Technology

This course will use the Canvas learning management system.

Python instructional materials are written in Markdown (.md) an made available in multiple formats:
- GitHub webpage
- Google Colaboratory link you can copy to your local drive or download as a `.ipynb` file

One option is installing the Anaconda data science toolkit on your personal computer (free- no cost):
- [Install Anaconda](https://www.anaconda.com/products/individual)

Another option is to use Google Colaboratory, an online web-based interface for Jupyter Notebooks (available for free through your ND Google account):
- [Google CoLab tutorial](https://github.com/kwaldenphd/python-jupyter-notebooks/blob/main/google-colab-instructions.md)
- ["Welcome to Colaboratory" notebook from Google CoLab](https://colab.research.google.com/notebooks/intro.ipynb)

If you do not have access to a personal computer, laptops are available for checkout at the Hesburgh Library’s first floor Circulation Desk ([link to more information](https://library.nd.edu/technology-lending)). You can also reserve a computer station at the Hesburgh Library ([link to reservation system](https://libcal.library.nd.edu/reserve/hesburgh-library-computer-stations)).

# Course Overview

<table>
  <tr>
    <th>Week</th>
    <th>Topic</th>
    <th>Lab</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Course Introductions and course overview</td>
    <td><a href="https://github.com/kwaldenphd/python-spyder">Lab: Python in Spyder</a></td>
  </tr>
 <tr>
  <th colspan="3">Data Structures in Python</th>
 </tr>
  <tr>
    <td>2</td>
    <td>Where can we get data?</td>
    <td><a href="https://github.com/kwaldenphd/apis-python">Lab: Web APIs in Python</a></td>
  </tr>
  <tr>
    <td>3</td>
    <td>Identifying a data source</td>
   <td><a href="https://github.com/kwaldenphd/eoc-final-project-resources/blob/main/assignment-prompt.md#identify-a-data-source">Final project: Identify a data source</a></td>
  </tr>
  <tr>
  <th colspan="3">Relational Database Systems</th>
 </tr>
  <tr>
    <td>4</td>
    <td>What is a data model?; What are relational databases?</td>
    <td><a href="https://github.com/kwaldenphd/data-models">Lab: Data Models & SQLite Intro</a></td>
  </tr>
  <tr>
    <td>5</td>
    <td>How can we access information in a database?</td>
    <td><a href="https://github.com/kwaldenphd/sql-queries-joins">Lab: Queries & Joins</a></td>
  </tr>
  <tr>
    <td>6</td>
    <td>How can we access and use relational databases in Python?</td>
    <td><a href="https://github.com/kwaldenphd/sqlite-to-python">Lab: From SQLite to Python</a></td>
  </tr>
  <tr>
    <td>7</td>
    <td>Building a data model</td>
    <td><a href="https://github.com/kwaldenphd/eoc-final-project-resources/blob/main/assignment-prompt.md#build-a-data-model">Final project: Building a data model</a></td>
  </tr>
  <tr>
  <th colspan="3">Data Wrangling</th>
 </tr>
    <tr>
    <td>8</td>
    <td>What is tidy data and why does it matter?</td>
    <td><a href="https://github.com/kwaldenphd/tidy-data-principles">Lab: Tidy Data</a></td>
  </tr>
  <tr>
    <td>9</td>
    <td colspan="2">MID-TERM BREAK</td>
  </tr>
  <tr>
    <td>10</td>
    <td>What is data wrangling? How can we work with structured data in Python?</td>
   <td><a href="https://github.com/kwaldenphd/eda-pandas">Lab: Data Wrangling With Pandas</a></td>
  </tr>
  <tr>
  <th colspan="3">Data Communication</th>
 </tr>
  <tr>
    <td>11</td>
    <td>What is data visualization?</td>
    <td><a href="https://github.com/kwaldenphd/matplotlib-intro">Lab: Introduction to Matplotlib</a></td>
  </tr>
    <tr>
    <td>12</td>
    <td>Data visualization considerations and best practices</td>
    <td><a href="https://github.com/kwaldenphd/more-with-matplotlib">Lab: More with Matplotlib</a></td>
  </tr>
    <tr>
    <td>13</td>
    <td>How can we use Python to communicate using data?</td>
     <td><a href="https://github.com/kwaldenphd/interactive-visualization-python">Lab: Interactive Visualization in Python</a></td>
  </tr>
  <tr>
  <th colspan="3">Final Project</th>
 </tr>
    <tr>
    <td>14</td>
    <td>Final project</td>
    <td><a href="https://github.com/kwaldenphd/eoc-final-project-resources/blob/main/assignment-prompt.md">Final project</a></td>
  </tr>
    <tr>
    <td>15</td>
    <td colspan = "2">Final project shareouts + course reflections</td>
  </tr>
  </table>

# Assignments

## Reflections

Each week, you will engage with the assigned material and other course content via individual reflections. These reflections summarize what you have learned and how you learned during the process of engaging with the readings and related work during a given week. The reflection should provide an analysis of the experience drawing upon the course topics, themes, and readings. Someone reading your reflection should have a sense of why this project was significant to your learning, how your understanding of computing has changed (or not), and how the project has impacted your understanding of computing and digital technology.

These reflections could take a variety of forms--written text, recorded audio, video, etc. Length guidelines:
- Written text (at least 300 words in length)
  * OR
- Recorded audio/video (at least 2 minutes)

## Lab Notebooks

Throughout the semester, we will work through a number of lab projects designed to increase your comfort level and proficiency with specific computing concepts. For each lab project, you will be provided with a set of instructions that will guide you through the successful completion of the lab. Your lab notebook will document your experience completing the tutorial including your questions and observations and responses to the discussion questions included in the lab instructions. 

Your notebook should be submitted on Canvas as a single document containing the responses to the discussion questions, your observations and questions, and any additional reflection. **Lab notebooks that do not use the provided notebook template will be marked as incomplete.**

## Final Project

The final project for this course involves an open-ended data communication project built using Python. There is no one specific form this project must take. One of my goals for the final project is for you to have an opportunity to delve into and explore in greater depth an aspect of the course that interests you, while also having the opportunity to further develop skills you would like to hone. 

Successful final projects will include two main components:
- a well-documented, working Python program written in Jupyter Notebooks
- a written reflection (minimum 300 words) that documents how you approached the final project/what you wanted to accomplish via the final project, resources consulted, how you handled challenges you encountered, key takeaways, etc.
  * That reflection can come at the end of the Jupyter Notebook or be embedded throughout the Jupyter Notebook, if you want to approach authoring the notebook as a type of tutorial or "report".

Other components you could develop as part of the final project:
- Blog post with data analysis/visualization
- Research paper with data analysis/visualization
- Presentation that features slide deck with data analysis/visualization
- Infographics
- Research poster
- Interactive digital project (embedded plotly visualizations or Dash app)

I will generally be open to final project ideas with a strong rationale and feasibility plan.

GitHub repository with resources, tutorials, sample projects, etc: github.com/kwaldenphd/eoc-final-project-resources

The wide range of possible project directions makes it hard to have a single overarching criteria in terms of project length/scope. So we’ll approach this in terms of the number of hours you should expect to spend working on the final project. 

Expect to spend at least 30 hours working on the final project. That includes brainstorming, meeting with instructor/TAs, in-class work time, etc. If you’re working on a project that is not going to take that much time, think about how to add complexity or take on another smaller scale project.

Contact the instructor with questions.

We will approach the final project in stages:
- Identifying a data source
- Building a data model
- Developing data visualizations
- In-class work time
- Shareouts

## Participation and Engagement

Class sessions will consist of three modes of instruction and participation/engagement. All of these options include synchronous and asynchronous engagement options.

**Lectures** will typically focus on the presentation of a key idea and may include some in-class activities. Lectures will be pre-recorded and posted on Panopto (which you can access through Canvas).

**Discussions** will build on assigned materials and information presented in lectures. These conversations are an opportunity for you to build on individual reflections, engage with colleagues’ observations, and work collaboratively to more fully understand assigned material and core concepts. Discussions will take place synchronously.

These discussions will be framed by questions/prompts provided by your colleagues as well as the instructor. Participation/engagement involves showing up, interacting/engaging with colleagues, and providing well-developed contributions and responses. Discussion engagement/participation options will include a wide variety of formats, including:
- Large group discussions
- Small group discussions
- Individual brainstorming/reflection
- Collaborative Google Doc annotation
- Etc.

**Labs** will typically focus on working through a series of steps to learn or make use of a particular tool–such as the command line, Python code, or a software designed to demonstrate a particular computing concept. A lab overview and in some cases live coding will be recorded and posted on Panopto (which you can access through Canvas). Participation and engagement involves showing up, working with colleagues as assigned, asking questions as needed, and completing the work of the lab. You may not always complete the lab during class. Be prepared for labs to also require work outside class time. Slack and/or email are available to let you pose questions to colleagues, teaching assistants, and the instructor.

# Grading

PLACEHOLDER

## What This Looks Like in Practice

## Grade Requirements

## FAQs

## Assignment Deadlines, Late Work & Extenuating Circumstances

All assignments are due at the date and time listed in the individual assignment descriptions. For assignments without a specific due date/time, they should be submitted in the week listed on the schedule.

In the event we move to remote learning (for a period of time or the remainder of the semester): Posted deadlines reflect whatever time zone is local to where you are (i.e. an assignment due at 5pm on Friday in South Bend would be due 5pm on Friday in your local time zone).

Assignments that are not submitted in a timely fashion will result in an Incomplete assessment. This policy protects both your time and mine. It also ensures that you will remain on track to complete all of your work by the end of the term. I will make exceptions for extenuating circumstances, so please reach out to me if you believe that you cannot meet an assignment deadline.

Complete/Incomplete grades will be posted on Canvas. If you would like to discuss your performance in the course, email me to set up an appointment. I am not able to send or discuss grade information via email. 

It is your responsibility to contact me as soon as possible if such a circumstance will prevent you from attending a class session or completing the coursework according to the set schedule. I will then work with you to determine the best path forward for your particular situation.

# Accessibility and Inclusion

## Privacy

This course is a community built on trust; in order to create the most effective learning experience, our interactions, discussions, and course activities must remain private and free from external intrusion. The hybrid nature of this course means we will be using digital platforms that create additional  As members of this course community, we are obliged to respect the individual dignity of all and to refrain from actions that diminish others’ ability to learn. 
Course materials (videos, assignments, problem sets, etc) stay within the course. If you’re wanting to share them with students outside the course or in a public forum, check with me first.

Some class meetings (when there are lectures) will be recorded to support remote students and to provide everyone in the class with useful study aids. These recordings will be available for review through Canvas. The University strictly prohibits anyone from duplicating, downloading, or sharing live class recordings with anyone outside of this course, for any reason.

Student work, discussion posts, and all other forms of student information (name, email, image, etc.) are protected by the Family Educational Rights and Privacy Act of 1974. Sharing private information about our course community (including discussions, activities, presentations, student work, etc) with others for the purpose of inviting external attention, intrusion, ridicule, or harassment is an egregious breach of trust.

## Non-Discrimination

My goal is to create a fully inclusive classroom, thus I welcome individual students to approach me about distinctive learning needs. Our work in this class falls under the University’s non-discrimintion policy, which prohibits discrimination “basis of race, color, national or ethnic origin, sex, disability, veteran status, genetic information, or age” ([University of Notre Dame, Office of Institutional Equity, “Notice of Non-Discrimination”](https://equity.nd.edu/equity-resources/notice-of-non-discrimination/))

## Accomodations

In particular, I encourage students with disabilities to have a conversation with me and disclose how our classroom or course activities could impact the disability and what accommodations would be essential.

Any student who has a documented disability and is registered with Accessibility Services should speak with the professor as soon as possible regarding accommodations. Students who are not registered should contact the Sara Bea Center for Student Accessibility Services as soon as possible (https://sarabea.nd.edu/). 

## Mental Health

Care and Wellness Consultants provide support and resources to students who are experiencing stressful or difficult situations that may be interfering with academic progress. Through Care and Wellness Consultants, students can be referred to The University Counseling Center (for cost-free and confidential psychological and psychiatric services from licensed professionals), University Health Services (which provides primary care, psychiatric services, case management, and a pharmacy), and The McDonald Center for Student Well Being (for problems with sleep, stress, and substance use). Visit http://care.nd.edu to learn more.

## Title IX

The University of Notre Dame provides services for those who have been affected by sexual assault, sexual misconduct, dating or domestic violence, stalking and any conduct that creates a hostile environment.  For help and further information including contact information for on and off-campus resources, consult titleix.nd.edu/support-resources. 

## Additional Resources and Links

- Sara Bea Center for Student Accessibility Services [sarabea.nd.edu]
- Office of Institutional Equity [equity.nd.edu]
- Title IX / Sexual Assault Resources [titleix.nd.edu/support-resources] 
- University Counseling Center [ucc.nd.edu]
- McDonald Center for Student Well-Being [mcwell.nd.edu]
- University Health Services [uhs.nd.edu]
- List with additional resources [care.nd.edu/resources-to-use/campus-resources]

# Honesty and Intellectual Integrity

[Click here](https://github.com/kwaldenphd/eoc-final-project-resources/blob/main/honor-code.md) to learn more about how Notre Dame's honor code applies to your work in this class.

# Schedule

Assigned material not openly available online is available through Hesburgh Libraries and/or posted as an accessible PDF on Canvas. Links to Hesburgh Library resources are included in the “Course Schedule” of the syllabus and also posted on Canvas. Contact the instructor if you have questions or challenges accessing assigned readings.

- [Week 1: Introductions & course overview](#week-1-introductions--course-overview)
- [Week 2: Where can we get data?](#week-2-where-can-we-get-data)
- [Week 3: Identifying a data source](#week-3-identifying-a-data-source)
- [Week 4: What is a data model?; What are relational databases?](#week-4-what-is-a-data-model-what-are-relational-databases)
- [Week 5: How can we access information in a database?](#week-5-how-)
- [Week 6: How can we access and use relational databases in Python?](#week-6-how-can-we-access-and-use-relational-databases)
- [Week 7: Building a data model](#week-7-building-a-data-model)
- [Week 8: What is tidy data and why does it matter?](#week-8-what-is-tidy-data-and-why-does-it-matter)
- [Week 9: MID-TERM BREAK](#week-9-mid-term-break)
- [Week 10: What is data wrangling? How can we work with structured data in Python?](#week-10-what-is-data-wrangling-how-can-we-work-with-structured-data-in-python)
- [Week 11: What is data visualization?](#week-11-what-is-data-visualization)
- [Week 12: Data visualization considerations and best practices](#week-12-data-visualization-considerations-and-best-practices)
- [Week 13: How can we use Python to communicate using data?](#week-13-how-can-we-use-python-to-communicate-using-data)
- [Week 14: Final project work](#week-14-final-project-work)
- [Week 15: Final Project Shareouts + Course Reflections](#week-15-final-project-shareouts--course-reflections)

## Week 1: Introductions & course overview

### Assigned Material
- *Coded Bias*, directed by Shalini Kantayya. 7th Empire Media, 2020. 90 minutes.
  * [Link to access via Panopto](https://notredame.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=5edb13f5-cc56-4231-9b68-ac7a0148e66c)
  * [Link to stream via Netflix](https://www.netflix.com/watch/81328723) (requires subscription)

### Lab
- [Lab: Python in Spyder](https://github.com/kwaldenphd/python-spyder)

### In-Class Work
- Course overview, Introductions
- Lab work time

### Work Due Outside Class
- Technology intake survey
- Introductions (discussion post)
- Lab notebook

## Week 2: Where can we get data?

### Assigned Material
- Catherine D’Ignazio and Lauren F. Klein, “Introduction: Why Data Science Needs Feminism” from *Data Feminism* (MIT Press, 2020): 1-20. https://doi.org/10.7551/mitpress/11805.001.0001

### Lab
- [Lab: Web APIs in Python](https://github.com/kwaldenphd/apis-python)

### In-Class Work
- Discussion
- Lab work time

### Work Due Outside Class
- Reflection
- Lab notebook

## Week 3: Identifying a data source

### Assigned Material
- Catherine D’Ignazio and Lauren F. Klein, “Chapter 1: The Power Chapter” from *Data Feminism* (MIT Press, 2020): 21-48. https://doi.org/10.7551/mitpress/11805.001.0001

### Lab
- [Final project: Identify a data source](https://github.com/kwaldenphd/eoc-final-project-resources/blob/main/assignment-prompt.md#identify-a-data-source)

### In-Class Work
- Discussion
- Final project work

### Work Due Outside Class
- Reflection
- Final project: Identify a data source

## Week 4: What is a data model?; What are relational databases?

### Assigned Material
- Janet Murray, “The Database Model: Strategies for Segmentation and Juxtaposition of Information” from *Inventing the Medium: Principles of Interaction Design as a Cultural Practice* (MIT Press, 2012); 223-252. [Link to electronic access through Hesburgh Libraries.](https://onesearch.library.nd.edu/permalink/f/1phik6l/ndu_aleph005914907)

### Lab
- [Lab: Data Models & SQLite Intro](https://github.com/kwaldenphd/data-models)

### In-Class Work
- Discussion
- Lab work time

### Work Due Outside Class
- Reflection
- Lab notebook
- Complete grade contract

## Week 5: How can we access information in a database?

### Assigned Material
- Catherine D’Ignazio and Lauren F. Klein, “Chapter 2: Collect, Analyze, Imagine, Teach” from from *Data Feminism* (MIT Press, 2020): 49-72. https://doi.org/10.7551/mitpress/11805.001.0001

### Lab
- [Lab: Queries & Joins](https://github.com/kwaldenphd/sql-queries-joins)

### In-Class Work
- Discussion
- Lab work time

### Work Due Outside Class
- Reflection
- Lab notebook

## Week 6: How can we access and use relational databases in Python?

### Assigned Material
- Ellen Gruber Garvey, “‘facts and FACTS’: Abolitionists’ Database Innovations” in *Raw Data is an Oxymoron*, edited by Lisa Gitelman and Virginia Jackson (MIT Press, 2013): 89-102. [Link to Google Drive PDF.](https://drive.google.com/file/d/1mbjFkJHBHSccfCYoLdpw8fPPwkVg2A26/view?usp=sharing)

### Lab
- [Lab: From SQLite to Python](https://github.com/kwaldenphd/sqlite-to-python)

### In-Class Work
- Discussion
- Lab work time

### Work Due Outside Class
- Reflection
- Lab notebook

## Week 7: Building a data model

### Assigned Material
- Catherine D’Ignazio and Lauren F. Klein, “Chapter 4: What Gets Counted Counts” from from *Data Feminism* (MIT Press, 2020): 97-124. https://doi.org/10.7551/mitpress/11805.001.0001

### Lab
- [Final project: Building a data model](https://github.com/kwaldenphd/eoc-final-project-resources/blob/main/assignment-prompt.md#build-a-data-model)

### In-Class Work
- Discussion
- Final project work

### Work Due Outside Class
- Reflection
- Final project: Build a data model

## Week 8: What is tidy data and why does it matter?

### Assigned Material
- Karl W. Broman and Kara H. Woo, "Data Organization in Spreadsheets," The American Statistician 72:1, 2-10. https://doi.org/10.1080/00031305.2017.1375989 
- Catherine D’Ignazio and Lauren F. Klein, “Chapter 5: Unicorns, Janitors, Ninjas, Wizards, and Rockstars” from from *Data Feminism* (MIT Press, 2020): 125-148. https://doi.org/10.7551/mitpress/11805.001.0001

### Lab
- [Lab: Tidy Data](https://github.com/kwaldenphd/tidy-data-principles)

### In-Class Work
- Discussion
- Lab work time

### Work Due Outside Class
- Reflection
- Lab notebook

## Week 9: MID-TERM BREAK

## Week 10: What is data wrangling? How can we work with structured data in Python?

### Assigned Material
- Catherine D’Ignazio and Lauren F. Klein, “Chapter 6: The Numbers Don’t Speak for Themselves” from from *Data Feminism* (MIT Press, 2020): 149-172. https://doi.org/10.7551/mitpress/11805.001.0001

### Lab
- [Lab: Data Wrangling With Pandas](https://github.com/kwaldenphd/eda-pandas)

### In-Class Work
- Discussion
- Lab work time

### Work Due Outside Class
- Reflection
- Lab notebook
- Midterm reflections

## Week 11: What is data visualization?

### Assigned Material
- Giorgia Lupi, “[Data Humanism: The Revolutionary Future of Data Visualization](http://giorgialupi.com/data-humanism-my-manifesto-for-a-new-data-wold)” *PrintMag* (30 January 2017).
- Enrico Bertini, “[From Data Visualization to Interactive Data Analysis](https://medium.com/@FILWD/from-data-visualization-to-interactive-data-analysis-e24ae3751bf3)” *Medium* (28 November 2017).

### Lab
- [Lab: Introduction to Matplotlib](https://github.com/kwaldenphd/matplotlib-intro)

### In-Class Work
- Discussion
- Lab work time

### Work Due Outside Class
- Reflection
- Lab notebook

## Week 12: Data visualization considerations and best practices

### Assigned Material
- Catherine D’Ignazio and Lauren F. Klein, “Chapter 3: On Rational, Scientific, Objective Viewpoints from Mythical, Imaginary, Impossible Standpoints” from from *Data Feminism* (MIT Press, 2020): 73-96 https://doi.org/10.7551/mitpress/11805.001.0001

### Lab
- [Lab: More with Matplotlib](https://github.com/kwaldenphd/more-with-matplotlib)

### In-Class Work
- Discussion
- Lab work time

### Work Due Outside Class
- Reflection
- Lab notebook

## Week 13: How can we use Python to communicate using data?

### Assigned Material
- Catherine D’Ignazio and Lauren F. Klein, “Chapter 7: Show Your Work” from from *Data Feminism* (MIT Press, 2020): 173-202. https://doi.org/10.7551/mitpress/11805.001.0001

### Lab
- [Lab: Interactive Visualization in Python](https://github.com/kwaldenphd/interactive-visualization-python)

### In-Class Work
- Discussion
- Lab work time

### Work Due Outside Class
- Reflection
- Lab notebook

## Week 14: Final Project Work

### Assigned Material
- Catherine D’Ignazio and Lauren F. Klein, “Conclusion” from from *Data Feminism* (MIT Press, 2020): 203-214. https://doi.org/10.7551/mitpress/11805.001.0001

### Lab: None

### In-Class Work
- Final project work time
- Final project work time

### Work Due Outside Class
- Final project status update

## Week 15: Final Project Shareouts + Course Reflections

### Assigned Material: None

### Lab: None

### In-Class Work
- Final project shareouts
- Course reflections

### Work Due Outside Class
- Final project
- Course reflections
