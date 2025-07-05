# Smart-Schedule
The traditional method of creating college lecture timetables is a highly manual, laborious, and error-prone process.Educational institutions frequently grapple with scheduling conflicts, inefficient allocation of critical resources such as classrooms, laboratories, and faculty members, and significant administrative overhead. 
The "Smart Schedule" project proposes an intelligent, web-based solution to automate and streamline the complex process of college timetable generation. 
Our approach is centered on a modular design that separates concerns between data management, core generation logic, and user interaction. The system operates on a constraint-satisfaction methodology, where predefined rules (e.g., a teacher cannot be in two places at once, a room must have sufficient capacity, a batch cannot have two lectures simultaneously) are systematically applied during the allocation process. 
A greedy algorithm is employed to assign lectures to available time slots, rooms, teachers, and batches, prioritizing conflict avoidance. The user interface provides intuitive forms for inputting and managing all necessary entities, while the backend handles the computational heavy lifting, ensuring that the generated timetables are not only conflict-free but also optimally utilize available resources![image](https://github.com/user-attachments/assets/12b654ae-3e6e-4f7b-a36d-fc8d1a00e89c)
Frontend: 
HTML5: For structuring the web pages.
CSS3 (Tailwind CSS Framework): For modern, responsive, and utility-first styling, 	ensuring a clean and adaptive user interface across various devices.
JavaScript: For interactive elements, dynamic content updates (like dashboard counts), and client-side PDF generation. 
● Backend: 
	○   PHP (Hypertext Preprocessor): The server-side scripting language responsible 				for handling all business logic, database interactions, and dynamic content 				generation. 
● Database: 
	○   MySQL: A powerful and widely used relational database management system 				for storing all project data, including courses, teachers, rooms, batches, time slots, users, 		and generated timetable entries. 
● Server Environment: 
	○   XAMPP (Apache, MySQL, PHP, Perl): A free and open-source cross-platform web server 			solution stack package, used for local development and testing. This 	combination 			provides a solid foundation for a functional and user-friendly 	timetable generation             		system.
![image](https://github.com/user-attachments/assets/5c759aea-b207-4616-884f-3f299c4ec135)
