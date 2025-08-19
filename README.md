# Simple-Python3-Emulator-For-Github-IO
## I use this to host my python3 programs on github. 
- It uses pyodide library.
- It's a highly useful low complexity solution that saves me actual money as I don't have to go pay for a service like trinket to run and share my python 3 snippets on web.

## Contribution
- Feel free to fork and raise PRs if you have any changes in mind.

## How to use
### 1 - Download and open index.html
### 2 - Find and replace text inside text area with id = "code" with your python code. 
    Look below for IMPORTANT formatting notes or minor changes you might have to make to make your code "web friendly"
### 3 - Host it wherever you want :)
### 4 - (Optional) Open and test by clicking run!
IMPORTANT: It's absolutely crucial that your python code within the text-area is indented correctly. 
    - This means you can't have space between <textarea>tags and start/end of your code 
        <textarea id="code">print("Welcome to the rollercoaster!")<textarea/> 
        observe how there's no spaces in start and end between code and tag
IMPORTANT: Put 'Await' before any input in python so height = int(input("What is your height?")) becomes height = int(await input("What is your height?"))

Note for beginners -  you can play around with the text live but it won't save so any permenant changes will have to be made in html file that you are hosting. 

Give it a star if it saved you a few $
