# Information

Some more information on the projects in my GitHub.

All of the projects were created because I wanted to have some utility and wanted to learn by creating them by myself.

Lately I've been adding and updating the use of Docker on many of the projects.

Below, the projects are ordered based on when they were started and active years marked in parentheses.

# Projects

## 2020

### [Ledivilkutin](https://github.com/Tomava/Ledivilkutin) (2020)

`Python`

This project came from a desire to automate creation of tedious code for an embedded electronic on one of the first courses in university. 

It taught about pysimplegui-library and making an undo-functionality even though it could be handled much better and not with dictionaries. I also learned how multiple components, inputter and the main functionality, can work together.


### [Minesweeper](https://github.com/Tomava/Minesweeper) (2020 - 2021)

`Python | Tkinter`

This was originally a self-selected and designed school project, but I made quite a few improvements after finishing the course. The structure of the code could be made a bit clearer as some functions are multipurposed in somewhat confusin ways. 

This project taught Tkinter.


## 2021

### [DailyNotifier](https://github.com/Tomava/DailyNotifier) (2021 -)

`Python`

This project taught me more about APIs and automatic web page scaping as well as some regular expression and HTML on the way. Also handling API-keys and using *.env* file to store them and not add them to version control. The project is nicely organized and easy to edit later on. Beautifulsoup-library could have been used instead of regex to read pages.


### [DiscordBot](https://github.com/Tomava/HelperBot) (2021 -)

`Python`

This was originally the first real project I made with Python, and I was just starting out as programmer as well. However, the original project did not utilize git and was poorly structured, so I rewrote the whole code which is this project.

In this project I learned about asynchronous functions, working with JSON-files, saving stuff to disk and discord.py-library. This was also one of the first times I utilized organizing code into different files. The organization is OK, but file naming could be better. Also, a reminder-class would benefit the code a lot.


### [TelegramBot](https://github.com/Tomava/CryptoTrackerBot) (2021 -)

`Python | Matplotlib`

This project taught about usage of APIs and requests, and I utilized Matplotlib-library that I had used quite a lot at the time to create different graphs.


### [Pairs](https://github.com/Tomava/Pairs_GUI) (2021)

`C++`

This was also originally a school project of which I improved afterwards. I learned more about C++ as well as created a Python-code that created randomized colors for the cards.


## 2022

### [Pytris](https://github.com/Tomava/Pytris) (2022)

`Python`

In this project I used and learned about classes and class inheritance in Python quite a bit. The classes could however be used a bit more optimally than what they currently are. Also, Pygame-library became familiar as well as some game design concepts.


### [Full stack open 2022](https://github.com/Tomava/FullStackOpen) (2022 - 2023)

`JavaScript / TypeScript / MongoDB | React / Node.js`

When I started this course I had no experience with JavaScript but I gathered a lot of knowledge about it during the course. React, Node.js and MongoDB became familiar as well. These skills were then used in a university course in a real software project where I mostly used Node.js and also learned TypeScript.


## 2023

### [TemperatureMonitor](https://github.com/Tomava/TemperatureMonitor) (2023 -)

`Python / PostgreSQL | Flask / MQTT`

This project's goal was to monitor and visualize the temperature inside and outside. This was the first project where I used sensors in IoT. Although, the measurement were simple to take with a Python library.

The frontend part is still on very early steps, but the backend and data collection is fully implemented. The data is collected to CSV files for easier manual viewing for now but PostgreSQL database is implemented in a separate branch. I also experimented and implemented MQTT protocol after learning about it theoretically which would move the backend API tasks from the data collecting unit to a more powerful server.

From this project, I learned multiple things about Flask, MQTT and databases, and I hope to learn some more about how to graph data on the frontend.


## 2024

### [SecureNotes](https://github.com/Tomava/SecureNotes) (2024)

`Python / TypeScript / PostgreSQL | Flask / Next.js`

This is a project with a freely chosen topic for a course where the focus is on secure programming principles.

For backend, I chose to implement it in Python and I chose Flask as I has some experience with it and wanted to deepen my knowledge. The database is implemented with PostgreSQL. For frontend, I chose TypeScript with Next.js as I was familiar with them. All the components are used withing Docker containers.

I wanted to focus my effort on secure and private note taking. I implemented secure sign up and logging in flows, where encryption keys and login hash are securely derived from the user password with different salts in the frontend. The point was to have an end-to-end encrypted solution where the backend is never able to decrypt the notes. Also TOTP is implemented. Although the implementations are secure, the usability is somewhat lacking in some parts. There are also some things I’m not quite satisfied with, such as how the navigation and data fetching is handled in the frontend and the structure of some API endpoints. Also the visual look is just bad with barely any CSS.

I learned and deepened my knowledge about the practical implementation of, for example, secure logins, sessions, encryption, SQL statements, data validation and CSRF.

### Infra (2024 -)

I've been focusing a lot in my server infrastructure with Ansible and other tools in a private repos.

I've wanted to move away from my manually created documentation, which would require manually running things, to an automated method where in the end everything could be recreated by scripts. This has been a gradual task with small (and sometimes bigger) additions at a given time.

With this task I've been learning a lot about Ansible as well as thinking about how to setup things in a way that makes automation of different tasks easier.
