# Introduction
<p>
It was certainly a long journey, but now that I am finished with my time at SNHU I can reflect on my growth, both as a software developer and modern and as a life-long learner. I originally began at SNHU as a criminal Justice major. After taking a few classes I began to realize that this career path was not for me. I had always had great interest in technology and growing up I spent a lot of time tinkering with anything I could get my hands on. I had drifted away from this interest in the first few years of my adult life but as I began to search for new career options my love of technology and computers came back. I thought back on taking an introduction to webpage design class in high school and how much I enjoyed writing code and designing my own websites. From there it was not long before I had switched my major to computer science with a concentration in software engineering. 
</p>
<p>
Throughout my time in the Computer Science program at SNHU I have worked hard to learn and develop skills to prepare myself for a career in software. While I learned many valuable concepts, there are few in particular that stand out and better showcase my strengths.
</p>

# Self Assesment
## Team Collaboration
<p>
	It is challenging to learn to write software, and even more challenging to learn to do so with others in a way that allows for a collaborative and productive environment for everyone. In CS 310 Team Collaboration; a class specific to the software engineering concentration, I learned skills to do just that. I learned how to use Git and GitHub to work as a team concurrently on the same piece of software. I learned to create separate branches to work on our own assigned parts of a central project and merge them together once they were complete and tested. I also learned specific skills related to working with others that I feel often do not get mentioned at the developer level.</p>
<p>
	I learned the importance of balancing making sure everyone’s ideas are heard and being efficient and productive. Both the technical and personal skills were challenging to implement at times but having completed the course I now know I can use collaborative technologies like Git to work on software in a team with great success. I am also confident in my skills working with others in a professional and supportive environment.  
</p>

## Communication to Stakeholders
<p>
	Another set of skills which I learned in my degree that I feel stands out is the ability to communicate with the stakeholders of a software project. The business and communication side of software is as much a part of the process as the actual development, and having a good understanding of how this process works made a big difference for me as to how I felt about my understanding of software development and computer science as a whole. In this course I learned the Agile development process and undertook each different role within the process. 
</p>
<p>
	As a product owner, I had to directly communicate with investors of our project. I learned how to relay information about the project to the stakeholders as it was being developed. Something that stood out to me was when the course dictated that the stakeholders request additional functionality of the project in the middle of development. This taught us how to adapt to a challenging situation which often occurs in the real world. As the product owner I had to plan these new improvements with the team, while also balancing what was possible or not possible based on what the stakeholders were asking for. 
</p>
## Data structures and Algorithms
<p>
	When I reflect on things that I have learned, learning different data structures and algorithms stands out to me in value. I also found these concepts to be very interesting, and learning them, propelled me into an even deeper interest in the computer science field as a whole. I learned that having the right data structure is critical to being able to get the most value out of a project, and they are essential for developing software. Algorithms are equally as important to the value of software. I particularly found the efficiency of different algorithms with different applications to be interesting.  Most of this learning was done in CS-260 Data Structures and Algorithms course.</p>
<p>	
	In this course I gained experience working with and improving many types of algorithms and data structures. Some of these included vectors, hash tables, and tree structures for data structures as well as sort, search, and hashing algorithms. I learned that planning accordingly for a project by selecting the right data structure and algorithm is often times where developers have the most value. Understanding these concepts and applying them well is often the difference between that gets by and software that is magnitudes better.
</p>
## Software Engineering and Databases
<p>
	Throughout my degree I learned many aspects of software development over a broad scope of courses. It is difficult to discuss everything because there is such a wide variety of topics. I was introduced to basic programming concepts in CS-200 with Python as my introductory language, with Java being introduced next in IT 145 to solidify those basic concepts. I learned the importance of object-oriented design in IT-315 Object Oriented Analysis and Design, and the importance of testing in CS 320: Software Testing, Automation, and Quality Assurance. I also learned to work with graphical applications using C++ in CS 330: Computational Graphics and Visualization, and to develop mobile applications in CS 360: Mobile Architecture and Programming.
</p>
<p>	
	In the broad scope of topics, I learned and worked with, databases were often a key component. I learned the basics of SQL and built a database in DAD 220: Introduction to SQL. In CS 340: Advanced Programming Concepts, I learned to use MongoDB to build NoSQL databases, and built on software engineering concepts learned in introductory courses. I also took DAT 220: Fundamentals of Data Mining, which focused more on the data aspect of databases rather than the design. I found this class the most interesting out of the other database courses because it showed how data mining can be used to extract immense value out of a collection of data.
</p>
## Security
<p>
	Another key lesson in most of the courses I took was that security should always be a major concern when developing software. There are a seemingly endless number of things that can go wrong security wise if a security mindset is not used. Buffer overflows, insecure input, or lack of proper authentication can all become major security issues which in some cases can lead to security breaches which impact millions of people. In CS 405: Secure Coding, I conducted a secure code audit on C++ source code for a utility company management software. The audit documented dozens of security vulnerabilities from String formatted output, memory management, pointer errors, and more. I learned the importance of using security analysis software tools in combination with detailed manual reviews. In CS 410: Reverse Software Engineering I disassembled binary files and were shown how this can make security vulnerabilities apparent. This highlighted the importance of having secure code, as reverse engineering can always be used to find vulnerabilities which are left in code. 
</p>
<h2>Summary</h2>
<p>To best showcase my skillset relating to these topics, I chose to utilize a project which I originally developed in the CS 350: Emerging Systems Architectures and Technologies course at SNHU. The project originally charted data from a temperature and humidity sensor and displayed the readings on an LCD which changes color based on the readings. I go into much further detail in my code review and throughout my portfolio, but I wanted to provide a brief and concise review of what I planned to change originally versus what changes I ended up implementing. Please review the rest of the portfolio and the two GitHub repositories for a much more detailed analysis of my work. </p>

<h2>Originally Planned Enhancements</h2>
<ul>
	<li>Code cleanup and best practice review.</li>
	<li>Separation of code into functions and classes, such as the logic to append the data to the json file.</li>
	<li>New and improved graph of the data done in python as opposed to CanvasJS and HTML.</li>
	<li>Firebase Database which will store temp, humid, light under a timestamp for each recording, and user settings, with authentication. </li>
	<li>Fix of background LCD function and improvement colors.</li>
	<li>Command line menu with options to set settings or display the graph.</li>
	<li>Graphical user interface with same options as the command line menu. This could incorporate the chart, and display the current temperature and humidity using the real-time database with a weather-related background image.</li>
</ul>
<h2>Completed Enhancements</h2>
<p>I go into much more detail throughout the portfolio but in short, the only planned enhancement which I did not implement was the graphical user interface. I was able to make an extremely simple GUI which read the latest temperature and humidity from the database over a picture of a sunny sky. However, I ran into problems when I tried to do more than that. Essentially it was more of a graphical display, because the user could not interface with it at all. </p>
<p>
	I explored a few options for getting this done, but in the end, I decided that this was out of the scope of this project. A GUI would have been nice, but it would not provide much value over the graph I already had, and the interface through the Google Firebase Database. I chose to focus on developing the other improvements I planned and refining the final product.</p>
	
<p>I was able to complete all other enhancements as planned, although that does not mean I did not have complications. Many times, it felt that the improvements I was trying to make were impossible. For example, I had a hard time figuring out how to parse through the array of data when reading data from Firebase to use in my graph. Reading through documentation and much trial and error lead me to figure out how to do this, and it ended up being a pretty simple fix. You can see how I accomplish this in the json_reading.py file of the envPi repository. I also had difficulty creating the menu. I struggled both with organizing what I wanted the menu options to be and getting the menu loop to run without running the main loop of the envPi project. Again, my savior was documentation and trial and error. </p>

## Code Review

<p>This is my code review for my capstone project. Here I go over the project at the begining of the course. I demonstrate the original functionality, give an in-depth review of the code, and list the improvements I planned to make.</p>

<iframe src="https://drive.google.com/file/d/1wAWk0ekPUS0zROQoBSAq1Beo8ZwgxG_q/preview" width="640" height="480"></iframe>

## Capstone Project Introduction
[Original Project Repository.](https://github.com/John0207/cs350_original_artifact)

[Improved envPi GitHub Reposiotory.](https://github.com/John0207/envPi)
<p>
	The project, which I have named “EnvPi”, uses Python, HTML, and some JavaScript with CanvasJS. I orginally developed envPi in the CS 350: Emerging Systems Architectures and Technologies course at SNHU. The hardware consists of a grovepi+ board attached to a Raspberry Pi model 3 B+. The project takes data from a light sensor, a humidity sensor, and a temperature sensor attached to the Pi. If the light sensor indicates that the light is on then the temperature and humidity is displayed on an attached LCD screen, and recordings of the data are stored in an array and sent to a .json file.
</p>
<p>
        With the orignal version, the color of the LCD screen is changed to either red, green, blue, or light blue depending on the temperature and humidity. Values which are benchmarks can be set in the code. The data from the file is displayed in a graph using HTML and CanvasJS.
</p>
<p>
	The main reason I chose to include envPi orignally in my portfolio is because out of all the projects I have worked on it is the one that has the most real-world value. The project is far from perfect but nonetheless it would serve the purpose of an environment monitoring system and display. As is, this project does have a real use case in a garden for example. This means the improvements I make will improve on already existing real value as both software and a hardware device. I also enjoy working with IoT devices and technologies, specifically the Raspberry Pi. 
</p>
<p>
	The envPi also demonstrates solid programming foundational skills. I learned a lot originally developing this project in the course CS 350: Emerging Systems Architectures and Technologies, and it is difficult to mention them all, but I will mention the skills which I feel are most valuable. I use consistent and concise comments throughout the project making it easy to read and follow. I follow consistent indentation improving the readability further. I properly define all default variables such as the list for the background colors for the LCD. I correctly implement the use of functions to make the code more efficient, such as with the function for calculating the background color of the LCD. I also demonstrate use of a while loop and account for exceptions. 
</p>

## Software Engineering Enhancement
<p>The following improvements realting to software engineering and design were made to the envPi: </p>
<ul>
	<li>Consistent following of best practices and PEP8 guidelines.</li>
	<li>Renaming variables and functions to be clearer and more concise. As one example, I renamed threshold to light_threshold.</li>
	<li>Addition of consistent, clear, necessary comments. For example, I label with comments the different functions in the database file, so it is clear which ones work with the settings, which ones work with the sensor data, and so on.</li>
	<li>Consistent spacing and indentation, and continuous overall cleanup of the code.</li>
	<li>Functions
		<ul>
			<li>Many functions were extracted out of the code and separated into separate files based on what they do, with much clearer names. The database file is a great example of how I was able to do this. I got the idea to do this from watching Robert Martin’s series “Clean Code”. In one of the videos in the series, Martin mentions that this will “result in a lot of functions”, but that the tradeoff for this is code that “reads like well written prose”. While there are a few extra functions, a reader can clearly find where the execution of my code begins and because of the clearly named functions, understand how the code works overall quickly.</li>
			<li>The LCD background color function was reordered to check for most likely case first to be more efficient.</li>
			<li>I extracted code from the function which calculates the background color of the LCD into Boolean environment functions such as too_cold() which makes the code much more readable and easy to work with.</li>
		</ul>
	</li>
	<li>I created a Menu for the user to set settings or view the chart of data.</li>
	<li>I re-did the graph using the matplotlib python library.</li>
<p>
I learned a lot while making improvements to the software engineering and design of envPi. I learned that things that may seem to have a small impact like naming conventions, consistent spacing, and indentation can have a major impact on readability. I also noticed how much easier it was to make other enhancements once I improved the readability. 
</p>
<p>
	The most important lesson I learned was learning the value of extracting as many functions as possible and giving them well written names. Doing this made the main logic of code much easier to understand, especially for others reading my code. It also made improvements much easier going forward. After this change I felt as if my code was organized, and I knew exactly where to go to make changes as I decided upon changes to make. It made things much easier for me and I have learned it is well worth the time, effort, and extra code to get clean and organized code in return. 
</p>
<p>
The biggest challenge was deciding what needed to be extracted into a function, which functions should go into a separate file, and which parts needed to stay as – is. I was concerned about over complicating the code just to make more functions, so I asked my professor about it and I incorporated his feedback, which was that the functions I extracted were useful and improved the code.
</p>
<p>	
	Creating the logic for the menu was also challenging. It was difficult to get the code from the menu to run without the while loop executing. I was also unfamiliar with how to read and store input from the user in Python but through trial, error, and documentation I was able to get it to work as I wanted. 
</p>

<h2> Algorithmns and Data Structure Enhancement</h2>
<ul>
	<li>Improvement of while loop and algorithms:</li>	
	<ul>
		<li>Re-structured to fully account for possible exceptions.</li>
		<li>Algorithms account for all cases such as too cold case which previously caused an error.</li>
		<li>More graceful termination of loop with new exit message.</li>
	</ul>	
	<li>Expanding as needed based on improvements:</li>	
	<ul>
		<li>Algorithms and data structure added for sending and receiving data to and from Google Firebase.</li>
		<li>Algorithm to run new data chart in python.</li>
		<li>Algorithm for new menu, giving the user the option to set their own settings, or an option for viewing the graph and running the system.</li>
		<li>Algorithm to calculate a timestamp based on when data is recorded.</li>
		<li>Adjustment of algorithm for background color to check the most likely cases first.</li>
		<li>Reorganization of the structure of the data to be stored under a timestamp.</li>
		<li>Reorganization of the data structure to store user settings. </li>
	</ul>
<p>
		        I learned a great deal in developing the algorithm and data structure for this project. Learning how to make the code more readable and easier to work with was something I consider to be very valuable, and it was an area where I was lacking. Proper, consistent naming conventions, and spacing makes a big difference. Also, having functions which only do one thing made the code much easier to work with, and easier to understand as well. Seeing this improvement in my code will heavily impact how I write code form now on. This was a challenge for me as I had struggled with this in the past. After a few attempts I was able to figure out a good ratio of simple functions without over complicating the code. It felt like a big achievement when I had the functions separated as I wanted them.
	</p>
	<p>
         The importance of efficiency and testing were also things that I have learned working on these enhancements. Testing the algorithm to figure out it did not work if the temperature was too cold was a wake-up call of sorts to the importance of testing. I also learned that small changes in order of an algorithm can have a profound impact. Ordering the calculation of the color for the LCD by the most likely case made the program much more efficient. Improving what seems like minute details will be something I focus more on in the future. 
</p>
	
<h2> Database Enhancement</h2>
<p>Here are the improvements which I made to the envPi regarding the database:</p>
<ul>
	<li>I created a firebase database and authenticated it with the envPi project.</li> 
	<li>I added functionality to store temperature and humidity data, along with the brightness value underneath a timestamp in the Firebase database.</li>
	<li>I added functionality to store settings to determine what is too cold, too hot, too humid, etc.</li> 
	<li>All code relating to the storing of data is extracted into separate functions and moved to their own file, which is be referenced in the main file as a class.</li> 
	<li>The chart is created by reading data through a local JSON file, which is populated with data from the Firebase database.</li>
</ul>
<p>
	Making enhancements for the envPi database has been both challenging and rewarding. I am clearly able to see the benefits of separating the database into its own file and working with it and related functions by importing them as a class. This has made working with the database a lot easier. I noticed this when I changed the database to store user defined settings, and when I modified the data to be stored under a time stamp with new data(light sensor).</p>
<p> 
    I was mainly challenged trying to read the environment data from Firebase into a chart to chart the data. Originally, I had difficulty trying to use the data from the database with the chart. I was able to solve this issue by reading from the database into a local file and using that to populate the data. I also refactored the data structure so that the data was no longer under a unique ID number, making it much easier to read from. I have learned that while a design may be best suited for one purpose, it may cause issues with a different purpose. 
</p>
	
	

