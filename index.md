## Welcome to My GitHub Page

I will periodically update this page with new projects to showcase my abilities to work with various technologies, databases, data structures, and algorithms.

## About Me

I'm a Computer Science student, in my capstone course, at Southern New Hampshire University. I am focusing my efforts to earning a Software Engineering position when I transition out of the Navy in July.

## Code Review
[YouTube video](https://www.youtube.com/watch?v=VkhiAthh_xE&t=3s) of a code review that I performed on one of my projects.

## Code Snippets

As I decide on snippets to add to my page, I will showcase them here.

## Projects

### [Raspberry Pi Python with GrovePi HAT Simple Weather Station](https://github.com/Richard-WS-Allen/Raspberry-Pi-Weather-Station)
#### Narrative
In this artifact, I have a simple mock weather station. It was created to act like a weather station that would collect data and write to a json file for use in a dashboard. I made it last semester, with my Emerging Technologies course.
	I selected this item, because although it was a simple project, it has a lot of room for improvements. It also showcases control structures skills, reading and writing to files, and using I/O devices.
	To update this artifact, I added an API call, to showcase skills with IOT devices. I also cleaned up my code and followed standing coding practices to showcase my ability to critique myself, perform a code review, and improve upon existing software.
	In modifying this artifact, I realized my original plans for improvement went far beyond an improvement. I was starting to work on it and realized I was re-writing the entire thing to make it function as an alarm clock. So, I scrapped this idea. I went back and updated the FIXME statements I added in the code review. I wanted to showcase that I could efficiently critique my own work and creating a completely different project did not accomplish that. So, I decided to improve on the artifact, I would add the API call, and remove the sensor data. The device could now be set up for me to use as a quick check of the weather when I wake up using the LED lights and the LCD display. In the future I can go back and add to this project if I want to expand it to a “smart mirror” project that I have seen people use the Pi for before.

### [C++ Data Structures and Algorithms](https://github.com/Richard-WS-Allen/Data-Structures-and-Algorithms-cpp)

#### Introduction
The artifact(s) I worked with for this project was a binary search tree (BST) project, that had functionality to insert nodes, remove them, search, and perform an in-order traversal. I wanted to add another data structure to showcase skills working with other data structures and the ability to pick up on new data structures and the algorithms to use with them. For this, I made a new project, working with tries. Which sort of work like a BST, in that there are nodes and pointers to “children” nodes. In this case, there’s significantly more null nodes that never get used, unless you add a lot of nodes.
#### Inclusion
These data structures and algorithms are some that are harder to work with and implement than something like a linked-list or hash table. They’re not a data structure that you would use very often, so these artifacts especially showcase skills in working with lesser used structures and that I can work with unique structures when the time arises. Understanding data structures and algorithms show an ability to use the right structures and algorithms for the given occasion. Without understanding of the lesser known structures, one could get by with a more inefficient structure, but missed out on improved speed and functionality.
#### Meeting Objectives
The objectives I planned to meet for this course was to improve on the existing data structures and add a new one. I met the objectives I set for this and even caught a fatal error in my BST artifact. During the in-order traversal, a stack overflow error would occur when the CSV that it was reading values from was much larger. This was due to a recursive algorithm that worked well enough on a small BST, but when put through the ringer with a larger CSV, it made too many function calls to avoid this fatal error. I was able to go back and change the algorithm to not use recursion in this case. This especially showcases using the right algorithm for the data structure. Knowing when a recursive function will work and when it will not could be a crucial lesson that I learned.
#### Lessons Learned
In performing my modifications and enhancing the artifacts, I learned about tries and about their inefficiencies. These are data structures that have a very narrow usefulness. I would not be surprised if I never use them again. They’re difficult to work with and waste a lot of memory on null pointers. They only have a very few useful situations, such as autocomplete for text fields. I found this interesting in my research for this artifact, some companies like Google use these structures to speed up their suggestions for text fields. I also learned about ternary search trees, which was my original plan for this artifact. They kind of mesh tries and BSTs. They allow storing data in the nodes and limit it to three children nodes. This would have taken much more time to implement, so I settled on adding the trie functionality.

### [C# CRUD Operations on MongoDB Golf Course Collection] (https://github.com/Richard-WS-Allen/MongoDB-CRUD-Csharp)
#### Artifact
The artifact I worked with this week was a MongoDB CRUD API in Python. It was working with an established NoSQL database, that we had wrote code to perform the CRUD operations on, in a limited scope. This was from my CS-340 class, last semester (Jan-Feb 2020).
#### Inclusion
I chose this artifact because NoSQL databases are one of the emerging trends that I’ve noticed in the computer science field. I started noticing this pop up in job requirements as I was searching for jobs in my new career field. It’s important to be familiar with a broad field of technologies, maybe not so much early in a career, but definitely as you get more senior in your field. I wanted to go back and try this in a different language, because as much as I enjoy working in Python, I need to get more comfortable with other languages to be a reasonable choice as a new hire.
Not only does this artifact show that I can work with a wide range of technologies, it shows that I can pick them up quickly as well. I hadn’t worked with C# in almost a year, so this was a difficult task that required me to go back to the docs and pick up where I left off and dive deeper into another language outside my comfort zone.
#### Objectives
I met the objectives I set for myself in the beginning of the course. I developed an interface, used a different language to broaden my horizons, and made a database structure that could prove useful to a golf handicap calculator.
#### Reflection
In creating this artifact, I realized how much planning can save you time. The planning step would have been easier had I understood more about working with this technology stack. I was learning as I was going, which slowed me down significantly. As I researched next steps for my artifact, I would come to the realization that other steps could have been done better. This is an artifact that I’d like to re-visit even after graduation to brush up on this and improve my interface and database design.
