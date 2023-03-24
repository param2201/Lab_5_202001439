<center> <h1> IT 314 Software Engineering</h1>
<h2> Lab 5 </h2>
<h2> Name : Param Mistry </h2>
<h2> ID : 202001439 </h2> </center>

<ol>
  <dl><h3>Static Code Analysis of a git repositary using MYPY tool </h3></dl>
  <dl><h3>Reference Git Repositary : https://github.com/param2201/Django-Blog.git </h3></dl>
</ol>
<br>

<h3>MYPY Tool :</h3>
<ul>
  <li>Mypy is a static type checker that allows you to specify the types of variables, function arguments, and function return values in your Python code.</li>
  <li>Mypy checks types at compile time, before your code is executed. This can help catch errors early in the development process, before they cause problems in production.</li>
  <li>Mypy integrates with popular tools like PyCharm, VSCode, and Sublime Text. It also works well with build tools like Make, Gradle, and Maven.</li>
  <li>Mypy runs on Windows, macOS, and Linux, and can be used with Python 2.7 and 3.x.</li>
  <li>Mypy is an open source project, released under the MIT license. This means that you can use it for free and even contribute to the project if you'd like to.</li>
  <li>Mypy is widely used in the Python community, and is considered one of the most popular static type checkers for Python.</li>
</ul>

<br>

<h3>Process :</h3>

### 1. Install mypy Using Command : python -m pip install mypy

### 2. Clone The Git Repository
![image](https://user-images.githubusercontent.com/118919249/227483708-5c4f475a-541f-4216-a8f1-32703fed9a58.png)

### 3. Running Command for Code Analysis : python -m mypy <path_of_file>
![image](https://user-images.githubusercontent.com/118919249/227486651-e68e443f-7787-4290-9f7c-128480cf99cd.png)
### The Above Error Shows That some Moduels are not Found.

### 4. Running Command for Code Analysis : python -m mypy .\mysite\urls.py
![image](https://user-images.githubusercontent.com/118919249/227489114-613e0f91-8615-4307-a1f5-77274017dae4.png)
### The Above Error Shows that some Variables are not Defined.

### 5. Running Command for Code Analysis : python -m mypy .\blog\urls.py
![image](https://user-images.githubusercontent.com/118919249/227489906-9c97005a-1f77-4721-ab69-6b8369e10f95.png)
### The Above Error Shows that some Moduels are not Found.

### 6. Running command for code analysis : python -m mypy .\mysite\settings.py
![image](https://user-images.githubusercontent.com/118919249/227490388-b2902759-0238-44f4-9532-2b266fe550d9.png)
### The Above Screenshot shows that there is no error in settings.py file.

### 7. Running command for code analysis : python -m mypy .\mysite\asgi.py
![image](https://user-images.githubusercontent.com/118919249/227490775-fa760781-3e0f-4ad6-ae7b-0b65cf72e766.png)
### The Above Screenshot shows that it cannot find library for module named "django.core.asgi".



