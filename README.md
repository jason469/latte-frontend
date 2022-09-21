# Latte's Frontend
> Created by Jason Liu

### What is Latte?
Latte is an image categorisation application created for a small audience. <br>
It allows users to upload **images** onto the application, where they can assign them to **tags** or add them to **albums**. <br>
**Images**, **tags** and **albums** can all be named and have a description attached to them, which can be edited in the front or backend.
<br><br>
Images, tags and albums can also all be deleted from the frontend as well. <br>
Latte does have authentication in that a username and password is needed to access the application (which can only be administered by an admin)


### What technologies does Latte use?
Latte uses _**React**_ as the frontend framework (shown in this current repository).
<br><br>
In the backend, I've used the _**Django Rest Framework**_ to create an API for the frontend to connect to. <br>
This backend is connected to a _**PostgresSQL database**_. <br>
For security, the repository storing the backend code has been kept private, however you can explore the source code for the front end here. 
<br><br>
I made the decision to separate the front and backend into separate repositories for security, and to make it easier for me to deploy the application using _**Render**_.

### Moving forward with Latte
Latte is currently in version 1.0 for the production state.<br>
In future, I plan to add more metadata to each image (e.g. allow the user to specify when the image was taken) to allow for improved filtering. <br>
More work also needs to be done to allow for additional image formats (e.g HEIC or SVG formats)
<br><br>

# Where can I see Latte?
To visit Latte, please visit the following link: <br>
> [Latte](https://latte-frontend.onrender.com/)