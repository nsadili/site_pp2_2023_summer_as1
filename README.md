<h1> Assignment 1 </h1>
<h3> Creating a simple JAVA application to implement a Inheritance and Polymorphism. </h3>

Dear students,

In this assignment, you need to submit you work to implement a project which demonstrates your knowledge on mainly
inheritance, polymorphism and abstraction.

<h3>Task Related - List of the required types</h3>
<ul>
    <li><strong><em>Vehicle class</em></strong></li>
    <li><strong><em>Car class </em></strong>(a subclass of the Account)</li>
    <li><strong><em>Motorcycle class </em></strong>(a subclass of the Account)</li>
    <li><strong><em>Main</em></strong></li>
</ul>

<h3>Task Related - Vehicle class <strong>(20 %)</strong></h3>
<p>It should have the following fields and the methods:</p>
<p>Fields:</p>
<ul>
    <li><strong><em>id</em></strong> - (String - autogenerated) </li>
    <li><strong><em>brand</em></strong> - (String) </li>
    <li><strong><em>year</em></strong> - (Integer) </li>
</ul>
<p>Methods:</p>
<ul>
    <li>a parametrized constructor to initialize fields</li>
    <li>a getter method for each field</li>
    <li>a setter method for brand and year</li>
    <li>an abstract method named <em>startEngine()</em></li>
</ul>

<h3>Task Related - Car class <strong>(20 %)</strong></h3>
<p>It should have the following fields and the methods:</p>
<p>Fields:</p>
<ul>
    <li><strong><em>numberOfSeats</em></strong> - (Integer) </li>
</ul>
<p>Methods:</p>
<ul>
    <li>a parametrized constructor that initializes the <em>numberOfSeats</em> field with the value 5</li>
    <li>a parametrized constructor that initializes all the fields with the input parameters</li>
    <li>getter and setter methods for the field</li>
    <li>overrriden <em>startEngine()</em> method that prints <em>"Car engine starts..."</em></li>
</ul>

<h3>Task Related - Motorcycle class <strong>(20 %)</strong></h3>
<p>It should have the following fields and the methods:</p>
<p>Fields:</p>
<ul>
    <li><strong><em>hasSidecar</em></strong> - (Boolean) </li>
</ul>
<p>Methods:</p>
<ul>
    <li>a parametrized constructor that initializes the <em>hasSideCar</em> field with the value false</li>
    <li>a parametrized constructor that initializes all the fields with the input parameters</li>
    <li>getter and setter methods for the field</li>
    <li>overrriden <em>startEngine()</em> method that prints <em>"Motorcycle engine starts..."</em></li>
</ul>

<h3>Task Related - Exception handling <strong>(10 %)</strong></h3>
<ul>
    <li>Please, carefully follow the instructions above.</li>
    <li>Your program should properly enforce encapsulation, inheritance, abstraction and polymorphism.</li>
    <li>Your program should prevent invalid operations using proper exceptions and exception handling. Some of them are
        the following:
        <ul>
            <li>number of numberOfSeats cannot be less than 1</li>
            <li>year cannot be in the future, etc.</li>
        </ul>
    </li>
</ul>

<h3>Task Related - Testing all together <strong>(25 %)</strong></h3>
<p> You will need to define a <strong><em>Main</em></strong> class which demonstrates all the functionality of
    your program. However, it is strongly encouraged to test each class and each method as soon as they are completed to
    have
    less errors and easy debugging in the end. </p>
<p> Define a method <em>race()</em>in the Main class that accepts and array of Vehicles and simulates a race. In the
    method call <em>startEngine()</em> of each vehicle in the array to print the relevant message.</p>
<p> Create a JavaDoc comment and explain the inheritance and polymorphism principles in the application.</p>
<p> When you compile, make sure your .class files are totally isolated from the rest and are never commited and pushed.
</p>


<h3>Task Related - Class diagrams <strong>(5 %)</strong></h3>
Draw the class diagrams including all the relations among the classes. Add the image(s) to the project
folder so that they are submitted to the repository as well. You may use any tool to draw the diagrams. Make sure you
submit image format (.jpg or .png).

<h4> Submission related: (5%)</h4>
<ul>
    <li> Record a short video not exceeding 5 minutes to explain the code as well as the way users can interact with the
        end product
        <ul>Show:
            <li> main blocks of the code base</li>
            <li> each of the features mentioned above</li>
        </ul>
    </li>
    <li> Upload the video to YouTube and share the link by adding it to your README.md file as the first line (Note: do
        not empty the READMY.md file).</li>
    <li> Submissions without a video recording will not be graded.</li>
</ul>

<h4>Important notes:</h4>
- Codes that do not compile and run for any reason will <strong>not be graded</strong>. Test properly before you submit
your work.<br />
- Please, also refer to the course syllabus about the assignments. <br />
- Each completed feature must be commited and pushed <strong>works submitted in just one or two commits are not
    acceptable</strong>. <br />
- This assignment will give you <strong><em>10 %</em></strong> of the overall. <br />