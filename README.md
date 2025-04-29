# Web Agents

***********************************************
### Video: Intro to Web Agents
***********************************************

##What is a Web Agent?

##Autonomous Software Program: 
Automate repetitive tasks, Monitor websites, Gather data

##Applications: 
Search engines, Social media management, Customer support automation, Travel planning and booking, E-commerce assistance (find products and complete purchases), Data Analysis across multiple applications, etc.

##Five Components of Web Agent Architecture:
- User Interface (UI): For user-agent communication in natural language
- Control: For reasoning and decision-making towards actions
- Knowledge Base (KB): For storing important data, rules and information to complete the tasks
- Communication Module: For managing interaction with websites, APIs and other systems
- Data Processing Module: For analyzing, processing and transforming data before returning results

## Key Modules that work together within these Components:
- Parsers: Systematically extract website data and interpret HTML
- Action models: Perform decision-making and predict which actions to take
- Executors: Take specific actions on the website e.g. click, fill form etc.

## Process Flow:
- User sends request to LLM (which understands the request)
- Personalization Enginge personalizes requests based on context
- Action model takes web representation of the website (embeddings) and determines possible actions one can take
- Action model predicts the optimal action in the given setting and Executor performs them
- Repeat until the task is complete  








