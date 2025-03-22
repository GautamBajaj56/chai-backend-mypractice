# chai aur backend series 

this is a video series on backend with javascript 

.gitkeep is used to keep track of temporary folders which dont have any file in them yet but we still wants git to track them so that we can push them urgently without any major file in it.

files written or fields under .gitignore file are not tracked or pushed onto git as they contain some private information so for security reasons not pushed.

nodemon is imported to restart the server whenever any change is made automatically. 

prettier is downloaded for cleaner code formatting and readibility.

a prettierignore file is made so that it dont touch env variables which had a slight weird formatting by defualt.

there are two types of dependencies dev and dev dependencies dev dependencies are required only for development phase(nodemon, prettier) whereras dependencies are used in production ( express , mongoose)

also we write in package.json type : module so to implement modular import synatx in our project rather than require syntax.