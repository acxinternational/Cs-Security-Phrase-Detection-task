# Task: Security Phrase Detection in Customer Support Tickets
Objective: Build a minimal web application that fetches customer support ticket history from a mock API, processes the data using a GPT-3.5 Turbo LLM Model, and displays the results in an interface.
 
# Scope: The application should
  1. Fetch mock ticket data from the following mock API endpoint https://goruen.free.beeceptor.com/tickets-history.
  2. Detect specific phrases and words in the conversation history.
  3. Display the detected messages that have security issue phrases.

# Examples of security words or similar phrases to be detected:
  - my account was hacked
  - My funds are stolen
  - My access was compromised
  - Someone got access to my account
  - I have lost my funds

# Requirements:
  - Backend:
    1. Create a mock RESTful API using JAVA or Python or any prefered backend library to serve ticket data.
    2. Implement a sentiment analysis function that detects certain phrases and words.
   
  - Frontend:
    1. Use React.js to build a simple interface.
    2. Show detected messages as a result.
    3. Your design should adhear to the figma design https://www.figma.com/design/3UhOy22CSHLL4WBW3vzrR7/ACX-Test-Task?node-id=1-2
   
# Detailed Steps:
  - Backend Development:
    1. Set up a preferred backend library.
    2. Create an endpoint /api/tickets that returns mock ticket data.
    3. Implement a security phrase detection that detects specific phrases/synonyms in the ticket history.

  - Frontend Development:
    1. Set up a React.js project using Create React App.
    2. Fetch ticket data from the backend API.
    3. Display the ticket history and sentiment analysis results in a table.

# Evaluation Criteria:
  - Technical Skills:
    1. Effective communication between frontend and backend.
    2. Balancing between working independently and asking the right questions.
    3. Ability to write a code that adhears to Clean Architecture.

  - Code Quality:
    1. Clean, maintainable, and readable code.
    2. Proper use of version control (Git) and adherence to best practices.
    3. Adhearence to SOLID principals.

# Submission:
  - Please create a repository with your name, and push your solution to it.
  - Duration: You have 2 hours to complete this task.
