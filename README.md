# l6adt_advProg_codeReview
Scenario and code to be used for the Code Review aspect of the ADT Advanced Programming assessment

Scenario:
You work for an independent software engineering business. A small local printing business requires a mechanism for customers to be able to leave feedback about their staff, and they have approached your company, requesting an early prototype of a software solution.  They have asked that this be a web application/page, with the intention that eventually this facility could be added to their company website.
At this early stage, it has been decided that functionality is the most important thing (over aesthetics/UX).  You have delegated development of this initial protoype to your trainee developer.
The trainee has created this repository, containing an early working version of the prototype.  This uses Python and Flask for the back-end, exposing functionality via an API.  A simple HTML, CSS and javascript front-end is also included to allow an early idea of how the solution may eventually work as a web application. You need to perform a Code Review of this prototype (i.e. the python back-end code and the web front-end).

INSTRUCTIONS TO RUN:
- Using the green 'Code' button to the top-right, select 'Codespaces'.
- Open a new Codespace via the 'Create Codespace on main' option (or click on the name of a previous Codespace if it exists).
- This repo has been set up so that the dependencies/set-up for our project are automatically loaded.  In theory this means that once the Codespace opens, all you need to do is open the 'app.py' file and click RUN (or execute 'python app.py' in the Terminal). You may be asked to install the Python extension for VSCode, but that is all the installation that should be needed.
- When the Flask server app starts, you should see a pop-up and be able to click to open in your browser.
- The app loads in a new browser window, where you can enter customer feedback data and save it.  The feedback is saved to the 'feedback.json' file.
- If you want to STOP the app from running, press 'Ctrl + C' in the Terminal.
  
