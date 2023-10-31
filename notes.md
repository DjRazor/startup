### Things I learned about github:
- How to create a personal access token for an easier authentication process
  - Go to profile, settings, personal access tokens, generate a new one
- How to write markdown (https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#lists)
- How to push via VS Code (commit first, add commit notes, save notes, then sync changes).
- How to pull (open gitbash, type git pull)

In the following code, what is the difference between the #title and .grid selector?
- In CSS, the "#" symbol is used to select elements by their id attribute, and the "." (dot) symbol is used to select elements by their class attribute.

In the following code, what is the difference between padding and margin?
- Margin:
  - Margin is the space outside an element, which defines the gap between the element and other elements in the layout. It controls the spacing between the border of an element and its neighboring elements.
- Padding:
  - Padding is the space inside an element, between its content and its border. It is used to create space between the content of an element and the border of that element. Padding can be applied to elements like divs, paragraphs, and headings to control the spacing between the content and the border of the element.

What does the following code output using getElementByID and addEventListener?
- var element = document.getElementById("myElementId");
- element.innerHTML = "New content"

- var button = document.getElementById("myButton");
button.addEventListener("click", function() {
  alert("Button clicked!");
});

What does the following line of Javascript do using a # selector?
- var element = document.querySelector("#myElement");
element.textContent = "This text has been changed using JavaScript!";

Which of the following are true? (mark all that are true about the DOM)
By default, the HTML span element has a default CSS display property value of: 
- Property value of inline. This means that a <span> element is treated as an inline-level element within the flow of text or other inline content, and it does not create a line break or a block-level box on its own. Instead, it is used to style or group a portion of inline content. You can change the display property value for a <span> element in your CSS to make it behave as a different type of element, such as block or inline-block, depending on your layout needs.

In the CSS box model, what is the ordering of the box layers starting at the inside and working out?
+------------------------+
|   Margin (outermost)  |
|                        |
|   +----------------+   |
|   |   Border       |   |
|   |                |   |
|   |   +--------+   |   |
|   |   | Padding|   |   |
|   |   |        |   |   |
|   |   | Content|   |   |
|   |   |        |   |   |
|   |   +--------+   |   |
|   |                |   |
|   +----------------+   |
|                        |
+------------------------+

What is the correct syntax for creating a javascript object?
- var person = {
  firstName: "John",
  lastName: "Doe",
  age: 30,
  isStudent: false,
  hobbies: ["reading", "gaming"],
  address: {
    street: "123 Main St",
    city: "Exampleville"
  },
  sayHello: function() {
    console.log("Hello, my name is " + this.firstName + " " + this.lastName);
  }
};

Is it possible to add new properties to javascript objects?
Yes, dot notation and list notation

If you want to include JavaScript on an HTML page, which tag do you use?
<script src="main.js"></script> 

What does the console command chmod, pwd, cd, ls, vim, nano, mkdir, mv, rm, man, ssh, ps, wget, sudo  do?
- chmod: Used to change the permissions (read, write, execute) of files or directories in Unix-like operating systems. It allows you to control who can access, modify, or execute a file.
- wget: Used to download files from the internet. It allows you to retrieve files from web servers via HTTP, HTTPS, or FTP protocols.
- sudo: Stands for "Superuser Do." It is used to execute commands with superuser or administrative privileges. It is often used to perform tasks that require elevated permissions on Unix-like systems.

Which of the following is true when the -la parameter is specified for the ls console command?
- File types and file permissions

Which of the following is true for the domain name banana.fruit.bozo.click, which is the top level domain, which is a subdomain, which is a root domain?
Is a web certificate is necessary to use HTTPS.
- Yes

Port 443, 80, 22 is reserved for which protocol?
- Port 443 is reserved for the HTTPS (Hypertext Transfer Protocol Secure) protocol, which is the secure version of HTTP. It is used for secure communication over the web, encrypting data exchanged between a web server and a user's web browser.
- Port 80 is typically associated with the HTTP protocol, which is used for standard web communication. While it's not "reserved" in the same way that port 443 is for HTTPS, port 80 is commonly used for unencrypted web traffic.
- Port 22 is reserved for the SSH (Secure Shell) protocol, which is used for secure remote access and administration of computer systems. It provides secure, encrypted communication between a client and a server, commonly used for managing remote servers and devices.
