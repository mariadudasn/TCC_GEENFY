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
		  <li text-decoration="none"><a href="#Programming-Language">💻Programming Language</a></li>
			<ul>
				<li text-decoration="none"><a href="#Python-v.-3.12.4">🐍Python v. 3.12.4</a></li>
				<li text-decoration="none"><a href="#JavaScript">☕JavaScript</a></li>
			</ul>	
		  <li text-decoration="none"><a href="#Specific-Objectives-of-the-Project">🖱Markup Language</a></li>
			<ul>
				<li text-decoration="none"><a href="#HTML5">📄HTML5</a></li>
				<li text-decoration="none"><a href="#CSS3">📱CSS3</a></li>
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
	<li><b>Programming Language</b></li>
</br>
		<ul>
			<li><b>Python v. 3.12.4</b></li>
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
	  		<li><b>JavaScript</b></li>
			</br>
   			<p align="justify">
O JavaScript é uma linguagem de programação amplamente utilizada na web para adicionar dinamismo e interatividade às páginas. Enquanto HTML estrutura o conteúdo e CSS define a aparência, o JavaScript traz vida às páginas, permitindo a criação de funcionalidades complexas, como animações, validações de formulários, atualizações em tempo real e interações personalizadas do usuário.

Uma das principais vantagens do JavaScript é sua execução diretamente nos navegadores, sem necessidade de compilação prévia. Isso possibilita respostas rápidas às ações do usuário, como cliques, movimentos do mouse ou entrada de dados, tornando a experiência mais fluida e envolvente. Além disso, a linguagem é versátil e pode ser usada tanto no lado do cliente quanto no lado do servidor, com tecnologias como o Node.js.

O JavaScript também se destaca por sua vasta comunidade e ecossistema. Milhares de bibliotecas e frameworks, como React, Angular e Vue.js, foram criados para facilitar o desenvolvimento de aplicações robustas e escaláveis. Essas ferramentas economizam tempo e oferecem soluções para problemas comuns, tornando o JavaScript uma escolha favorita entre os desenvolvedores.

Outra característica importante é a integração com outras tecnologias. O JavaScript trabalha em conjunto com HTML e CSS, manipulando o DOM (*Document Object Model*) para atualizar dinamicamente o conteúdo das páginas sem necessidade de recarregá-las. Essa capacidade é crucial para criar aplicações modernas e responsivas, como as que vemos em redes sociais e serviços de e-commerce.

Por fim, o JavaScript é uma linguagem inclusiva e adaptável, sendo usada desde projetos simples até aplicações complexas. Sua presença onipresente na web e seu papel no desenvolvimento de experiências interativas e responsivas fazem do JavaScript uma peça-chave no mundo da tecnologia e um recurso indispensável para desenvolvedores que desejam criar soluções inovadoras e centradas no usuário.</p>
		</ul>
	<li><b>Markup Language<b></li>
 </br>
		<ul>
			<li><b>HTML5</b></li>
			</br>
			<p align="justify">
HTML (*HyperText Markup Language*) is a markup language for the web used to structure and organize the content of internet pages. With a variety of *tags*, developers can define how different types of content, such as headings, paragraphs, images, lists, and links, will be displayed in browsers. This language is widely recognized as the standard for building virtually all websites we access, playing a fundamental role in presenting all the elements that make up a page in a coherent manner.

One of HTML's greatest advantages is its compatibility. Any browser, on any device—whether a computer or a smartphone—can interpret and correctly display an HTML-based page. This means that regardless of where you are or what you’re using, the content will be accessible.

Moreover, HTML stands out for its flexibility, as it easily integrates with other technologies such as CSS (*Cascading Style Sheets*) and JavaScript. CSS helps style the appearance of pages by defining colors, fonts, and layouts, while JavaScript adds interactivity, making pages more dynamic for users.

Another essential aspect of HTML is accessibility. When used correctly, with semantic elements and proper attributes, HTML ensures that screen readers and other assistive devices can effectively interpret the content. This is crucial for making web pages more inclusive for people with visual impairments or other special needs.

In summary, HTML is a markup language that serves as the foundation for building websites and integrates seamlessly with other technologies. Its ability to promote accessibility and compatibility across various platforms makes HTML an essential tool for developers and designers, helping them create effective and accessible web experiences for everyone.</p>
			<li><b>CSS3</b></li>
			</br>
			<p align="justify">
CSS (Cascading Style Sheets) is a design language used to style web pages structured with markup languages like HTML. It allows developers to define colors, sizes, shapes, spacing, fonts, and various other visual aspects, creating a unique look for websites. Beyond enhancing design, CSS enables control over a page's responsiveness—its ability to adapt to different screen sizes—ensuring a seamless experience across devices like smartphones, tablets, and computers.

When it comes to responsiveness, CSS plays a vital role in making web pages accessible. Using techniques like media queries, developers can create layouts that adjust dynamically to different devices and screen resolutions. This is crucial for providing a consistent and enjoyable browsing experience, regardless of the device being used.

CSS can be implemented in several ways. The most common method is creating a separate file (.css) linked to the HTML file, keeping structure and design neatly organized. Alternatively, CSS can be written directly within the HTML file, either in a <style> tag in the page's head or by applying styles directly to each HTML element using the style attribute.

In addition to styling colors and fonts, CSS enables the creation of animations, transitions, and visual effects, making navigation smoother and more engaging. It also integrates seamlessly with design frameworks and component libraries like Bootstrap, which speed up development and help create standardized, polished interfaces.

With its versatility and power, CSS not only shapes the visual appeal of a website but also ensures it is functional and accessible, catering to diverse user needs and expectations.</p>
		</ul>
</ul>
