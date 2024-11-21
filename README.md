<h1 align="center">Automation of ID Card Development with QR CODE</h1>

<br/>

![GEENFY](https://github.com/user-attachments/assets/cb138e44-bd2e-472f-ba4f-ff5dd4939195)

<div align="center">
	<a href="https://www.canva.com/pt_br/" ><img src="https://img.shields.io/badge/Canva-%2300C4CC.svg?&style=for-the-badge&logo=Canva&logoColor=white"/></a>
	<a href="https://www.djangoproject.com/"><img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=green"/></a>
	<a href="https://www.figma.com/"><img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/></a>
	<a href=""><img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/></a>
	<a href=""><img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E"/></a>
	<a href="https://www.notion.so/pt-br"><img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white"></a>
	<a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue"/></a>
	<a href="https://www.sqlite.org/" ><img src="https://img.shields.io/badge/Sqlite-003B57?style=for-the-badge&logo=sqlite&logoColor=white"/></a>
	<a href="https://trello.com/pt-BR" ><img src="https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=trello&logoColor=white"/></a>
	<a href="https://code.visualstudio.com/"><img src="https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white"/></a>
</div>


<h2>Menu</h2>

<ul>
  <li text-decoration="none"><a href="#Automation-of-ID-Card-Development-with-QR-CODE">💳Title</a></li>
  <li text-decoration="none"><a href="#Project-Planning">📅Project Planning</a></li>
  <li text-decoration="none"><a href="#Project-Planning">🎯Project Objectives</a></li>
	<ul>
		  <li text-decoration="none"><a href="#Project-Planning">🎯General Objectives of the Project</a></li>
		  <li text-decoration="none"><a href="#Project-Planning">🎯Specific Objectives of the Project</a></li>
	</ul>
</ul>

<h2>Project Planning</h2>

<div align="justify">
📅The project developed by the team aims to automate the process of issuing identification cards for students enrolled in FIC courses (Initial and Continuing Training) at the SENAI Jundiaí unit. Currently, this responsibility falls to the institution's administrative office, and the task is performed entirely manually. This procedure, in addition to being repetitive, requires a considerable amount of the staff's time, negatively impacting the performance of other activities and compromising the office's operational efficiency.

Every 15 days, new FIC course classes are formed, with an average of 20 students enrolled per class. The current process requires staff to issue each student's identification card individually, which is time-consuming and prone to operational errors.

Given these challenges, the team proposed the development of an automation solution based on RPA (Robotic Process Automation) to optimize the card issuance process. This automated solution aims not only to reduce the time spent on this task but also to improve the administrative workflow, allowing staff to focus on other responsibilities.

The automation was implemented through a web application, which serves as the entry point for the process. Staff responsibilities will be simplified to uploading a file containing the new students' data, from which the automated system will efficiently and accurately generate the identification cards.

This solution, therefore, seeks to enhance agility, reduce errors, and free up the institution's staff for more strategic activities, ultimately increasing the overall productivity of the administrative office.
</div>

<div align="center">
	<img src="https://github.com/user-attachments/assets/16e1e0f3-35e1-4403-95bf-68adc4d78b66" alt="Project Planning">
	<p>Bissoli, Giovana. , PDF file. London: Great Publishing House, 2010. Accessed December 1. 2012, http://www.books.google.com</p>
</div>

<h2>Project Objectives</h2>

<h3>General Objectives of the Project</h3>

<div align="justify">
🎯The main objective of this project was to develop an automation solution through RPA (Robotic Process Automation) to streamline the issuance of ID cards for students enrolled in FIC (Initial and Continuing Education) courses at SENAI Jundiaí. The solution aims to reduce the manual workload of the administrative office, speeding up the issuance process and minimizing the time spent on repetitive tasks.

The automation was implemented using a Raspberry Pi 4, a microcomputer that served both as a host for the web application and as a platform to execute the automation scripts. Through this platform, users can upload files containing student data, which will be automatically processed by the RPA to generate the ID cards.
</div>

<h3>Specific Objectives of the Project</h3>

<div align="justify">
🎯The project's specific objectives can be divided into the following areas:

<br/>
<br/>

<ul>
	<li>RPA (Robotic Process Automation):</li>
		<ul>
			<li>Develop a Python script using the Pandas, Selenium, and Pyautogui libraries, each fulfilling a specific function in processing and automation.</li>
			<li>Create a script capable of opening, manipulating, and processing uploaded files to extract necessary information and automate the ID card issuance process within the institution's systems.</li>
			<li>Implement a script to return the generated files to the web platform, allowing users to download the finalized ID cards.</li>
		</ul>
	<li>Web Platform Development:</li>
		<ul>
			<li>Develop a homepage that redirects users to the login screen, ensuring intuitive navigation.</li>
			<li>Create a login screen that ensures only pre-registered and authorized users can access the automation system.</li>
			<li>Implement an upload screen where users can submit files containing data of new students enrolling in courses.</li>
			<li>Develop a download screen, enabling users to download the files generated after completing the automation process.</li>
			<li>Implement a control mechanism to prevent simultaneous file uploads, avoiding the machine running multiple tasks at the same time and preventing overwriting of ongoing activities.</li>
		</ul>
	<li>Use of Raspberry Pi 4:</li>
		<ul>
			<li>Use the Raspberry Pi 4 as a server to host the web system.</li>
			<li>Configure the Raspberry Pi to run the developed automation scripts.</li>
		</ul>
	<li>API Development:</li>
		<ul>
			<li>Create an API (Application Programming Interface) to enable efficient integration between the website and the automation scripts, ensuring a smooth and secure data flow between the web application and the automation processes.</li>
		</ul>
	<li>Automation with Python:</li>
		<ul>
			<li>Implement a Python-based solution combining the functionalities of the following libraries:</li>
				<ul>
					<li>Pandas: responsible for data manipulation and analysis of the uploaded files.</li>
					<li>Selenium: used to automate interactions with the ID card issuance system by identifying elements on the website.</li>
					<li>Pyautogui: responsible for automating actions such as mouse clicks and keyboard inputs, simulating human interaction with the system when needed.</li>
				</ul>
		</ul>
	<li>Security and User Management:</li>
		<ul>
			<li>Implement an access control system that allows the administrator (coordinator) to register, list, edit, and remove users, ensuring the security and restricted access to the automation system.</li>
		</ul>
</ul>
</div>
