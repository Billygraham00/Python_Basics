<h1>🐍 Python Basics</h1>

<img src="https://raspberry-valley.azurewebsites.net/img/Python-01.jpg" />

<h2>📅 Day 1 - History of Programming Languages</h2>

<h3>🔹 C Programming (Introduced in 1972 by Dennis Ritchie)</h3>
<b>Advantages:</b>
<ul>
  <li>Powerful language for desktop and embedded applications</li>
  <li>High-level security</li>
  <li>Used to develop other programming languages</li>
  <li>Used in game development</li>
  <li>100% CPU utilization possible</li>
</ul>

<b>Disadvantages:</b>
<ul>
  <li>Difficult to learn and implement</li>
  <li>No reusability</li>
  <li>No frameworks</li>
</ul>

<h3>🔹 C++ (Introduced in 1978)</h3>
<b>Advantages:</b>
<ul>
  <li>Very powerful language</li>
  <li>Supports Game, Desktop, Mobile, Embedded applications</li>
  <li>Object-Oriented (developed mainly by Bjarne Stroustrup)</li>
  <li>High security and 100% CPU utilization</li>
  <li>Supports reusability</li>
</ul>

<b>Disadvantages:</b>
<ul>
  <li>Complex to learn and implement</li>
  <li>No built-in frameworks</li>
</ul>

<h3>🔹 Python (Introduced in 1991)</h3>
<b>Advantages:</b>
<ul>
  <li>Easy to learn and implement</li>
  <li>Supports Desktop, Web, and Mobile App development</li>
  <li>Supports reusability</li>
</ul>

<b>Disadvantages:</b>
<ul>
  <li>100% CPU utilization not possible (max ~99.99%)</li>
  <li>Lower security compared to C++</li>
</ul>

<h3>🔹 Java (Introduced in 1993)</h3>
<b>Advantages:</b>
<ul>
  <li>High-level security</li>
  <li>Used in Web, Desktop, Mobile, Embedded Apps, Games, and Banking</li>
  <li>Supports reusability and has frameworks like Spring and Hibernate</li>
  <li>100% CPU utilization is achievable</li>
</ul>

<b>Disadvantages:</b>
<ul>
  <li>Steeper learning curve</li>
</ul>

<h3>🔹 .NET Family (Launched in 2001 by Microsoft)</h3>
<ul>
  <li>Includes 32+ languages like C#, J#, Visual Basic</li>
  <li>C# is widely used in banking applications</li>
</ul>

<h3>🔹 Python and AI (1991 - 2008 and beyond)</h3>
<ul>
  <li>Python community focused on AI development</li>
  <li>Mathematics-oriented language for AI/ML</li>
  <li>Popular frameworks: Flask, Django</li>
  <li>Used by NASA, ISRO, etc.</li>
</ul>

<b>Disadvantage:</b>
<ul>
  <li>CPU utilization slightly below 100%</li>
</ul>

<h2>📅 Day 2 - Installing IDLE and Key Concepts</h2>

<h3>🔧 Installing IDLE</h3>
<ul>
  <li>Download Python from the official site</li>
  <li>IDLE: Integrated Development and Learning Environment</li>
  <li>Use Google Colab for cloud-based notebooks (.ipynb)</li>
</ul>

<h3>🛠 How to Setup Google Colab:</h3>
<ol>
  <li>Open Google Drive</li>
  <li>Create a new folder and right-click → "Connect more apps"</li>
  <li>Search and install "Colaboratory"</li>
  <li>Open notebook → Click "Connect" → Select GPU via Runtime settings</li>
</ol>

<h3>📘 IDLE Tips:</h3>
<ul>
  <li>Use <code>#</code> for comments</li>
  <li>Use <code>+</code> to add text/markdown cells</li>
  <li>Up to 6 <code>#</code> for different heading levels</li>
  <li>Enable line numbers from Tools → Settings</li>
</ul>

<h2>📚 Python Concepts Covered</h2>

<h3>✅ Basic Python</h3>
<ul>
  <li>Data Types</li>
  <li>Variables</li>
  <li>Type Conversions</li>
  <li>Print Statements</li>
  <li>Operators</li>
  <li>Built-in Functions</li>
  <li>Strings, Lists, Tuples, Sets, Dictionaries</li>
  <li>Math Libraries</li>
</ul>

<h3>🌀 Intermediate Python</h3>
<ul>
  <li>For & While Loops</li>
  <li>If, Else, Elif Conditions</li>
  <li>Break, Continue</li>
  <li>Functions, Lambda Functions</li>
  <li>Local & Global Variables</li>
  <li>List & Dictionary Comprehension</li>
  <li>Map, Filter, Reduce</li>
  <li>Recursion</li>
  <li>System Libraries</li>
</ul>

<h3>🚀 Advanced Python</h3>
<ul>
  <li>File Handling</li>
  <li>Exception Handling</li>
  <li>OOP: Class, Object, Constructor</li>
  <li>Self, Inheritance, Polymorphism, Abstraction, Encapsulation</li>
</ul>

<h3>🛠 Production-Level Python</h3>
<ul>
  <li>Processes</li>
  <li>Multiprocessing</li>
  <li>Multithreading</li>
</ul>

<h3>📦 Popular Python Libraries</h3>
<ul>
  <li>NumPy</li>
  <li>Pandas</li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
</ul>

<h3>📊 Statistics & Machine Learning</h3>
<ul>
  <li>Basics of Stats</li>
  <li>ML Concepts</li>
  <li>Implementation using Python</li>
</ul>

<h2>🧠 Python Data Types</h2>
<ul>
  <li><b>int</b>: Whole numbers (e.g., 12, 100)</li>
  <li><b>float</b>: Decimal numbers (e.g., 12.5, 99.99)</li>
  <li><b>str</b>: Text/String (e.g., 'Python', "123")</li>
</ul>

<h2>📦 Variables in Python</h2>

<h3>🔹 What is a Variable?</h3>
<p>A <b>variable</b> is a container that stores data in RAM (memory). It holds values that can change during program execution.</p>

<h3>🔹 Example:</h3>
<pre><code>a = 122
print(a)</code></pre>
<p><b>Output:</b> 122</p>

<h3>🧠 Understanding Variables:</h3>
<ul>
  <li>Once assigned (e.g., <code>a = 122</code>), Python stores the value in memory.</li>
  <li>You can access it later just by calling <code>print(a)</code>.</li>
</ul>

<h3>⚠ Rules for Naming Variables:</h3>
<ol>
  <li>Cannot start with a number (e.g., <code>100 = 50</code> is invalid).</li>
  <li>Cannot use spaces. Use underscores instead (e.g., <code>sai_kumar = 33</code>).</li>
  <li>Are <b>case sensitive</b> (<code>City</code> ≠ <code>CITY</code>).</li>
  <li>Cannot use special characters like <code>!@#$%^&*</code>.</li>
</ol>

<h3>✅ Examples:</h3>
<pre><code># Valid
a = 10
user_name = "Ajay"
City = "Delhi"

# Invalid
100a = 20
user name = "Ajay"
%val = 40
</code></pre>

<hr/>

<h2>➕ Operators</h2>
<p>Operators perform operations on variables and values.</p>

<h3>🔹 Example:</h3>
<pre><code>a = 122
print(a + 10)</code></pre>
<p><b>Output:</b> 132</p>

<hr/>

<h2>💾 Memory & Data Types</h2>

<h3>🧠 How Python Stores Data</h3>
<ul>
  <li><code>int</code>: Takes 4 bytes (32 bits)</li>
  <li><code>str</code>: Each character takes 1 byte</li>
</ul>

<h3>🔹 Check Type and Memory Address</h3>
<pre><code>p = 457
print(p)
print(type(p))
print(id(p))</code></pre>

<p><b>Output:</b></p>
<pre>457
&lt;class 'int'&gt;
13583317590720</pre>

<h3>ℹ Variable Updates Change Memory Address:</h3>
<pre><code>a = 10
print(id(a))

a = 50
print(id(a))</code></pre>

<p>Each new assignment creates a new memory reference.</p>

<hr/>

<h2>🔄 Type Conversion</h2>

<h3>🔹 Converting Types</h3>
<pre><code>a = 12
print(a)
print(type(a))

b = float(a)
print(b)
print(type(b))</code></pre>

<p><b>Output:</b></p>
<pre>12
&lt;class 'int'&gt;
12.0
&lt;class 'float'&gt;</pre>

<h3>⚠ Invalid Conversion:</h3>
<pre><code>a = "data"
b = int(a)  # ❌ Error</code></pre>
<p><b>Reason:</b> Strings must be numeric to convert to <code>int</code> or <code>float</code>.</p>

<h3>✅ Valid String Conversion:</h3>
<pre><code>a = "56"
b = int(a)
print(b)</code></pre>

<hr/>

<h2>🖨 Print Conditions</h2>

<h3>🗣 Different Ways to Use <code>print()</code></h3>

<h4>Type 1: Using Commas (adds space automatically)</h4>
<pre><code>name = "Ajay"
age = 27
print("My name is", name, "and my age is", age)</code></pre>

<h4>Type 2: Using <code>+</code> (only works with same data type)</h4>
<pre><code>print("My age is " + str(age))</code></pre>

<h4>Type 3: Using Formatting with <code>%</code></h4>
<pre><code>print("My age is %d" % age)</code></pre>

<h4>Type 4: Using f-strings (recommended)</h4>
<pre><code>print(f"My name is {name} and my age is {age}")</code></pre>

<h4>Multi-line Example:</h4>
<pre><code>country = "Dubai"
cost = 45.55
duration = 3

print(f"I'm going to travel to {country} with {cost} dollars for {duration} hours.")</code></pre>

<hr/>

<h2>🔣 Special Print Characters</h2>
<ul>
  <li><code>\n</code> - New Line</li>
  <li><code>\t</code> - Tab Space</li>
</ul>

<pre><code>print("Jan\nFeb\nMar")
print("Jan\tFeb\tMar")</code></pre>

<p><b>Output:</b></p>
<pre>Jan
Feb
Mar

Jan    Feb    Mar</pre>

<hr/>

<h2>📚 Built-in Functions & Libraries</h2>

<h3>🔹 What is a Function?</h3>
<p>A function is a reusable block of code that performs a specific task.</p>

<h3>🔹 Built-in Functions:</h3>
<ul>
  <li><code>print()</code></li>
  <li><code>type()</code></li>
  <li><code>int()</code>, <code>float()</code></li>
  <li><code>len()</code></li>
  <li><code>sum()</code></li>
</ul>

<h3>🔹 What is a Library?</h3>
<p>A library is a collection of pre-written code (modules) that you can use in your program.</p>

<h4>Example: Math Library</h4>
<pre><code>import math

print(dir(math))       # Lists all functions in math
print(len(dir(math)))  # Total number of functions
print(math.factorial(5))</code></pre>

<p><b>Popular Python Libraries:</b> <code>math</code>, <code>random</code>, <code>datetime</code>, <code>os</code>, <code>statistics</code></p>

<hr/>

<h2>📞 Support</h2>
<p>📧 Email: <a href="mailto:billygrahamkandavalli@gmail.com">billygrahamkandavalli@gmail.com</a></p>
<p>🔗 LinkedIn: <a href="https://www.linkedin.com/in/billy-graham-kandavalli-328607372" target="_blank">Billy Graham Kandavalli</a></p>

<img src="https://via.placeholder.com/1000x200.png?text=Thanks+for+visiting+this+repo!" alt="Thank you banner" />
