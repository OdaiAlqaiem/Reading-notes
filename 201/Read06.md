# Object Literals
![Object Literals](https://miro.medium.com/max/1400/1*gslNlU_BKtZuSyjLMbmp7Q.png)

This example starts by creating 
an object using literal notation. 
This object is called hotel which 
represents a hotel called Quay 
with 40 rooms (25 of which have 
been booked). 
Next, the content of the page 
is updated with data from this 
object. It shows the name of the 
hotel by accessing the object's 
name property and the number 
of vacant rooms using the 
checkAvail ability() method. 
To access a property of this 
object, the object name is 
followed by a dot (the period 
symbol) and the name of the 
property that you want. 
Similarly, to use the method, 
you can use the object name 
followed by the method name. 
hotel . checkAvailability() 
If the method needs parameters, 
you can supply them in the 
parentheses (just like you can 
pass arguments to a function).


! [js](http://xomino.files.wordpress.com/2013/04/j1.png)

Here you can see another object. 
Again it is called hote 1, but this 
time the model represents a 
different hotel. For a moment, 
imagine that this is a different 
page of the same travel website. 
The Park hotel is larger. It has 
120 rooms and 77 of them are 
booked. 
The only things changing in the 
code are the values of the hot e 1 
object's properties: 
• The name of the hotel 
• How many rooms it has 
• How many rooms are booked 
The rest of the page works in 
exactly the same way. The name 
is shown using the same code. 
The checkAvai 1 abi l ity() 
method has not changed and is 
called in the same way. 
If this site had 1,000 hotels, 
the only thing that would 
need to change would be the 
three properties of this object. 
Because we created a model for 
the hotel using data, the same 
code can access and display the 
details for any hotel that follows 
the same data model. 
If you had two objects on the 
same page, you would create 
each one using the same 
notation but store them in 
variables with different names. <hr><br>


# Document Object 

+ The browser represents the page using a DOM tree. 

+ DOM trees have four types of nodes: document nodes, 
element nodes, attribute nodes, and text nodes.

+ You can select element nodes by their id or cl ass 
attributes, by tag name, or using CSS selector syntax. 

+ Whenever a DOM query can return more than one 
node, it will always return a Nadel i st. 

+ From an element node, you can access and update its 
content using properties such as textContent and 
i nnerHTML or using DOM manipulation techniques.

+ An element node can contain multiple text nodes and 
child elements that are siblings of each other.

+ In older browsers, implementation of the DOM is 
inconsistent (and is a popular reason for using jQuery). 
Browsers offer tools for viewing the DOM tree.