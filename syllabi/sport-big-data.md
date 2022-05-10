# Sport and Big Data

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

This syllabus and all course materials have been prepared in conversation with and adapted from the examples and work of many generous colleagues, including but not limited to: Dr. Liz Rodrigues, Dr. Lindsay K. Mattock, Dr. Anelise Hanson-Shrout, Dr. Jesse Stommel, Professor Sean Michael Morris, Dr. Alfie Kohn, Dr. Peter Elbow, Dr. Lauren F. Klein, Dr. Catherine D’Ignazio, Dr. Shannon Mattern, Dr. Virginia Eubanks, the #DataFeminism book club, Dr. Miriam Posner, and Jarren Santos. Previous cohorts of students who have taken this class have also provided critical feedback on their experiences, and this feedback is instrumental in shaping future iterations of the course.

# Description and Goals

![Image caption: Whitey Herzog’s batting chart for Eddie Murray, 1989–1990. National Baseball Hall of Fame and Museum.](https://www.loc.gov/static/exhibitions/baseball-americana/images/objects/the-art-and-science-of-baseball/the-measure-of-the-game/ba0098_enlarge.jpg)
*Image caption: Whitey Herzog’s batting chart for Eddie Murray, 1989–1990. National Baseball Hall of Fame and Museum.*

Sport is one of the most enduringly popular and significant cultural activities in the United States. Data has always been a central part of professional sport in the US, from Henry Chadwick’s invention of the baseball box score in the 1850s to the National Football League’s use of Wonderlic test scores to evaluate players. This course focuses on the intersecting structures of power and identity that shape how we make sense of the “datification” of professional sport. By focusing on the cultural significance of sport data, this course will put the datafication of sport in historical context and trace the ways the datafication of sport has impacted athletes, fans, media, and other stakeholders in the sport industry. The course will also delve into the  technology systems used to collect and analyze sport data, from the TrackMan and PITCHf/x systems used in Major League Baseball to the National Football League’s Next Gen Stats partnership to emerging computer vision and artificial intelligence research methods. This course is not about gaining mastery of particular technologies, tools, or methods, therefore familiarity with statistical analysis or data science tools (R, RStudio, Python, etc.) is NOT a prerequisite for this course

Through this course, you will be able to:
- Identify and describe key developments, structures, and stakeholders involved at the intersection of sport and data
- Describe and explain various aspects of sport/data intersections in terms of their historical context, cultural significance, and technical infrastructures
- Evaluate and critique data-driven sport technology systems and research projects through the lens of interdisciplinary American Studies frameworks
- Gain self-efficacy in working with structured data and related data tools
- Design and construct research projects that connect American Studies interdisciplinary frameworks and methods to course topics and content
- Undertake collaborative work that builds project management skills

# Textbook

There are no required texts that must be purchased for this course. All assigned materials are available through Hesburgh Libraries and/or posted as an accessible PDF on Canvas. Links to Hesburgh Library resources are included in the “Course Schedule” of the syllabus and also posted on Canvas. 

If you would like to buy books, we will be reading multiple chapters from a few key texts. I encourage you to support a Black-owned bookstore if purchasing any of these titles. An option local to South Bend is [Brain Lair Books](https://www.brainlairbooks.com/).
- Phillips, Christopher J. *Scouting and Scoring: How We Know What We Know About Baseball* (Princeton University Press, 2020)
- Colás, Yago. *Numbers Don’t Lie: New Adventures in Counting and What Counts In Basketball Analytics* (University of Nebraska Press, 2020)
- Goldsberry, Kirk, and Aaron Dana. *Sprawlball: A Visual Tour of the New Era of the NBA* (Houghton Mifflin Harcourt, 2019).
- Fouche, Rayvon. *Game Changer: The Techno-Scientific Revolution in Sports* (Johns Hopkins University Press, 2017).
- Sterling, Jennifer, and Mary G. McDonald. *Sports, Society, and Technology: Bodies, Practices, and Knowledge Production* (Palgrave Macmillan, 2020).
- Marchi, Max, Jim Albert, and Benjamin S. Baumer. *Analyzing Baseball Data With R* (CRC Press, 2019).
- Zuccolotto, Paola, and Marica Manisera. *Basketball Data Science With Applications in R* (CRC Press, 2020).

# Technology

This course will use the Canvas learning management system.

Labs in this course have an RStudio and Python option. We will walk through how to set up a programming environment on your local computing environment during the first few weeks of the semester. Instructional materials will use Jupyter Notebooks for Python and RStudio for R, but you are welcome to use any environment.

If you do not have access to a personal computer, laptops are available for checkout at the Hesburgh Library’s first floor Circulation Desk ([link to more information](https://library.nd.edu/technology-lending)). You can also reserve a computer station at the Hesburgh Library ([link to reservation system](https://libcal.library.nd.edu/reserve/hesburgh-library-computer-stations)).

# Course Overview

<table>
  <tr>
    <th>Week</th>
    <th>Topic</th>
    <th>Python Lab</th>
    <th>RStudio Lab</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Course overview and introductions; What do we mean by sport and big data?</td>
    <td><a href="https://github.com/kwaldenphd/pandas-machine-learning-intro">Lab: Getting Started With RStudio</a></td>
    <td><a href="https://github.com/kwaldenphd/Python">Lab: Getting Started With Python</a></td>
  </tr>
  <tr>
    <td>2</td>
    <td>Baseball, Sabermetrics, and “Moneyball” (part 1)</td>
    <td><a href="https://github.com/kwaldenphd/pandas-machine-learning-intro">Lab: Getting Started With RStudio</a></td>
    <td><a href="https://github.com/kwaldenphd/Python">Lab: Getting Started With Python</a></td>
  </tr>
  <tr>
    <td>3</td>
    <td>Baseball, Sabermetrics, and “Moneyball” (part 2)</td>
    <td><a href="https://github.com/kwaldenphd/tidy-data-r-intro">Lab: Introduction to Tidy Data in R</a></td>
    <td><a href="https://github.com/kwaldenphd/apis-python">Lab: Web APIs in Python</a></td>
  </tr>
  <tr>
    <td>4</td>
    <td>Data and power: historical, social, and cultural context</td>
    <td><a href="https://github.com/kwaldenphd/dplyr-intro">Lab: Data Wrangling in R Using dplyr</a></td>
    <td><a href="https://github.com/kwaldenphd/pandas-intro">Lab: Introduction to Pandas</a></td>
  </tr>
  <tr>
    <td>5</td>
    <td>Policing Gender (at the Olympics) (part 1)</td>
    <td><a href="https://github.com/kwaldenphd/merging-joining-rstudio">Lab: Merging and Joining in R using dplyr</a></td>
    <td><a href="https://github.com/kwaldenphd/eda-pandas">Lab: Data Wrangling in Pandas</a></td>
  </tr>
  <tr>
    <td>6</td>
    <td>Policing Gender (at the Olympics) (part 2)</td>
    <td><a href="https://github.com/kwaldenphd/data-scraping-rvest">Lab: Data Scraping in R Using rvest</a></td>
    <td><a href="https://github.com/kwaldenphd/data-scraping-python">Lab: Data Scraping in Python</a></td>
  </tr>
  <tr>
    <td>7</td>
    <td>Race, Power, and the National Football League (part 1)</td>
    <td><a href="https://github.com/kwaldenphd/ggplot-intro">Lab: Data Visualization in R Using ggplot2</a></td>
    <td><a href="https://github.com/kwaldenphd/matplotlib-intro">Lab: Introduction to Matplotlib</a></td>
  </tr>
    <tr>
    <td>8</td>
    <td>Race, Power, and the National Football League (part 2)</td>
    <td><a href="https://github.com/kwaldenphd/intro-statistics-rstudio">Lab: Getting Started With Statistics in R</a></td>
    <td><a href="https://github.com/kwaldenphd/more-with-matplotlib">Lab: More With Matplotlib</a></td>
  </tr>
  <tr>
    <td>9</td>
    <td colspan="3">MID-TERM BREAK</td>
  </tr>
  <tr>
    <td>10</td>
    <td>Basketball, Analytics, and  the Geography of Moving Dots (part 1)</td>
    <td><a href="https://github.com/kwaldenphd/plotly-intro-r/tree/sport-data">Lab: Interactive Visualization in R With plotly</a></td>
    <td><a href="https://github.com/kwaldenphd/interactive-visualization-python">Lab: Interactive Visualization in Python</a></td>
  </tr>
  <tr>
    <td>11</td>
    <td colspan="3">Basketball, Analytics, and  the Geography of Moving Dots (part 2)</td>
  </tr>
  <tr>
    <td>12</td>
    <td colspan="3">Current Issues (part 1): Measuring Diversity</td>
  </tr>
  <tr>
    <td>12</td>
    <td colspan="3">Current Issues (part 2): What Gets Counted Counts</td>
  </tr>
    <tr>
    <td>14</td>
    <td colspan = "3">Final project work</td>
  </tr>
    <tr>
    <td>15</td>
    <td colspan = "3">Final project shareouts + course reflections</td>
  </tr>
  </table>

# Assignments

## Reflections

Each week, you will engage with the assigned material and other course content via individual reflections. These reflections summarize what you have learned and how you learned during the process of engaging with the readings and related work during a given week. The reflection should provide an analysis of the experience drawing upon the course topics, themes, and readings. Someone reading your reflection should have a sense of why this project was significant to your learning, how your understanding of computing has changed (or not), and how the project has impacted your understanding of computing and digital technology.

These reflections could take a variety of forms--written text, recorded audio, video, etc. Length guidelines:
- Written text (at least 400 words in length)
  * OR
- Recorded audio/video (at least 3 minutes)

## Lab Notebooks

We will work through a number of lab projects designed to increase your comfort level and proficiency with structured data. The default option is to complete these labs in RStudio, an open-source program and scripting language widely used in data science work. 

If you are already proficient in RStudio, there is an option for a Python lab track. NOTE: If you have taken/are taking/will take the Elements of Computing sequence, then complete the RStudio lab track. If you are proficient in both languages, I can connect you with specialized resources that would build on existing skills to come up with a robust lab experience. 

Again--the default is R/RStudio. There is a Python option. If you know both of these languages (such that the labs provided would not be a robust learning experience), let’s talk.

For each lab project, you will be provided with a set of instructions that will guide you through the successful completion of the lab. Your lab notebook will document your experience completing the tutorial including your questions and observations and responses to the discussion questions included in the lab instructions. 

Your notebook should be submitted on Canvas as a code or notebook file (or compressed folder containing multiple files) that includes responses to the discussion questions, your observations and questions, and any additional reflection. 

For weeks that have a lab assignment, we will spend time in class on Thursday introducing the lab and working on it collaboratively. 

<table>
  <tr>
    <th>Week</th>
    <th>Python Lab</th>
    <th>RStudio Lab</th>
  </tr>
  <tr>
    <td>1-2</td>
    <td><a href="https://github.com/kwaldenphd/pandas-machine-learning-intro">Lab: Getting Started With RStudio</a></td>
    <td><a href="https://github.com/kwaldenphd/Python">Lab: Getting Started With Python</a></td>
  </tr>
  <tr>
    <td>3</td>
    <td><a href="https://github.com/kwaldenphd/tidy-data-r-intro">Lab: Introduction to Tidy Data in R</a></td>
    <td><a href="https://github.com/kwaldenphd/apis-python">Lab: Web APIs in Python</a></td>
  </tr>
  <tr>
    <td>4</td>
    <td><a href="https://github.com/kwaldenphd/dplyr-intro">Lab: Data Wrangling in R Using dplyr</a></td>
    <td><a href="https://github.com/kwaldenphd/pandas-intro">Lab: Introduction to Pandas</a></td>
  </tr>
  <tr>
    <td>5</td>
    <td><a href="https://github.com/kwaldenphd/merging-joining-rstudio">Lab: Merging and Joining in R using dplyr</a></td>
    <td><a href="https://github.com/kwaldenphd/eda-pandas">Lab: Data Wrangling in Pandas</a></td>
  </tr>
  <tr>
    <td>6</td>
    <td><a href="https://github.com/kwaldenphd/data-scraping-rvest">Lab: Data Scraping in R Using rvest</a></td>
    <td><a href="https://github.com/kwaldenphd/data-scraping-python">Lab: Data Scraping in Python</a></td>
  </tr>
  <tr>
    <td>7</td>
    <td><a href="https://github.com/kwaldenphd/ggplot-intro">Lab: Data Visualization in R Using ggplot2</a></td>
    <td><a href="https://github.com/kwaldenphd/matplotlib-intro">Lab: Introduction to Matplotlib</a></td>
  </tr>
    <tr>
    <td>8</td>
    <td><a href="https://github.com/kwaldenphd/intro-statistics-rstudio">Lab: Getting Started With Statistics in R</a></td>
    <td><a href="https://github.com/kwaldenphd/more-with-matplotlib">Lab: More With Matplotlib</a></td>
  </tr>
  <tr>
    <td>10</td>
    <td><a href="https://github.com/kwaldenphd/plotly-intro-r/tree/sport-data">Lab: Interactive Visualization in R With plotly</a></td>
    <td><a href="https://github.com/kwaldenphd/interactive-visualization-python">Lab: Interactive Visualization in Python</a></td>
  </tr>
  </table>

Some things that might fall under "other":
- Max Marchi, Jim Albert, and Benjamin S. Baumer, *Analyzing Baseball Data With R* (CRC Press, 2019). [Link to online access via Hesburgh Libraries](https://onesearch.library.nd.edu/permalink/f/1phik6l/ndu_aleph006004137).
- Paola Zuccolotto, and Marica Manisera, *Basketball Data Science With Applications in R* (CRC Press, 2020). [Link to online access via Hesburgh Libraries](https://onesearch.library.nd.edu/permalink/f/1phik6l/ndu_aleph005460621).
- Work through select tutorials
  * A few Towards Data Science examples: "[Re-Imagining NFL Cornerback Performance using Pandas and Plotly](https://towardsdatascience.com/re-imagining-nfl-cornerback-performance-using-pandas-plotly-21e86fe2c445)," "[Python Hockey Analytics Tutorial for Beginners](https://towardsdatascience.com/python-hockey-analytics-tutorial-b0883085938a)," "[Modelling a Game of Tennis](https://towardsdatascience.com/building-a-tennis-match-simulator-in-python-3add9af6bebe)"
  * [GitHub repository with some tutorials/starting places](https://github.com/kwaldenphd/sport-data-resources/blob/main/tutorials.md)
- Explore selected Python/RStudio packages ([GitHub repository with some starting places](https://github.com/kwaldenphd/sport-data-resources/blob/main/data-packages.md))

## Case Studies

Throughout the course, we will be engaging in virtual site visits, hosting guest speakers, and learning more about the current professional landscape of sport and data. As we broaden our collective understanding of this landscape, you also have the opportunity to do a deep dive into a sport data system, issue, context, or application that is of interest to you. These deep dives will take the form of case studies that will be shared or presented with the larger class. 

Each student will complete and/or contribute to at least one (1) case study. You can undertake this assignment individually or in a group. 

This assignment could take a variety of forms. Some examples:
- Research paper
- Research poster
- Blog post or visual essay
- Audio narrative
- Narrated presentation
- Video essay
- Infographic
- Timeline
- Interactive visualization

Length expectations:
- Written projects: at least 1200 words
- Audio/video media projects: at least 5 minutes
- Visual media projects: criteria developed in conversation with the instructor

These projects will be shared on the “Case Studies” Canvas discussion board, with the additional option of sharing or presenting the work in-class.

Step #1: In-class time will be provided for brainstorming ideas and possible collaborations. Keep working on your own to browse the syllabus and consider possible topics of interest.

Step #2: When you/your group has a more developed idea, complete the case study Google Form. This form needs to be completed by the end of Week #6.

Step #3: Instructor will follow up with feedback. We’ll talk over Zoom or via email about next steps.

Step #4: You’ll work on the project.

Step #5: You’ll submit and possibly present the project.

## Final Project

The final project for this course is an open-ended creation that engages topics, concepts, and other course elements. One of my goals for the final project is for you to have an opportunity to delve into and explore in greater depth an aspect of the course that interests you, while also having the opportunity to further develop skills you would like to hone.

You can undertake this project individually or in a group.

Projects that could fulfill this assignment might include:
- Analyze or audit an sport data technology system
- Draft a white paper or set of recommendations
- Build a public-facing interactive resource built using RStudio/Shiny or Python/Plotly (or another data science tool). 
- Research paper (could be for a scholarly or public audience)
- Build a tutorial, package, module, or other type of technical documentation
- A podcast, video, or other type of multimedia/digital project that applies course concepts and interdisciplinary frameworks
- Some type of creative work (musical performance, dance, short story, piece of art, etc.) that connects to the work of this course

I will generally be open to final project ideas with a strong rationale and feasibility plan. Final projects do not have to include an applied data science component. But all projects, regardless of topic and method, are expected to incorporate critical interdisciplinary perspectives grounded in American Studies--that includes consideration of historical, cultural, and social context; identity; power; etc.

The wide range of project options makes it hard to have a single overarching criteria in terms of project length/scope. So we’ll approach this in terms of the number of hours you should expect to spend working on the final project. 

Expect to spend at least 25 hours working on the final project. That includes brainstorming, meeting with instructor/colleagues, case study work (if applicable), in-class work time, etc. If you’re working on a project that is not going to take that much time, think about how to add complexity or take on another smaller scale project.

Contact the instructor with questions.

Things to consider when weighing final project options:
- Skills you bring to this course
- Who the project is “for,” or who you might want to be in conversation with
- What you might want or need to do with the project
- What projects are feasible given social distancing restrictions and other limits on access to campus spaces/resources
- This includes thinking about what resources you would still be able to access in the event of disruption

We will move toward the final project in stages:
- Introduction + Brainstorming
- Proposal
- In-class work time
- Project plan and status update 
- Final Project Share Outs + Submission

GitHub repository with final project resources, including examples of prior student work: github.com/kwaldenphd/sport-data-resources

## Participation and Engagement

Class sessions will consist of three modes of instruction and participation/engagement. All of these options include synchronous and asynchronous engagement options.

**Lectures** will typically focus on the presentation of a key idea and may include some in-class activities. Synchronous engagement is ideal and involves listening, taking notes, asking questions, and participating fully in activities. Lectures will be recorded and posted on Canvas. 

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

# Schedule

Assigned material not openly available online is available through Hesburgh Libraries and/or posted as an accessible PDF on Canvas. Links to Hesburgh Library resources are included in the “Course Schedule” of the syllabus and also posted on Canvas. Contact the instructor if you have questions or challenges accessing assigned readings.

- [Week 1: Course overview and introductions; What do we mean by sport and big data?](#week-1-course-overview-and-introductions)
- [Week 2: Baseball, Sabermetrics, and “Moneyball” (part 1)](#week-2-what-do-we-mean-by-race-and-technologies-of-surveillance)
- [Week 3: Baseball, Sabermetrics, and “Moneyball” (part 2)](#week-3-the-poorhouse-historical-context-for-race-)
- [Week 4: Data and power: historical, social, and cultural context](#week-4-the-plantation-historical-context-for-race-and-technologies-of-surveillance-part-2)
- [Week 5: Policing Gender (at the Olympics) (part 1)](#week-5-the-algorithm-historical-context-for-race-and-technologies-of-surveillance-part-3)
- [Week 6: Policing Gender (at the Olympics) (part 2)](#week-6-where-do-we-go-from-here-part-1)
- [Week 7: Race, Power, and the National Football League (part 1)](#syllabi/race-tech-surveillance.md#week)
- [Week 8: Race, Power, and the National Football League (part 1)](#week-8-case-study-risk-prediction-algorithms-and-the-criminal-justice-system)
- [Week 9: MID-TERM BREAK](#week-9-mid-term-break)
- [Week 10: Basketball, Analytics, and  the Geography of Moving Dots (part 1)](#week-10-case-study-social-media-feed-curation-and-targeted-advertising)
- [Week 11: Basketball, Analytics, and  the Geography of Moving Dots (part 2)](#week-11-case-study-racialized-surveillance-and-k-12-education)
- [Week 12: Current Issues (part 1): Measuring Diversity](#week-12-case-study-racialized-surveillance-and-law-enforcement)
- [Week 13: Current Issues (part 2): What Gets Counted Counts](#week-13-case-study-racial-justice-activism-and-surveillance-of-public-space)
- [Week 14: Final project work](#week-14-final-project-work)
- [Week 15: Final Project Shareouts + Course Reflections](#week-15-final-project-shareouts--course-reflections)

## Week 1: Course overview and introductions; What do we mean by sport and big data?

### Assigned Material
- Chris Gilliard, “[A Black Woman Invented Home Security. Why Did It Go So Wrong](https://www.wired.com/story/black-inventor-home-security-system-surveillance/)” *Wired* (14 November 2021)
- *Coded Bias*, directed by Shalini Kantayya. 7th Empire Media, 2020. 90 minutes.
  * [Link to access via Panopto](https://notredame.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=5edb13f5-cc56-4231-9b68-ac7a0148e66c)
  * [Link to stream via Netflix](https://www.netflix.com/watch/81328723) (requires subscription)

### Lab
- [Lab: Getting started with Python](https://github.com/kwaldenphd/python-refresh)

### In-Class Work
- Course overview, Introductions
- Lab work time

### Work Due Outside Class
- Technology intake survey
- Introductions (discussion post)
- Lab notebook

## Week 2: Baseball, Sabermetrics, and “Moneyball” (part 1)

### Assigned Material
- Simone Browne, “Race and Surveillance” in *Routledge Handbook of Surveillance Studies* (Routledge, 2014): 72-80. [Link to Google Drive PDF](https://drive.google.com/file/d/1Tz-4Lt6SEoZAfn6ZCWE8v0fy3YaDZ39T/view?usp=sharing).
- Amanda Borquaye, “[The ‘Smart Wall’ Relies on Invasive and Ineffective Experimental Technology](https://www.newamerica.org/oti/blog/the-smart-wall-relies-on-invasive-and-ineffective-experimental-technology-theres-nothing-smart-about-that/)” *New America* (5 August 2021)
  * For more on border tech activism: [#NoTechForICE reports produced by Mijente, Just Futures Law, and No Border Wall Coalition](https://notechforice.com/resources/)

### Lab
- [Lab: Getting started with Python](https://github.com/kwaldenphd/python-refresh)

### In-Class Work
- Discussion
- Lab work time

### Work Due Outside Class
- Reflection
- Lab notebook

## Week 3: Baseball, Sabermetrics, and “Moneyball” (part 2)

### Assigned Material
- Virginia Eubanks, *Automating Inequality: How High-Tech Tools Profile, Police, and Punish the Poor* (St. Martin’s, 2017).
  * [Introduction: Red Flags (1-14)](https://drive.google.com/file/d/1h22SQd7_qZzsaHbLug-hh7f7AtSJ-KRn/view?usp=sharing)
  * [Chapter 1, From Poorhouse to Database (14-38)](https://drive.google.com/file/d/1jb3MZo9gOPcoFB_7WDt-FcWg-pPnD4oF/view?usp=sharing)

### Lab
- [Lab: Getting started with Pandas (for machine learning)](https://github.com/kwaldenphd/pandas-machine-learning-intro)

### In-Class Work
- Discussion
- Final project work

### Work Due Outside Class
- Reflection
- Final project: Identify a data source

## Week 4: Data and power: historical, social, and cultural context

### Assigned Material
- Angela Saini, *Superior: The Return of Race Science* (Beacon Press, 2020).
  * [Chapter 2 (25-37)](https://drive.google.com/file/d/19RREWQWeD_Fw8ithqAPnEulxTMA6VSnq/view?usp=sharing)
  * [Chapter 3 (38-52)](https://drive.google.com/file/d/1WVubogX1mi8cVQ_WSaUF-kW42thFkG_H/view?usp=sharing)


### Lab
- [Lab: Building a job screening algorithm in Python](https://github.com/kwaldenphd/job-screening-algorithm)

### In-Class Work
- Discussion
- Lab work time

### Work Due Outside Class
- Reflection
- Lab notebook
- Complete grade contract

## Week 5: Policing Gender (at the Olympics) (part 1)

### Assigned Material
- OPTIONAL: Society for Cultural Anthropology, “[Scientific Racism](https://culanth.org/fieldsights/anthrobites-scientific-racism)” *AnthroBites podcast* (29 August 2017) 17 minutes
- Sidney Fussell, “How Surveillance Has Always Reinforced Racism” *Wired* (19 June 2020)
  * [Interview with Dr. Simone Browne](https://www.wired.com/story/how-surveillance-reinforced-racism/)
  * [Podcast](https://megaphone.link/CNE5532925482)
- Brenda Medina and Thomas Frank, “[TSA Agents Say They’re Not Discriminating Against Black Women, But Their Body Scanners Might Be](https://www.propublica.org/article/tsa-not-discriminating-against-black-women-but-their-body-scanners-might-be)” *ProPublica* (17 April 2019)
  * See also: Jess Kung, Gene Demby, and Shereen Marison Meraji, “[Is ‘race science’ making a comeback?](https://www.npr.org/sections/codeswitch/2019/07/10/416496218/is-race-science-making-a-comeback)” *Code Switch Podcast* (10 June 2019), NPR. 

### Lab
- [Lab: Introduction to machine learning and predictive models in Python](https://github.com/kwaldenphd/machine-learning-intro)

### In-Class Work
- Discussion
- Lab work time

### Work Due Outside Class
- Reflection
- Lab notebook

## Week 6: Policing Gender (at the Olympics) (part 2)

### Assigned Material
- Ruha Benjamin, *Race After Technology: Abolitionist Tools for the New Jim Code* (Polity, 2019). [Link to electronic access through Hesburgh Libraries](https://onesearch.library.nd.edu/permalink/f/1phik6l/ndu_aleph005503708).
  * Pages 1-96 (Introduction through Chapter 2)

### Lab
- [Lab: Building your own machine learning model in Python (part 1)](https://github.com/kwaldenphd/building-a-ml-model)

### In-Class Work
- Discussion
- Lab work time

### Work Due Outside Class
- Reflection
- Lab notebook

## Week 7: Race, Power, and the National Football League (part 1)

### Assigned Material
- Ruha Benjamin, *Race After Technology: Abolitionist Tools for the New Jim Code* (Polity, 2019). [Link to electronic access through Hesburgh Libraries](https://onesearch.library.nd.edu/permalink/f/1phik6l/ndu_aleph005503708).
  * Pages 97-197 (Chapters 3-5)

### Lab
- [Lab: Building your own machine learning model in Python (part 2)](https://github.com/kwaldenphd/building-a-ml-model)

### In-Class Work
- Discussion
- Final project work

### Work Due Outside Class
- Reflection
- Final project: Build a data model

## Week 8: Race, Power, and the National Football League (part 2)

### Assigned Material
- Julia Angwin, Jeff Larson, Surya Mtatu, and Lauren Kirchner, “[Machine Bias](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing)” *ProPublica* (23 May 2016). 
- Jeff Larson, Surya Mattu, Lauren Kirchner, and Julia Angwin, “How We Analyzed the COMPAS Recidivism Algorithm” *ProPublica* (23 May 2016).
- Explore:
  * [Google Drive folder that contains following items](https://drive.google.com/drive/folders/1-by_FJK2wi86flevOi2WKmomE6wL93yB?usp=sharing):
    * Northpointe document collection gathered by ProPublica team
    * Sentencing reports that include risk assessment, gathered by ProPublica team
  * [GitHub repository with data files and Jupyter notebook for ProPublica analysis of COMPAS risk scores](https://github.com/propublica/compas-analysis)

  * See also: Jerry Iannellli, “[Florida’s ‘secret’ formulas to calculate release dates may be trapping people in prison](https://theappeal.org/floridas-secret-formulas-to-calculate-release-dates-may-be-trapping-people-in-prison/)” *Appeal* (20 May 2021)

### Lab
- [Lab: ProPublica COMPAS analysis](https://github.com/kwaldenphd/propublica-compas-lab)

### In-Class Work
- Discussion
- Lab work time

### Work Due Outside Class
- Reflection
- Lab notebook

## Week 9: MID-TERM BREAK

## Week 10: Basketball, Analytics, and  the Geography of Moving Dots (part 1)

### Assigned Material
- Safiya Umoja Noble, *Algorithms of Oppression: How Search Engines Reinforce Racism* (New York University Press, 2018). [Link to electronic access through Hesburgh Libraries](https://onesearch.library.nd.edu/permalink/f/1phik6l/ndu_aleph005505291).
  * Chapter 1 (15-63)
  * Chapter 3 (110-118)

- U.S. House of Representatives Permanent Select Committee on Intelligence, “[Exposing Russia’s Effort to Sow Discord Online: The Internet Research Agency and Advertisements](https://intelligence.house.gov/social-media-content/default.aspx)” *U.S. House of Representatives* (16 February 2018).

- EXPLORE:
  * U.S. House of Representatives Permanent Select Committee on Intelligence, “[Social Media Advertisements](https://intelligence.house.gov/social-media-content/social-media-advertisements.htm)” *U.S. House of Representatives* (2018).
  * Ed Summers, “[Internet Research Facebook ads as structured data](https://github.com/umd-mith/irads)” *GitHub repository*.
  * [Internet Research Agency Ads digital project](https://archive.mith.umd.edu/irads/), Maryland Institute for Technology and the Humanities.
  * Simon Willison’s “Analyzing US Election Russian Facebook Ads”
    * [Blog post](https://simonwillison.net/2018/Aug/6/russian-facebook-ads/)
    * [Searchable interface](https://russian-ira-facebook-ads.datasettes.com/)

### Lab:
- [Lab: Social media, feed curation, and targeted advertising](https://github.com/kwaldenphd/social-media-targeted-advertising)

### In-Class Work
- Discussion
- Lab work time

### Work Due Outside Class
- Reflection
- Lab notebook
- Midterm reflections

## Week 11: Basketball, Analytics, and  the Geography of Moving Dots (part 2)

### Assigned Material
- Claire Galligan, Hannah Rosenfeld, Molly Kleinman, Shobita Parthasarathy, “[Cameras in the Classroom: Facial Recognition Technology in Schools](https://stpp.fordschool.umich.edu/research/research-report/cameras-classroom-facial-recognition-technology-schools)” *University of Michigan’s Science, Technology, and Public Policy Program* (25 August 2020)
  * The whole report is 115 pages- we’ll focus on the [13 page executive summary](https://stppstage.fordschool.umich.edu/sites/stpp/files/2021-07/cameras_in_the_classroom_executive_summary.pdf)

- Jack Gillum and Jeff Kao, with photography by Adrienne Grunwald, “[Aggression Detectors: The Unproven, Invasive Surveillance Technology Schools Are Using to Monitor Students](https://features.propublica.org/aggression-detector/the-unproven-invasive-surveillance-technology-schools-are-using-to-monitor-students/)” *ProPublica* (25 June 2019)

- Jennifer Smith Richards, Jodi S. Cohen, and Lakeidra Chavis, with photography by Zbigniew Bzdak, “[The Quiet Rooms: Children are being locked away, alone and terrified, in schools across Illinois. Often, it’s against the law](https://features.propublica.org/illinois-seclusion-rooms/school-students-put-in-isolated-timeouts/)” *ProPublica Illinois* (19 November 2019)
  * [More reporting from this investigation](https://www.propublica.org/series/illinois-school-seclusions-timeouts-restraints), a collaboration between ProPublica Illinois and the Chicago Tribune

- Coshandra Dillard, “[Envisioning School Safety Without Police](https://www.learningforjustice.org/magazine/fall-2021/envisioning-school-safety-without-police)” *Learning for Justice* (Fall 2021)

- See also:
  * Georgetown Law’s Center on Poverty and Inequality has an Initiative on Gender Justice and Opportunity doing [ongoing research on education and pushout for girls of color](https://genderjusticeandopportunity.georgetown.edu/school-and-pushout/)
  * American Civil Liberties Union, et al, “[The Cost of School Policing: What Florida’s students have paid for a pretense of security](https://www.aclufl.org/en/publications/cost-school-policing)” *ACLU Florida* (2 September 2020)
  * Two-part ACLU report:
    * UCLA Center for Civil Rights Remedies and ACLU of Southern California, “[11 Million Days Lost: Race, Discipline, and Safety and U.S. Public Schools](https://www.aclu.org/report/11-million-days-lost-race-discipline-and-safety-us-public-schools-part-1)” *ACLU* (24 August 2018)
    * ACLU et al, “[Cops and no Counselors: How the Lack of School Mental Health Staff is Harming Students](https://www.aclu.org/report/cops-and-no-counselors)” *ACLU* (4 May 2019)
  * Meribah Knight and Ken Armstrong, “[Black Children Were Jailed for a Crime That Doesn’t Exist. Almost Nothing Happened to the Adults in Charge](https://www.propublica.org/article/black-children-were-jailed-for-a-crime-that-doesnt-exist)” *ProPublica* (8 October 2021)
  * Colin Lecher and Maddy Varner, “[NYC’s School Algorithms Cement Segregation. This Data Shows How](https://themarkup.org/news/2021/05/26/nycs-school-algorithms-cement-segregation-this-data-shows-how)” *Markup* (26 May 2021)
  * Mark Keierleber, “[Gaggle Surveils Millions of Kids in the Name of Safety. Targeted Families Argue it’s ‘Not That Smart’](https://www.the74million.org/article/gaggle-surveillance-minnesapolis-families-not-smart-ai-monitoring/)” *74 Million* (12 October 2021)
  * Heather Schlitz, “[Schools often use AI to find students in crisis - one software-monitoring company reported 5,000 self-harm situations in a single week](https://www.businessinsider.com/school-students-communication-monitoring-ai-software-self-harm-suicide-risks-2021-9)” *Insider* (21 September 2021)

### Lab:
- [Lab: Race and surveillance tech in K12 education](https://github.com/kwaldenphd/race-surveillance-education)

### In-Class Work
- Discussion
- Final project overview

### Work Due Outside Class
- Reflection

## Week 12: Current Issues (part 1): Measuring Diversity

### Assigned Material
- Last Week Tonight with John Oliver, “[Facial Recognition](https://youtu.be/jZjmlJPJgug)” *YouTube* (15 June 2020)

- EXPLORE: [Gender Shades project website](http://gendershades.org/index.html), MIT Media Lab.
  * See also:
    * Joy Buolamwini and Timnit Gebru, “[Gender Shades: Intersectional Accuracy Disparities in Commercial Gender Classification](http://proceedings.mlr.press/v81/buolamwini18a/buolamwini18a.pdf)” *Proceedings of Machine Learning Research Conference on Fairness, Accountability, and Transparency 81* (2018): 1-15.
    * Todd Feathers, “[Google’s New Dermatology App Wasn’t Designed for People With Darker Skin](https://www.vice.com/en/article/m7evmy/googles-new-dermatology-app-wasnt-designed-for-people-with-darker-skin)” *Vice* (20 May 2021)

- Kashmir Hill, “[Wrongfully Accused by an Algorithm](https://www.nytimes.com/2020/06/24/technology/facial-recognition-arrest.html)” *New York Times* (24 June 2020).

- Ryan Mac, Caroline Haskins, Brianna Sacks, and Logan McDonald, "[Surveillance Nation: How A Facial Recognition Tool Found Its Way Into Hundreds Of US Police Departments, Schools, And Taxpayer-Funded Organizations](https://www.buzzfeednews.com/article/ryanmac/clearview-ai-local-police-facial-recognition)" *BuzzFeed News* (6 April 2021).

- SKIM: Todd Feathers, “[Gunshot-detecting tech is summoning armed police to black neighborhoods](https://www.vice.com/en/article/88nd3z/gunshot-detecting-tech-is-summoning-armed-police-to-black-neighborhoods)” *Vice* (19 July 2021)
  * ShotSpotter responds: Lachlan Cartwright and Maxwell Tani, “[Vice hit with $300M suit from controversial surveillance company](https://www.thedailybeast.com/vice-hit-with-dollar300m-suit-from-spotshooter)” *Vice* (12 October 2021)
  * For more on ShotSpotter:
    * Brooke Jarvis, “[Listening for Gunshots](https://story.californiasunday.com/shotspotter-gunshot-surveillance/)” *California Sunday Magazine* (29 September 2016)
    * Garance Burke, Martha Mendoza, Juliet Linderman, and Michael Tarm, “[How AI-powered tech landed man in jail with scant evidence](https://apnews.com/article/artificial-intelligence-algorithm-technology-police-crime-7e3345485aa668c97606d4b54f9b6220)” *Associated Press* (19 August 2021)

- See also: 
  * Federal law enforcement: Rachel Metz, “[Facial recognition tech has been widely used across the US government for years, a new report shows](https://www.cnn.com/2021/06/30/tech/government-facial-recognition-use-gao-report/index.html?utm_source=optzlynewmarketribbon)” *CNN* (30 June 2021)
  * Urban surveillance in New Orleans: Michael Isaaca Stein, Caroline Sinders and Winnie Yoe, “[Neighborhoods watched: the rise of urban mass surveillance](https://surveillance.thelensnola.org/)” *Lens* (21 October 2021) 
  * Clare Garvie, Alvaro Bedoya, Jonathan Frankle, “[The Perpetual Line-Up: Unregulated Police Face Recognition in America](https://www.perpetuallineup.org/)” *Georgetown Law Center on Privacy and Technology* (18 October 2016)
  * Nicholas Bogel-Burroughs and Frances Robles, “[When Police Lie, the Innocent Pay. Some Are Fighting Back](https://www.nytimes.com/2021/08/28/us/false-police-statements.html)” *New York Times* (28 August 2021)

### Lab:
- [Lab: Facial recognition and racialized surveillance in law enforcement](https://github.com/kwaldenphd/facial-recognition)

### In-Class Work
- Discussion
- Final project proposal workshop

### Work Due Outside Class
- Reflection
- Final project proposal

## Week 13: Current Issues (part 2): What Gets Counted Counts

### Assigned Material
- Read:
  * Joy Buolamwini, “[We Must Fight Face Surveillance to Protect Black Lives: An Urgent Letter from the Algorithmic Justice League](https://onezero.medium.com/we-must-fight-face-surveillance-to-protect-black-lives-5ffcd0b4c28a),” *OneZero* (3 June 2020). 
    * Explore: [Algorithmic Justice League organization website](https://www.ajl.org/library/home)
  * Caroline Haskins and Ryan Mac, “[Here are the Minneapolis Police’s Tools to Identify Protestors](https://www.buzzfeednews.com/article/carolinehaskins1/george-floyd-protests-surveillance-technology)” *Buzzfeed* (29 May 2020). 

- Explore:
  * Electronic Frontier Foundation, “[Street-Level Surveillance](https://www.eff.org/issues/street-level-surveillance)” project
  * Electronic Frontier Foundation, “[Atlas of Surveillance: Documenting Police Tech in Our Communities with Open Source Research](https://atlasofsurveillance.org/about)” project
  * Electronic Frontier Foundation, “[Spot the Surveillance: A VR Experience for Keeping an Eye on Big Brother](https://www.eff.org/pages/spot-surveillance-vr-experience-keeping-eye-big-brother)” project

- Additional resources:
  * Charlie Warzel and Stuart A. Thompson, “[How Your Phone Betrays Democracy](https://www.nytimes.com/interactive/2019/12/21/opinion/location-data-democracy-protests.html)” *New York Times* (21 December 2019)
  * Dave Biscobing, “[‘Prime for abuse’: Lack of oversight lets Phoenix police add protesters to gang database](https://www.abc15.com/news/local-news/investigations/protest-arrests/prime-for-abuse-lack-of-oversight-lets-phoenix-police-add-protesters-to-gang-database)” *ABC15 Arizona* (24 May 2021)
  * Matt Cagle, “[Recordings show the California Highway Patrol’s aerial  surveillance of racial justice protests](https://www.aclunc.org/blog/recordings-show-california-highway-patrol-s-aerial-surveillance-racial-justice-protests)” *ACLU Northern California* (16 November 2021)
  * Urban surveillance in New Orleans: Michael Isaaca Stein, Caroline Sinders and Winnie Yoe, “[Neighborhoods watched: the rise of urban mass surveillance](https://surveillance.thelensnola.org/)” *Lens* (21 October 2021)
  * Domestication of prison tech: Erin McElroy, Meredith Whitaker, and Nicole E. Weber, “[Prison Tech Comes Home](http://www.publicbooks.org/prison-tech-comes-home/)” *Public Books* (18 August 2021)

### Lab:
- [Lab: Data visceralization and environmental scan](https://github.com/kwaldenphd/data-visceralization)

### In-Class Work
- Discussion
- Final project work time

### Work Due Outside Class
- Reflection

## Week 14: Final project work

### Assigned Material: None

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
