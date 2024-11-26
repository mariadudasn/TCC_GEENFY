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
  <li text-decoration="none"><a href="#Project-Objectives">🎯Project Objectives</a></li>
	<ul>
		  <li text-decoration="none"><a href="#General-Objectives-of-the-Project">🎯General Objectives of the Project</a></li>
		  <li text-decoration="none"><a href="#Specific-Objectives-of-the-Project">🎯Specific Objectives of the Project</a></li>
	</ul>
  <li text-decoration="none"><a href="#Project-Justification">📝Project justification</a></li>
  <li text-decoration="none"><a href="#Methodology">⚙Methodology</a></li>
		<ul>
		  	<li><a href="#Programming-Language">💻Programming Language</a></li>
				<ul>
					<li><a href="#Python-v-3-12-4">🐍Python v. 3.12.4</a></li>
					<li><a href="#JavaScript">☕JavaScript</a></li>
				</ul>	
			  <li><a href="#Markup-Language">🖱Markup Language</a></li>
				<ul>
					<li><a href="#HTML5">📄HTML5</a></li>
					<li><a href="#CSS3">📱CSS3</a></li>
				</ul>
			<li><a href="#Framework">🖥Framework</a></li>
				<ul>
					<li><a href="#Django-5-0-7">📌Django 5.0.7</a></li>
					<li><a href="#Cypress">▶Cypress</a></li>
				</ul>
			<li><a href="#Libraries">📕Libraries</a></li>
				<ul>
					<li><a href="#Selenium-4-0">✅Selenium 4.0</a></li>
					<li><a href="#PyAutoGUI-0-9-54">⌨PyAutoGUI 0.9.54</a></li>
					<li><a href="#Pandas">🐼Pandas</a></li>
					<li><a href="#Django-Rest-Framework">📁Django Rest Framework</a></li>
					<li><a href="#OS">🐍OS</a></li>
					<li><a href="#Subprocess">🔄Subprocess</a></li>
					<li><a href="#Threading">〰Threading</a></li>
					<li><a href="#Pathlib">🗺Pathlib</a></li>
				</ul>
			<li><a href="#Browsers">🌏Browsers</a></li>
				<ul>
					<li><a href="#Firefox">🦊Firefox</a></li>
				</ul>
			<li><a href="#Prototype">🖍Prototype</a></li>
				<ul>
					<li><a href="#Figma">🧾Figma</a></li>
				</ul>
			<li><a href="#Organization">📦Organization</a></li>
				<ul>
					<li><a href="#Trello">📆Trello</a></li>
					<li><a href="#Notion">📅Notion</a></li>
				</ul>
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
<br/>
The automation was implemented using a Raspberry Pi 4, a microcomputer that served both as a host for the web application and as a platform to execute the automation scripts. Through this platform, users can upload files containing student data, which will be automatically processed by the RPA to generate the ID cards.

At the end of the development, the system is expected to meet the needs of SENAI Jundiaí's administrative office, providing greater efficiency, error reduction, and time savings in activities related to ID card issuance. The implementation of an integrated and automated solution hosted on a Raspberry Pi will offer a low-cost and easy-to-maintain infrastructure, aligning with the project's technical and functional requirements.
</div>

<h3>Specific Objectives of the Project</h3>

<div align="justify">
🎯The project's specific objectives can be divided into the following areas:

<br/>
<br/>

<ul>
	<li><b>RPA (Robotic Process Automation):</b></li>
		<ul>
			<li>Develop a Python script using the Pandas, Selenium, and Pyautogui libraries, each fulfilling a specific function in processing and automation.</li>
			<li>Create a script capable of opening, manipulating, and processing uploaded files to extract necessary information and automate the ID card issuance process within the institution's systems.</li>
			<li>Implement a script to return the generated files to the web platform, allowing users to download the finalized ID cards.</li>
		</ul>
	<li><b>Web Platform Development:</b></li>
		<ul>
			<li>Develop a homepage that redirects users to the login screen, ensuring intuitive navigation.</li>
			<li>Create a login screen that ensures only pre-registered and authorized users can access the automation system.</li>
			<li>Implement an upload screen where users can submit files containing data of new students enrolling in courses.</li>
			<li>Develop a download screen, enabling users to download the files generated after completing the automation process.</li>
			<li>Implement a control mechanism to prevent simultaneous file uploads, avoiding the machine running multiple tasks at the same time and preventing overwriting of ongoing activities.</li>
		</ul>
	<li><b>Use of Raspberry Pi 4:</b></li>
		<ul>
			<li>Use the Raspberry Pi 4 as a server to host the web system.</li>
			<li>Configure the Raspberry Pi to run the developed automation scripts.</li>
		</ul>
	<li><b>API Development:</b></li>
		<ul>
			<li>Create an API (Application Programming Interface) to enable efficient integration between the website and the automation scripts, ensuring a smooth and secure data flow between the web application and the automation processes.</li>
		</ul>
	<li><b>Automation with Python:</b></li>
		<ul>
			<li>Implement a Python-based solution combining the functionalities of the following libraries:</li>
				<ul>
					<li>Pandas: responsible for data manipulation and analysis of the uploaded files.</li>
					<li>Selenium: used to automate interactions with the ID card issuance system by identifying elements on the website.</li>
					<li>Pyautogui: responsible for automating actions such as mouse clicks and keyboard inputs, simulating human interaction with the system when needed.</li>
				</ul>
		</ul>
	<li><b>Security and User Management:</b></li>
		<ul>
			<li>Implement an access control system that allows the administrator (coordinator) to register, list, edit, and remove users, ensuring the security and restricted access to the automation system.</li>
		</ul>
</ul>
</div>

<h2>Project justification</h2>

<div align="justify">
📝The decision to develop an RPA (Robotic Process Automation) for issuing ID cards for students of SENAI Jundiaí's FIC (Initial and Continuing Education) courses is based on the need to optimize the administrative processes of the institution's office.

With this automation, it will be possible to eliminate the need for manual interventions in much of the process. This will enable:

<ul>
	<li><b>Reduction in execution time:</b> The ID card issuance process will be significantly accelerated, allowing administrative staff to focus on other essential tasks.</li>
	<li><b>Minimization of human errors:</b> By automating data transcription, the project aims to reduce errors commonly found in manual processes, such as incorrect input of student information.</li>
	<li><b>Increased operational efficiency:</b> Automation will enable ID cards to be generated more quickly and efficiently, ensuring a more agile response to the demands of regularly enrolling classes.</li>	
</ul>

Additionally, this project aligns with the growing trend of process digitization and automation in educational and administrative institutions. Implementing an RPA modernizes internal processes, fostering a more technological work environment, which is crucial for the competitiveness and efficiency of educational institutions in the 21st century.

Another significant aspect is that this project represents an opportunity for the team to practically apply the knowledge acquired throughout the technical course. The combination of automation, web development, and hosting on a Raspberry Pi allows the team to not only enhance their technical skills but also directly contribute to improving the institution's processes.

Finally, the impact of this project extends beyond the institution itself. The developed automation has the potential to be replicated in other schools and organizations facing similar challenges, creating a legacy that can promote operational efficiency on a broader scale. Thus, this project is justified not only by addressing an immediate need but also by its strategic and innovative value within and beyond SENAI Jundiaí.
</div>

<h2>Methodology</h2>

<ul>
	<li id="Programming-Language"><b>Programming Language</b></li>
</br>
		<ul>
			<li id="Python-v-3-12-4"><b>Python v. 3.12.4</b></li>
			</br>
			<p align="justify">
Python is an open-source programming language widely recognized for its versatility and simple syntax, making it suitable for a broad range of projects, from small automations to large corporate systems. The language is free and accessible to the public, contributing to its popularity and the continuous growth of its developer community. Moreover, Python features an extensive standard library, which, when combined with third-party frameworks, offers a flexible, agile, and efficient development environment.

One of Python's main advantages is its ability to easily integrate with other programming languages, enabling the development of hybrid solutions that combine the best of different technological environments.

Additionally, as shown in the analysis presented in Figure 1, Python excels in resource consumption, such as CPU and RAM, compared to other languages. This makes it particularly suitable for use in hardware-limited environments like the Raspberry Pi, ensuring efficient operation without overloading system resources.</p>
			<div align="center">
				<img src="https://github.com/user-attachments/assets/73389ccd-bc9b-4c9a-ab1c-265a8efa4e3c" alt="Resource Consumption">
	   			<p>Figure 1. Source: The authors (2023).</p>
       			</div>
	  		</br>
     			<p align="justify">
Another key point is the simplicity of Python's syntax, as demonstrated in Figure 2. Compared to languages like Java, Python offers a gentler learning curve, making it easier to develop and maintain code. This not only speeds up the coding process but also reduces the likelihood of errors, which is essential for implementing reliable and efficient automation.

Thus, the use of Python in the development of this project is justified by its efficiency, flexibility, and integration capabilities, characteristics that make it the ideal choice for building robust and innovative solutions.</p>
			<div align="center">
				<img width="500" src="https://github.com/user-attachments/assets/fdb904ae-d0b8-46f6-89f9-33f91e5e6faa" alt="Comparison between Java and Python">
	   			<p>Figure 2. Comparison between Java and Python. Source: https://www.penser.co.uk/article/building-a-strong-base-best-fintech-backend-platforms/</p>
       			</div>
	  		<li id="JavaScript"><b>JavaScript</b></li>
			</br>
   			<p align="justify">
O JavaScript é uma linguagem de programação amplamente utilizada na web para adicionar dinamismo e interatividade às páginas. Enquanto HTML estrutura o conteúdo e CSS define a aparência, o JavaScript traz vida às páginas, permitindo a criação de funcionalidades complexas, como animações, validações de formulários, atualizações em tempo real e interações personalizadas do usuário.

Uma das principais vantagens do JavaScript é sua execução diretamente nos navegadores, sem necessidade de compilação prévia. Isso possibilita respostas rápidas às ações do usuário, como cliques, movimentos do mouse ou entrada de dados, tornando a experiência mais fluida e envolvente. Além disso, a linguagem é versátil e pode ser usada tanto no lado do cliente quanto no lado do servidor, com tecnologias como o Node.js.

O JavaScript também se destaca por sua vasta comunidade e ecossistema. Milhares de bibliotecas e frameworks, como React, Angular e Vue.js, foram criados para facilitar o desenvolvimento de aplicações robustas e escaláveis. Essas ferramentas economizam tempo e oferecem soluções para problemas comuns, tornando o JavaScript uma escolha favorita entre os desenvolvedores.

Outra característica importante é a integração com outras tecnologias. O JavaScript trabalha em conjunto com HTML e CSS, manipulando o DOM (*Document Object Model*) para atualizar dinamicamente o conteúdo das páginas sem necessidade de recarregá-las. Essa capacidade é crucial para criar aplicações modernas e responsivas, como as que vemos em redes sociais e serviços de e-commerce.

Por fim, o JavaScript é uma linguagem inclusiva e adaptável, sendo usada desde projetos simples até aplicações complexas. Sua presença onipresente na web e seu papel no desenvolvimento de experiências interativas e responsivas fazem do JavaScript uma peça-chave no mundo da tecnologia e um recurso indispensável para desenvolvedores que desejam criar soluções inovadoras e centradas no usuário.</p>
		</ul>
	<li id="Markup-Language"><b>Markup Language</b></li>
 </br>
		<ul>
			<li id="HTML5"><b>HTML5</b></li>
			</br>
			<p align="justify">
HTML (*HyperText Markup Language*) is a markup language for the web used to structure and organize the content of internet pages. With a variety of *tags*, developers can define how different types of content, such as headings, paragraphs, images, lists, and links, will be displayed in browsers. This language is widely recognized as the standard for building virtually all websites we access, playing a fundamental role in presenting all the elements that make up a page in a coherent manner.

One of HTML's greatest advantages is its compatibility. Any browser, on any device—whether a computer or a smartphone—can interpret and correctly display an HTML-based page. This means that regardless of where you are or what you’re using, the content will be accessible.

Moreover, HTML stands out for its flexibility, as it easily integrates with other technologies such as CSS (*Cascading Style Sheets*) and JavaScript. CSS helps style the appearance of pages by defining colors, fonts, and layouts, while JavaScript adds interactivity, making pages more dynamic for users.

Another essential aspect of HTML is accessibility. When used correctly, with semantic elements and proper attributes, HTML ensures that screen readers and other assistive devices can effectively interpret the content. This is crucial for making web pages more inclusive for people with visual impairments or other special needs.

In summary, HTML is a markup language that serves as the foundation for building websites and integrates seamlessly with other technologies. Its ability to promote accessibility and compatibility across various platforms makes HTML an essential tool for developers and designers, helping them create effective and accessible web experiences for everyone.</p>
			<li id="CSS3"><b>CSS3</b></li>
			</br>
			<p align="justify">
CSS (Cascading Style Sheets) is a design language used to style web pages structured with markup languages like HTML. It allows developers to define colors, sizes, shapes, spacing, fonts, and various other visual aspects, creating a unique look for websites. Beyond enhancing design, CSS enables control over a page's responsiveness—its ability to adapt to different screen sizes—ensuring a seamless experience across devices like smartphones, tablets, and computers.

When it comes to responsiveness, CSS plays a vital role in making web pages accessible. Using techniques like media queries, developers can create layouts that adjust dynamically to different devices and screen resolutions. This is crucial for providing a consistent and enjoyable browsing experience, regardless of the device being used.

CSS can be implemented in several ways. The most common method is creating a separate file (.css) linked to the HTML file, keeping structure and design neatly organized. Alternatively, CSS can be written directly within the HTML file, either in a <style> tag in the page's head or by applying styles directly to each HTML element using the style attribute.

In addition to styling colors and fonts, CSS enables the creation of animations, transitions, and visual effects, making navigation smoother and more engaging. It also integrates seamlessly with design frameworks and component libraries like Bootstrap, which speed up development and help create standardized, polished interfaces.

With its versatility and power, CSS not only shapes the visual appeal of a website but also ensures it is functional and accessible, catering to diverse user needs and expectations.</p>
		</ul>
	<li id="Framework"><b>Framework</b></li>
 </br>
 		<ul>
			<li id="Django-5-0-7"><b>Django 5.0.7</b></li>
			</br>
			<p align="justify">
Django is a high-level framework written in Python, designed for rapid web application development. It is free and open-source. Its main goal is to simplify the creation of web applications with a clean and organized design, promoting efficient and agile development. It follows the Model-View-Template (MVT) architecture pattern, which helps in the logical separation of data, interface, and application control.

Additionally, Django is known for its detailed and extensive documentation, which helps reduce the learning curve for both beginner and experienced developers. Furthermore, it has an active community that offers support and contributes to the creation of numerous libraries and additional tools that extend its functionality.

Django also includes integrated features that speed up development, such as a user authentication system, an automated admin panel, and protection against common web application security threats like cross-site scripting (XSS) and cross-site request forgery (CSRF). It also simplifies database management by automatically creating tables and mapping data models to the database without the need to write extensive SQL queries.

In the context of this automation project, Django was chosen for its efficiency in the backend, especially for processing and managing files. The framework's scalability also makes it ideal for applications that may grow and require more processing power over time, while maintaining a solid architecture and easier maintenance.</p>
			<li id="Cypress"><b>Cypress</b></li>
			</br>
			<p align="justify">
Cypress is a web application testing automation tool designed to make the front-end testing process fast, reliable, and easy to use. Unlike other testing tools, Cypress executes tests directly in the browser, allowing developers to see the tests being performed in real-time, helping with debugging and understanding the behavior of applications.

One of the main advantages of Cypress is its complete integration with the browser. It has direct access to all the elements on the page, which allows it to manipulate and interact with the application in the same way a real user would. Additionally, Cypress is designed to be easy to configure and use, without the need for complicated environment setups, which speeds up the learning curve and increases productivity.

Cypress also stands out for its end-to-end (E2E) testing approach, where developers can write tests that simulate the full behavior of the user, from page loading to interaction with elements such as clicks, form filling, and navigation between pages. This makes Cypress ideal for testing dynamic applications, such as those based on JavaScript, where the interaction between components is crucial.

Another important feature is that Cypress offers an interactive graphical interface, which allows you to visualize tests in execution, monitor results in real time, and even debug directly from the interface. This provides a much more intuitive and accessible testing experience, especially for development teams that are just starting to implement automated tests.

Furthermore, Cypress has excellent integration with popular testing frameworks, such as Mocha, Chai, and Sinon, enabling efficient and structured test writing. It also offers advanced features such as video capture and detailed logs, making it easier to analyze failures and troubleshoot issues.</p>
		</ul>
	<li id="Libraries"><b>Libraries</b></li>
 </br>
 		<ul>
			<li id="Selenium-4-0"><b>Selenium 4.0</b></li>
			</br>
			<p align="justify">
The Selenium library in Python, also available in other programming languages like Java, C#, and Ruby, is a tool used for automating web browsers. It offers a wide range of methods and functions that allow control over the browser and interaction with elements on a web page, such as buttons, text fields, links, and more. While it is popular for its application in automated testing of web applications, Selenium is also used for other automation tasks, such as web scraping and automating repetitive tasks on the web.

One of the major advantages of Selenium is its ability to simulate human actions in the browser. With it, tasks like clicking buttons, filling out forms, navigating between different pages, and even taking screenshots can be automated. This level of automation is very useful in interface testing, as it ensures that all elements of a website function correctly under various conditions, without the need for constant human intervention.

Another powerful feature of Selenium is the ability to run tests in parallel. Combined with tools like Selenium Grid, it is possible to distribute automated tests across different machines and browsers simultaneously, speeding up the workflow and ensuring that the site works consistently across different platforms and devices. Selenium supports the major browsers in the market, including Google Chrome, Mozilla Firefox, Safari, and Microsoft Edge, as well as enabling tests on mobile devices using Appium.

This flexibility, along with its strong support community and documentation, makes Selenium an indispensable tool for developers and quality assurance teams who need to ensure the functionality and usability of their web applications efficiently.</p>
			<li id="PyAutoGUI-0-9-54"><b>PyAutoGUI 0.9.54</b></li>
			</br>
			<p align="justify">
PyAutoGUI is a library written in Python developed for automating interactions with the graphical user interface (GUI). With it, it is possible to simulate user actions in the graphical environment, such as controlling the mouse and keyboard. The functionalities include clicking buttons, pressing keys, typing text, moving the cursor to any position on the screen, dragging and dropping items, scrolling the screen, and capturing screenshots.

One of the major advantages of PyAutoGUI is its ease of use, even in projects that require little prior experience with automation. The library is useful for automating repetitive tasks, creating simple bots that can perform operations like navigating software interfaces, filling out forms, and executing command sequences in applications.

The PyAutoGUI screenshot feature is valuable for validating on-screen elements, allowing for the identification of icons, buttons, or other graphical components. Additionally, it helps in debugging automated processes, assisting developers in understanding whether automated actions are being performed as expected.

Another advantage of the library is its portability, working on operating systems such as Windows, macOS, and Linux. This broadens its use across different environments and enables the creation of cross-platform scripts. While it may not be the best solution for automating complex or large-scale applications, PyAutoGUI is perfect for simpler tasks and routines that require repetitive user interaction.</p>
			<li id="Pandas"><b>Pandas</b></li>
			</br>
			<p align="justify">
Pandas is an open-source library in Python widely used for data analysis and manipulation. With its powerful data structures, Pandas makes it easy to work with data in formats such as tables, time series, and large volumes of structured data. It is essential for data scientists, analysts, and developers who work with data and need tools for cleaning, transforming, and analyzing it.

One of the main structures in Pandas is the DataFrame, which can be thought of as a two-dimensional table, composed of rows and columns, similar to an Excel spreadsheet or a database table. The DataFrame is highly efficient and flexible, allowing you to store, manipulate, and analyze large datasets quickly and effectively. It also supports indexing, which makes it easier to organize and access specific data intuitively.

Pandas stands out for its ability to handle missing or incomplete data, a common task when working with real-world datasets. With specific functions, it is possible to identify, replace, or remove missing values efficiently. Additionally, it allows you to perform complex operations, such as data grouping, aggregation, merging (joining different datasets), and filtering data with simple Python code.

Another advantage of Pandas is its integration with other popular libraries in the Python ecosystem, such as NumPy (for numerical calculations), Matplotlib and Seaborn (for data visualization), and SciPy (for scientific computing). This allows Pandas to be used as a central part of a data analysis workflow, where data manipulation and preparation are done with Pandas, while numerical analysis and graphical visualizations are performed with other tools.

Furthermore, Pandas supports various input and output formats, such as CSV files, Excel, SQL, JSON, among others, which facilitates the import and export of data from different sources. This makes Pandas an essential tool for working with data in Python.</p>
			<li id="Django-Rest-Framework"><b>Django Rest Framework</b></li>
			</br>
			<p align="justify">
The Django REST Framework (DRF) is a robust library that enables the creation of REST APIs using the Django framework. DRF stands out for operating under the already established infrastructure of Django, making it easier to build APIs across various platforms, including Windows, macOS, and Linux. This versatility makes DRF a popular choice among developers looking for an efficient way to create web services and backend systems.

One of the great advantages of Django REST Framework is its ability to simplify API development by leveraging Django’s features, such as its powerful routing system and the ORM (Object-Relational Mapping) for database management. This means that with DRF, you can quickly and effectively create REST APIs, speeding up the development process and increasing productivity.

DRF offers a range of features that make API development more complete and secure. For example, it supports authentication and authorization, enabling the creation of protected APIs with access tokens to ensure that only authenticated users can access certain endpoints. Additionally, DRF makes it easier to use filters, which allow for the selection and visualization of data in a customized way, optimizing the experience for API consumers.

Another significant benefit of the Django REST Framework is its support for caching systems, which help improve API performance by making data retrieval much faster, especially in large-scale applications. Moreover, DRF is fully integrable with Django, meaning that you can take advantage of all the features and security provided by the main framework without the need for complex configurations.

Finally, DRF is highly extensible, offering support for a variety of external libraries that can be easily integrated to add extra functionalities, such as OAuth authentication, advanced serialization, and automatic documentation generation. This makes Django REST Framework one of the most comprehensive and reliable options for building REST APIs in the Python ecosystem.</p>
			<li id="OS"><b>OS</b></li>
			</br>
			<p align="justify">
The OS library in Python acts as a bridge between your code and the operating system where it is running. It provides a comprehensive set of functions that facilitate direct interaction with the system, allowing tasks such as navigating and manipulating directories, changing file permissions, retrieving detailed system information, and executing native commands. In other words, the OS library simplifies the programming of tasks that depend on the operating system, making them more intuitive and portable, regardless of the platform (Windows, macOS, or Linux) where your code is running.</p>
			<li id="Subprocess"><b>Subprocess</b></li>
			</br>
			<p align="justify">
The subprocess library in Python is a powerful tool for executing new processes in the operating system from Python code. It allows for the creation of processes, as well as communication with them and retrieving their results. Thus, subprocess offers a flexible and robust way to execute system commands directly from your script, replacing older functions like os.system().

One of the main advantages of the subprocess library is its ability to capture the output of executed commands, allowing you to process the results directly in your code. Additionally, it offers greater control over processes, allowing for the redirection of input, output, and error streams, as well as safer and more efficient management of subprocesses.

The subprocess module also allows commands to be executed in different environments, such as Shell, using the shell=True option, although this option should be used with caution due to potential security risks. In general, the use of the library is recommended for situations where it is necessary to call external programs, perform administrative task automations, or integrate Python scripts with other system applications and utilities.</p>
			<li id="Threading"><b>Threading</b></li>
			</br>
			<p align="justify">
The threading library in Python is a powerful tool for performing multitasking, allowing the simultaneous execution of multiple operations within a single program. This concept is known as multithreading, where the code is split into multiple "threads" that can run in parallel. Each thread functions as an independent unit of execution, allowing different parts of the code to run at the same time, which can lead to significant performance gains, especially in tasks involving I/O operations (such as file reading, data downloading, or API calls).

In simple terms, it is a way to execute multiple operations simultaneously. For example, if you have several tasks that can run independently — like downloading files, processing information, or making HTTP requests — the threading library allows you to run these tasks in parallel. This means that instead of waiting for one function to finish before starting another, you can execute all of them at the same time, increasing efficiency and speeding up the execution of your program.

Using the threading library can significantly improve the performance of your code, especially in situations where multiple tasks do not depend on one another. However, it is important to be cautious when using threads, as simultaneous execution can introduce complexities, such as race conditions and synchronization issues between threads, which need to be properly managed to avoid unexpected bugs.</p>
			<li id="Pathlib"><b>Pathlib</b></li>
			</br>
			<p align="justify">
The pathlib library is a module introduced in Python 3 that provides a modern and efficient way to handle file and directory paths in a way that is independent of the operating system. Unlike the traditional os.path module, which is also used for handling paths, pathlib offers an object-oriented interface that is more intuitive and readable, making it easier to work with files and directories.

One of the main benefits of pathlib is its ability to handle paths independently of the operating system. For example, on Unix-based systems (such as macOS and Linux), a file path might be represented as /Users/sammy/ocean/wave.txt, while on Windows, the same file might have the path C:\\Users\\sammy\\ocean\\wave.txt. With pathlib, you can manipulate these paths without worrying about the differences in formatting, as it abstracts these variations, making the code more portable.

The pathlib library is particularly useful in operations involving the creation, movement, and listing of files and directories. For example, it is possible to list all files with a specific extension in a directory, create new directories, or navigate through different folder levels in a simple manner. Using pathlib results in more readable and concise code, reducing the need for complex functions and improving clarity.

In addition to basic functionalities such as checking for file existence, retrieving attributes, and creating paths, pathlib also includes advanced utilities, such as using glob patterns to find files that match a specific pattern (*.txt, for example) and methods for efficiently traversing directory hierarchies.</p>
		</ul>
  	<li id="Browsers"><b>Browsers</b></li>
<p align="justify">
	The user will be able to access our website using any browser of their preference. However, external systems used, such as CAF and IHX, require a specific browser to ensure proper functionality. To ensure this compatibility, our website will automatically open Firefox, guaranteeing that all features work correctly.
</p>
	<ul>
		<li id="Firefox"><b>Firefox</b></li>
		</br>
		<p align="justify">
Mozilla Firefox is a free and open-source browser, widely recognized for its flexibility and efficient performance across various platforms, including Windows, macOS, Linux, as well as mobile devices running Android and iOS. One of Firefox’s main attractions is its extensive customization options, allowing users to adjust themes, colors, and extensions to tailor the browser to their preferences. With an intuitive interface, Firefox makes it easy to quickly access essential functions such as bookmarks, history, and downloads, providing a smooth and convenient browsing experience.

Compared to other popular browsers, Firefox stands out for its strong privacy and security features. It automatically blocks third-party trackers, protecting users from being monitored while online, which is an advantage over Google Chrome. Additionally, the browser includes built-in features such as a pop-up blocker, anti-phishing tools, and continuous verification of suspicious websites, ensuring a secure browsing experience. Automatic security updates keep Firefox up-to-date with the latest protections.

Another distinctive feature of Mozilla Firefox is its extensive catalog of extensions and advanced features, such as an internal tool for taking screenshots, support for watching videos in picture-in-picture mode, and an integrated PDF reader. The tab browsing experience is customizable, and the browser also supports configurable push notifications, giving users greater control over their browsing experience. With support for over 90 languages and optimized performance, Firefox remains a popular choice among users who prioritize privacy, security, and a feature-rich interface.</p>
	</ul>
 	<li id="Prototype"><b>Prototype</b></li>
  </br>
	  	<ul>
			<li id="Figma"><b>Figma</b></li>
			</br>
			<p align="justify">
Figma is a collaborative platform designed for creating prototypes and user interface (UI) and user experience (UX) designs, for both web applications and local applications. One of Figma's main differentiators is the ability for multiple users to work simultaneously on the same project, which facilitates collaborative and real-time development.

The platform also offers the creation of reusable components, such as buttons, icons, and other interface elements, ensuring greater visual consistency and saving time throughout the project. Additionally, Figma integrates easily with other popular tools such as Slack, JIRA, and developer design platforms, enhancing workflow efficiency and facilitating communication between design and development teams.

Another important aspect is the version history, which allows users to track and revert changes, providing security in the project’s development. This ensures that all previous versions can be recovered if needed, preventing the loss of work or implementation errors.</p>
		</ul>
 	<li id="Organization"><b>Organization</b></li>
  </br>
	  	<ul>
			<li id="Trello"><b>Trello</b></li>
			</br>
			<p align="justify">
Trello is a project management platform based on the Kanban methodology, which allows users to organize tasks, collaborate as a team, and track progress in a visual and intuitive way. Its main feature is the creation of “boards,” which represent different projects or work areas. Each board can be fully customized according to the project’s needs, allowing users to visually represent the workflow and break down tasks into clear stages.

Within each board, users can create “lists” that reflect the progress of tasks or different phases of the project, such as “To Do,” “In Progress,” and “Done.” The lists are used to organize “cards,” which represent individual tasks or action items. These cards are highly customizable and can contain detailed descriptions, checklists, deadlines, attachments, color-coded labels to categorize activities, and comments to facilitate communication among team members.

One of Trello's biggest advantages is its simple and highly visual interface, which makes it easy to understand the current status of any project. Additionally, the platform offers integrations with various productivity tools like Slack, Google Drive, and Dropbox, making it easier for teams to collaborate, especially in remote work environments. Trello also allows the use of "Power-Ups," which are extensions and additional features that expand the tool’s capabilities, such as automating repetitive tasks with Butler, generating custom reports, and integrating with other platforms.</p>
			<li id="Notion"><b>Notion</b></li>
			</br>
			<p align="justify">
Notion is a multifunctional organizational tool that combines various features such as note-taking, task management, project organization, and even database creation. Its flexibility allows both individual users and teams to utilize the platform for a wide range of activities, from creating simple lists to managing complex projects.

One of Notion's key differentiators is the ability to collaborate in real time. Multiple users can edit the same page simultaneously, making it ideal for teamwork and projects that require constant interaction. Additionally, Notion offers detailed permission controls, allowing users to define who can view, edit, or comment on each page or workspace.

The platform also stands out for its customization options. Virtually all the features available in Notion can be tailored to meet the specific needs of users. This includes creating custom layouts, using templates, building task tracking systems, and automating workflows.

Furthermore, Notion integrates with several other popular tools and services such as Google Drive, Slack, Trello, among others, which facilitates the centralization of information and the connection between different work platforms. This integration increases efficiency in information management and makes collaboration among distributed teams easier.</p>
		</ul>
</ul>
