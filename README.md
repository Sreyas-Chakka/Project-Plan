### 19 September 2025

# Maze Runner

By: Pranav Cheedalla, Austin Santhakumar, Sreyas Chakka, Rishi Vallabhaneni, Afsar Arif  

![Maze Runner Logo](https://upload.wikimedia.org/wikipedia/commons/6/60/Maze_Runner_Logo.svg)


---

## B. Summary

Maze Runner is a game where the player must guide a runner through a maze filled with obstacles to reach a finish line or a checkpoint. The core objective is to reach the checkpoint within sixty seconds. This time limit adds pressure to every decision, forcing the player to think quickly and test their reaction speed.  
As the runner progresses, obstacles will start to appear throughout the maze to increase the difficulty. These obstacles may take the form of moving walls, barriers, or traps that force the player to avoid them, or the game will end. To ensure fair gameplay, the system is designed so that at least one valid path to the checkpoint always exists, no matter how many obstacles there are.  
Lastly, clarity and usability are central to the design of the Maze Runner game. Checkpoints will be highlighted with some sort of distinct visual cues, making them easy for the player to identify. Obstacles are also visually distinct, ensuring the player can quickly recognize hazards and have ample time to avoid them. In the easier part of the game, the user will have exceedingly more time to avoid the obstacles, and as the user progresses, they will have a decreasing amount of time to avoid them. These clear visual elements help make a user-friendly experience, allowing players to focus on the actual game and their movements rather than struggling to understand how the game works.

---

## Why this work needs to be done (Why?)

### a. Relevance or importance of problem
Maze runner games are engaging because they combine strategy, problem-solving, and real-time decision-making.These games without properly designed challenges may quickly lose value. The same or predictable maze layouts allow players to memorize paths, reducing the overall experience to a repetitive task. By introducing obstacles and requiring players to adapt, the project aims to have engagement, improve replayability, and enhance thinking skills making it more entertaining. This makes the problem important for designing not only an enjoyable game but also one that demonstrates principles of adaptable game mechanics.

### b. Background information to educate the reader
Maze games have their origins in the arcade era of the 1970s, with one of the earliest examples being Amazing Maze (1976), where players navigated through a generated maze to reach an exit before their opponent. Now, the Maze runner game is a genre where players must navigate from a starting point to a certain checkpoint while avoiding obstacles like walls, traps, or enemies. Usually, the difficulty of the maze is increased through the sizes, smaller time limits, or additional obstacles. To maintain long-term interest, the use of obstacle generation has become a modern approach to creating challenging yet fair environments.

### c. Previous related work by others — literature review with credible sources
Past work in game design shows that adding variety and challenge keeps players interested. Smith et al. (2011) explain that generating random content makes games less predictable but still fair. Csikszentmihalyi (1990) says games should balance challenge with player skill, and Salen and Zimmerman (2004) note that obstacles make games more engaging. These ideas support adding obstacles to maze runner games.

### d. Detailed problem description, as you now understand it
The main problem is that the maze runner games without dynamic obstacles become too easy and predictable. If the maze layout and barriers never change, players can memorize the solution, which reduces both the challenge and replay value. Our project ensures these problems are met by creating a system that spawns obstacles each time the game is played, while making sure there's at least one valid path to the checkpoint keeping the users engaged and making sure it is solvable.

---

## Objectives (What?)

Define the scope of work and clearly state the project objectives, including the following:  
 i. Design specifications in specific, quantitative terms  
 ii. Critical design issues, constraints, limitations  

The Maze Runner game requires the player to pass checkpoints in 60 seconds to achieve the next level. Each level will have obstacles, and as the player goes through each level, the obstacles they will have to pass will be harder. To ensure that the player can pass the level, the maze will have a structured placement of obstacles that will have an acceptable path for the player to cross.  
Some critical design issues are that we have to consider the obstacle course placements so that there aren't breaks or dead ends so that the player can’t move through the maze. The obstacles should have a limit to how hard it can be, but yet it should be fun and fair to the player. The player should be able to play based on how they read the obstacles and adapt to it. They should also be manageable to beat within the 60 second constraint as well as any design/user constraints. The overall issue is to fix any controls and features from the player’s perspective and improve the game even further.

---

## First Design and Problem-Solving Process

### Steps:
- Define Core mechanics (generating mazes, movement, enemies, score)  
- Research maze layouts and prototype small aspects of game  
- Build a prototype of full game  
- Add feature (enemies, timing, checkpoints/levels)  
- Playtest, refine, and balance difficulty  
- Finalize the visuals, fix bugs, and optimize  

### Generating Solution Concepts:
- Do team brainstorming  
- Look at methods to generate mazes  
- Build different levels   
- Review similar maze-based games for inspiration.  

### Analyzing Performance:
- Technical: frame rate, responsiveness, loading.  
- Gameplay: difficulty, fairness, pacing.  
- User feedback: surveys and playtests.  

### Alternatives:
- Maze design: random vs. handcrafted vs. hybrid.  
- Game view: 2D top-down, 2D side-scroller, or 3D.  
- Enemy AI: simple patrol vs. adaptive chase.  
- Controls: keyboard-only vs. keyboard + mouse.  

### Choosing the Best Alternative:
- Evaluate based on feasibility, fun factor, and clarity.  
- Prioritize engaging gameplay over unnecessary complexity.  
- If the initial design fails (e.g., maze too confusing), switch to alternate (e.g., hybrid maze)  
- Revise and resubmit proposal if major design changes occur  

---

## Project Management

**Project Duration:** 10 weeks  

The schedule will be updated continuously based on team progress.  

Weekly check-ins will be used to track tasks, reassign responsibilities if needed, and log new tasks required from testing.  

Each Iteration is dependent on the previous, except iteration 1, due to it being the first. We will not be able to move to the next iteration until the previous iteration is fully complete.  

### Iteration 1: Maze and Obstacle Design (Week 1)
Assigned to:  
- Task 1.1: Brainstorm maze layouts — *Rishi & Sreyas*  
- Task 1.2: Identify and sketch obstacle ideas — *Pranav and Austin*  
- Task 1.3: Define valid path logic for solvability — *Rishi & Sreyas*  

### Iteration 2: Basic Game Prototype (Weeks 2–4)
- Task 2.1: Code maze generator prototype — *Afsar*  
- Task 2.2: Implement player movement controls — *Austin*  
- Task 2.3: Create non-functional obstacle placeholders — *Pranav*  
- Task 2.4: Add timer countdown & checkpoint system — *Afsar*  

### Iteration 3: Functional Gameplay (Weeks 5–6)
- Task 3.1: Implement obstacle mechanics (moving walls, traps) — *Rishi*  
- Task 3.2: Integrate random maze generator — *Afsar*  
- Task 3.3: Enable level progression/checkpoints — *Sreyas*  
- Task 3.4: Begin initial playtesting — *Everyone*  

### Iteration 4: Testing and Refinement (Weeks 7–8)
- Task 4.1: Conduct structured playtests and collect feedback — *Everyone*  
- Task 4.2: Debug controls, obstacle placement, and timer — *Austin & Afsar*  
- Task 4.3: Refine gameplay balance (fairness/difficulty pacing) — *Pranav & Sreyas*  

### Iteration 5: Final Game and Documentation (Weeks 9–10)
- Task 5.1: Finalize visuals, polish UI/UX — *Pranav & Sreyas*  
- Task 5.2: Prepare technical documentation — *Austin & Afsar*  
- Task 5.3: Compile project report and demo materials — *Everyone*  
- Task 5.4: Deliver final demonstration — *Everyone*  

---

## Deliverables for each iteration

The plan into designing and implementing the game to life can be created through many iterations. The plan is to design the maze, brainstorm ideas for obstacles, figure out where to place those obstacles, and draw out a valid path for the player to pass. This is the first iteration that should take a week to do. The second iteration is to code a basic layout to code the Maze Runner game, which will include the player movement, a functioning maze generator, obstacles placed (does not have to be functional), time countdown, and a functioning checkpoint. This process will take about 2-3 weeks. The third iteration will include functioning obstacles, player movements, random maze generators, and a next level check. After this iteration, it is time to review and test our game for feedback and find issues. We will take a week to document and report any issues, checkpoints, and progress. If there are issues, we will go back to prototyping and fixing any said issues. This iteration will take 1-2 weeks. The 5th iteration will consist of a full functioning game of the Maze Runner with all the features and documentation presented and be ready for a demonstration.

---

## Team Qualification

### Pranav Cheedalla
I have developed technical skills in C++, Java, Python, HTML/CSS, React, TypeScript, SQL, and Next.js, along with proficiency in Microsoft Word and Excel for documentation. I also have experience in application development, which has strengthened my ability to work across both front-end and back-end technologies. Professionally, I worked as a Software Developer Intern at Darling Ingredients, where I applied my technical knowledge to real-world projects and gained valuable experience. In addition, my coursework in CS 2336 (Computer Science II), CS 2340 (Computer Architecture), and CS 2305 (Discrete Mathematics for Computing) has provided me with experience for this project.

### Austin Santhakumar
I have experience with programming languages such as C++, Java, JavaScript, Python, SQL, and Bash/Shell, and frameworks including Docker, Flask, Git, Node.js, PyTorch, React.js, Nuxt, REST APIs, Vader, and Axios. I am also skilled with tools like VirtualBox, Wireshark, Git/GitHub, TensorFlow, and VS Code. My background includes a role as a Software Development Intern at T.R. Hoover and academic coursework in CS 2336, CS 2340, and CS 2305, which have strengthened my technical and problem-solving abilities.

### Sreyas Chakka
I have experience with Python, Java, JavaScript, HTML/CSS, C++, SQL, Pandas, Numpy, React, and Nuxt, as well as tools like Git/GitHub, VS Code, Thymeleaf, Spring Boot, and TensorFlow. I’ve worked as a Software Intern at DXC Technologies and a Software Development Intern at T.R. Hoover, and my coursework in CS 2336, CS 2340, and CS 2305 has further strengthened my software development skills.

### Rishi Vallabhaneni
I have experience with multiple programming languages, including Python, Java, JavaScript, C++, and React. I am proficient in Microsoft Office tools such as Word, Word Expert, Excel, Excel Expert, and PowerPoint. My job and course experience includes an internship at iStart Valley, serving as a PURE Youth Director and Taekwondo Assistant Director. I also completed coursework in CS 2336, CS 2340, and CS 2305, which has provided me with a strong foundation in computer science principles. 

### Afsar Arif
I have experience with Python, Java, JavaScript, C++, TypeScript, HTML, CSS, SQL, React, Next.js, Flask, Spring, Spring Boot, NestJS, PostgreSQL, and MySQL, and I am proficient with tools such as Docker, Git/GitHub, NPM, Maven, Tableau, SAP HANA, Snowflake, and VS Code. My background includes roles as a Data Engineering Intern at Oklahoma Gas & Electric and a Data Analyst Intern at Webacy, as well as project experience through HackTX 2023 – BenefitU and a Job Market Analysis Project. I have also strengthened my technical foundation through coursework in CS 2336, CS 3345, and CS 4349.

---

## Resumes

### Sreyas Chakka — Resume
EDUCATION [& Certifications]
University of Texas at Dallas, Richardson, TX, Computer Science Major 
Deans List Fall 2024 & AES Scholarship Applicant   
EXPERIENCE
 
T.R. Hoover – Software Development Intern                                                                    	             August 2025 - Present
·   	Built full-stack web app with a database to centralize 500+ housing, youth, outreach, and transportation records.
·   	Designed dashboards and forms for tracking participation, volunteer hours, and supply distribution.
·   	Delivered a standalone website with an integrated database, reducing reliance on 75 % of external platforms.
 
Software Intern – DXC Technologies (Dallas)                                                                                   May 2025 - August 2025
Observed and assisted software engineers in debugging and testing, reducing bug resolution time
Learned agile software development practices such as 3+ sprint planning and code reviews.
Gained exposure to enterprise IT solutions in cloud computing and system integration, impacting 1,000+ users.
 
Intern and Lead at NRIVA for Software Development (Dallas)                                                       May 2024 - August 2024 
Purpose: Created an app based on 300+ community survey responses to identify crucial features.
Front End: Built front-end with HTML, CSS, and JavaScript, reaching 200+ active community members.
Back End Development: Developed server-side logic and integrated database, managing 2,500+ records.
PROJECTS
Task Management Application
Built a full-stack task management application with a user interface for creating, updating, and managing tasks.
Designed the frontend using React in VS Code, ensuring a responsive and modern experience with 50+ users.
Integrated with backend APIs for real-time task updates and deployed via Microsoft Azure App Services.
 
Smart Finance AI Web App
Developed a cloud-hosted financial web application using Spring Boot and Thymeleaf, coded in VS Code.
Implemented features such as real-time financial predictions, responsive UI, and secure user interaction.
Collaborated with tools like GitHub and VS Code extensions to streamline development and version control.
Backend Stock Trading using Data Integration
Designed and implemented a backend system for automated trading with real-time market data integration.
Developed trading strategies with risk management rules (stop-loss, position sizing, portfolio exposure).
Integrated live data feeds and broker APIs for execution.
TECHNOLOGIES
Programming Languages: Python, Java, JavaScript, HTML/CSS, C++, SQL, Pandas, Numpy
Tools: Visual Studio Code, Git basics, TensorFlow, Thyme Leaf, Springboot
 
Certifications and Awards
Python Certification from CodeHS & Coddy Tech
Coddy Tech certifications for HTML, JAVA, and SQL
UT Austin Certification for Post Graduate Artificial Intelligence and Machine Learning: Business Applications
 

### Austin Santhakumar — Resume
      Austin Santhakumar
 austin.santhakumar@gmail.com •   (469) 986-5749 • lwww.linkedin.com/in/austinsanthakumar 

EDUCATION

University of Texas at Dallas  | Richardson, TX                                                                        	Aug 2024 - Present
B.S. in Computer Science                                                                                                  	              

TECHNICAL SKILLS

Languages: C++, Java, JavaScript, Python, SQL,  Bash/Shell
Frameworks: Docker, Flask, Git, Node.js, PyTorch, React.js, REST APIs, Vader, Axios
Tools: VirtualBOx, Wireshark, Git/Github, VS Code

EXPERIENCE
TR Hoover CDC | Dallas, TX	Aug 2025 - Present
Software Developer Intern	 
Supported 5+ Azure cloud adoption projects, contributing to workload migration, scalability planning, and hybrid deployment.
Integrated client datasets into Azure Storage and Azure SQL, strengthening cloud infrastructure and data pipeline skills.
Collaborated in account planning sessions, applying risk, cost, and security practices to optimize enterprise cloud solutions
Kumon | Irving, TX                                                                          	July 2023 - Present
Data Entry Operator	 
Input and maintained 100+ student records weekly, ensuring reliable tracking of math and reading progress.
Analyzed progress data for 50+ students, identifying learning gaps and adjusting workloads to improve completion rates by 15–20%.
Organized and digitized student progress data, reducing retrieval time by 30% and supporting data-driven instructional strategies.
Microsoft  | Las Colinas, TX	May 2023
Job Shadow – Senior Customer Success Account Manager (Azure)	 
Supported 5+ Azure cloud adoption projects, contributing to workload migration, scalability planning, and hybrid deployment.
Integrated client datasets into Azure Storage and Azure SQL, strengthening cloud infrastructure and data pipeline skills.
Collaborated in account planning sessions, applying risk, cost, and security practice to optimize enterprise cloud solutions



PROJECTS

Customer Priority Inbox| Flask, React                                                                                             	                August 2025
Built a full-stack email prioritization app that applied NLP techniques to rank messages by urgency, improving triage accuracy by 30%.
Reduced customer response times by 40% through a React dashboard that auto-sorted, filtered, and highlighted 200+ test emails.
Integrated a Flask API with sample email ingestion workflows, laying the foundation for Gmail/IMAP integration.
Penetration Testing Lab | VirtualBox, Wireshark                                                                                           	  September 2024
Enhanced incident response readiness by 35% by simulating 10+ real-world attacks (privilege escalation, brute force, traffic interception).
IIncreased security testing coverage by 40% by deploying and managing 4+ isolated VMs (Kali, Ubuntu) for penetration testing and monitoring.
Accelerated threat detection by capturing and analyzing 50,000+ packets in Wireshark, identifying anomalies with 90% accuracy in lab exercises.

### Rishi Vallabhaneni — Resume
RISHI VALLABHANENI
972-989-1870 | rishchowdary@gmail.com | Dallas, TX |
www.linkedin.com/in/rishi-vallabhaneni 

EDUCATION												
The University of Texas at Dallas, Dallas, TX      			                        (Anticipated graduation date)  May 2028
Bachelor of Science, Computer Science    GPA 3.74   AES Scholar

SKILLS													
Technical Skills: C++, Java, Python, React
Languages: Telugu, English
Certifications: Microsoft Word, Microsoft Excel, Microsoft Powerpoint, Microsoft Word Expert, Microsoft Excel Expert, Java, Python, OSHA

EXPERIENCE 												
PURE Youth, Irving, Texas				                                               	                  July 2022- May 2024
Director											
Provided guidance and support to youth in the community on a variety of issues
Organized activities, workshops and events for youth to engage in
Participated in public speaking engagements to promote positive youth development initiatives
iStart Valley, California, USA				                                                                   October 2022 - May 2023
Intern
We as a team are to create MediAlgnosis (software to assist the healthcare field) presentation pitch for investors about AI and entrepreneurship
Use presentation skills to make pitch more advertising

PROJECTS												
Pose Perfect										              		 February 2025
Developed an app that analyzes sitting and standing poses from uploaded photos to define good posture and provide personalized feedback for improvement
Built a responsive React web app with secure authentication that lets users upload posture images and receive AI-powered feedback to improve alignment
Revolutionizing Commodity Trading									        April 2025
Create an automated hedge fund using AI that takes in data of the market and trends that will make decisions in trading
Built a websites that analyzes satellite imagery, real time signal dashboard, and executes trades within seconds for companies and vendors

LEADERSHIP & COMMUNITY INVOLVEMENT									
Coppell ATA, Irving, Texas								         	   July 2022 - May 2024
Instructor’s Assistant
Developed and implemented beginner Taekwondo classes for children ages 5-7 years old
Instructed students in the proper techniques of blocking, punching, kicking, and sparring
Demonstrated drills to improve agility, balance, and coordinated


### Pranav Cheedalla — Resume
Pranav Cheedalla
Irving, TX | 972-946-4177| pxc230033@utdallas.edu
https://www.linkedin.com/in/pranav-cheedalla-3b18a628a/
 
EDUCATION
The University of Texas at Dallas, Richardson, TX                                                     Expected May 2027
Bachelor of Science, Computer Science
·   	Coursework: Data Structures/Algorithms, Computer Science ll, Computer Architecture
·   	Erik Jonsson Academic Success Scholarship Recipient
 
TECHNICAL SKILLS
Programming Languages: Java, Python, C++, HTML/CSS
Other Skills: Microsoft Word, Microsoft Excel, Bilingual
 
PROFESSIONAL EXPERIENCE
Tomorrow's Leaders Today – Software Developer Intern                                            Aug 2025 - Present
Developed a full-stack web application using Next.js, Node.js, SQLite, & Prisma enabling automated grant app
Bank of America – Programming Development Shadowing                            	      	                    	             May 2025 – August 2025
·   	Learned about secure coding standards and compliance requirements in the finance sector.
·   	Attended team stand-ups and sprint planning meetings to understand project workflows.
·   	Observed collaboration between developers, QA engineers, and project managers.
Darling Ingredients - Programming Development Intern                 	        	                       	             June 2024 – August 2024
·   	Assist in developing and maintaining internal software tools and applications.
·   	Write, test, and debug code under the guidance of senior developers.
·   	Document code changes and technical processes clearly and accurately.
Medical City - Assistant                                                                                        	     	   	                       	             June 2023 – August 2023
·   	Greeted and guided patients and visitors at the front desk with professionalism and care.
·   	Assisted staff with non-clinical tasks, including document delivery and supply runs.
·   	Supported daily operations by communicating effectively with medical and admin teams.
 
PERSONAL PROJECTS
CommodAI                                                                                                                   	         	                	            	                      	          April 2025
·   	Designed and built a prototype system to extract and process real-time data from websites, enabling analysis of commodity-related trends.
·   	Implemented predictive models to forecast price fluctuations based on extracted web data, supporting more informed decision-making.
 
CAMPUS INVOLVEMENT
Association for Computing Machinery, Mentee                                                                      	       	            January 2025 - May 2025
AIMD, Member                                                                                                                        


### Afsar Arif — Resume
AFSAR ARIF 
+1 (469)-636-2699 | Mohamedafsar.arif@gmail.com 
linkedin.com/in/afsararif/ |github.com/AfsarArif 
EDUCATION 
University of Texas at Dallas- Bachelors of Science, Computer Science May 2026 Relevant Coursework: Data Structures and Algorithims, Advanced Algorithim Design and Analysis, Aritificial Intelligince 
WORK EXPERIENCE 
Data Engineering Intern | Oklahoma Gas & Electric Jul 2024 - Present Engineered efficient ETL pipelines using SAP HANA and SQL to streamline data extraction, transformation, and loading processes, enhancing data accessibility and reliability. 
Developed and maintained 100+ data views in SAP Datasphere, ensuring efficient data modeling and integration for streamlined access to accurate, real-time insights across the organization. 
Designed and implemented Snowflake data pipelines, tagging over 500 tables to bolster governance and compliance efforts. Led data migration initiatives from Azure staging environments to Snowflake, successfully managing the transition for 70% of all stages while minimizing disruption to existing workflows. 
Data Analyst Intern | Webacy Jul 2024 - Sep 2024 Analyzed and categorized 40+ smart contract vulnerabilities, refining expertise in data categorization and risk assessment methodologies. 
Executed frequency and correlation analysis on risk tags to identify prevalent vulnerabilities and their interrelationships, demonstrating proficiency in data manipulation and statistical analysis. 
Applied unsupervised machine learning techniques for cluster analysis, uncovering patterns and trends among smart contracts to effectively profile and mitigate risks. 
Refined risk tags by integrating insights from cluster analysis, ensuring that categorized vulnerabilities accurately aligned with identified patterns for more effective risk mitigation. 
PROJECTS 
Back-End Developer | Personal Project - Job Market Analysis May 2024 Comprehensive Analysis of the Data Analyst Job Market 
Developed SQL queries, scripts, procedures, functions, triggers, for data manipulation in tables and views. Translated business questions into actionable SQL queries, extracting valuable insights on salary trends, skill demands, and job market opportunities. 
Created compelling visualizations and dashboards using tools like Tableau to effectively communicate findings and support data driven decision-making. 
Tech Stack: SQL, PostgreSQL, Visual Studio Code, Git, GitHub, Tableau 
Product Manager, Back-End Developer | HackTX 2023 - BenefitU Oct 2023 Flask application for employees benefits 
Leading a team of four, I fostered innovation, assigned strategic roles, and planned to meet product objectives. With Beautiful Soup web scraped levels.fyi and created a data collection with 1000+ entries using MongoDB Atlas. Created a Flask app that connects our data collection and user-centered chatbot to a dedicated front end. 
Tech Stack: Python, Flask, OpenAi, Figma, MongoDB Atlas, Rest API, Beautiful Soup 
ORGANIZATIONS 
Vice President of Internal Affairs | Kappa Theta Pi Sep 2023 - Present Member | ACM, Association for Computing Machinery Jan 2023 - Present 
TECHNICAL SKILLS 
Front End | React, NextJS, Javascript, TypeScript, HTML, NodeJS, CSS, Styled-Components 
Back End | Flask, Spring, Spring Boot, Spring Security, NestJS, PostgreSQL, MySQL 
Languages| Python, Java, JavaScript, C++ 
Tools| Docker, Git, NPM, Maven, Tableau, SAP HANA, Snowflake 
AWARDS 
Won first place at HackTX 2023 for the challenge: ACM for change. Link:https://devpost.com/software/benefitu 
