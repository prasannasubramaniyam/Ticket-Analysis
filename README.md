# Ticket-Analysis
Customer Ticket Analysis Python
Module End Assignment Python
Customer Support Ticket Analyzer
Summary Report

 
📌 Project Overview
●	Project Title: Customer Support Ticket Analyzer
⮚	📂 Data handling
⮚	⌨️ User input processing
⮚	🔀 Conditional logic
⮚	📊 Basic data analysis
 
🎯 Project Objective
●	🧩 Simulate a customer support ticket management system
●	🗂️ Store predefined customer complaints
●	➕ Allow users to add new tickets dynamically
●	📈 Perform analytical operations such as:
⮚	🔢 Counting ticket priorities
⮚	📋 Displaying ticket details
 


● from initializing ticket data to generating insights through keyword analysis and text processing.
 
🥇 1: Preloaded Tickets
●	📦 A dictionary named ticket_data is initialized
●	🗃️ It serves as the main data repository for customer tickets
●	🧾 Contains 10 predefined tickets, each with:
⮚	🆔 Ticket_No
⮚	👤 Customer_Name
⮚	📝 Issue_Description
⮚	⚡ Priority(high/Medium/Low)
Implementation Highlights:
●	📚 Data stored using a Python dictionary
●	🖨️ print() function used to display the dataset
Key Outcome:
●	✅ Initial ticket dataset with 10 complete records is displayed successfully
 
➕ Step 2: Add More Tickets (User inputs)
●	🧍 User-specifies number of new ticket creation is enabled
●	Workflow includes:
⮚	🔢 Asking how many tickets to add
⮚	🧾 Collecting:
✔	Customer name
✔	Issue description
✔	Priority level
⮚	✅ Validating priority (High / Medium / Low only)
⮚	🔼 Auto-incrementing ticket numbers
⮚	📥 Appending new entries to the dictionary
Implementation Highlights:
●	⌨️ input () for interaction
●	🔁 for loop for ticket entry
●	🔄 while loop for priority validation
●	🧮 max () to find the last ticket number
●	📌 append () for updates
Key Outcome:
●	✅ Updated ticket dataset displays new tickets with correct numbering and validated priorities
 
🧹 Step 3: data Cleaning for & Pre-Processing
●	Implemented using a custom function clean text ():
⮚	🔡 Converting text to lowercase
⮚	🔁 Replacing shorthand words:
✔	✂️ Removing punctuation
⮚	📏 Normalizing extra spaces
⮚	🧽 Trimming leading and trailing spaces
Implementation Highlights:
●	📚 re and string modules
●	🧠 re.sub() with word boundaries
●	🧩 str.lower(), str.translate(), str.strip()
Key Outcome:
●	✨ Example transformation:
⮚	“internet connection issue” → “internet connection problem”
 
🔍 Step 4: Keyword-Based Issue Insights
●	🔎 A function count tickets with word() analyses keyword frequency
●	🧪 Case-insensitive search
●       📊counts how many issue  descriptions contain a given word
Keywords Analysed:
●	🟠 poor → 1 ticket
●	🟢 good → 1 ticket
●	🐢 slow → 2 tickets
●	🌟 excellent → 0 tickets

Implementation Highlights:
●	🔁 Loop through descriptions
●	🔎 Keyword detection using word .lower() in description .lower()
Key Outcome:
●	📊 Recurring terms related to service quality and speed are identified
●tested with words like:
Poor, slow, good, excellent.
 
📊 Step 5: Final Summary & Analysis
📌 Final Cleaned Dataset
●Users Counter From collections
●Counts
●🧾 Fully cleaned ticket_ data dictionary is displayed
 
⚡ Priority Distribution
●	🔴 High Priority → 5 tickets
●	🟡 Medium Priority → 3 tickets
●	🟢 Low Priority → 3 tickets
 
🏆 Longest Issue identification
●	🆔 Ticket No: 2
●	👤 Customer Name: Meera
●	📝 Cleaned Text: “slow response, very poor service”
●	📏 Word Count: 5
 


🧠 Unique Word Extraction
●	🧩 All unique words extracted and sorted
●	📊 Total Unique Words: 28
Sample Words:
account, app, billing, crashing, delay, delivery, general inquiry, internet, issue, issues, login, malfunction, needed, not, poor, problem, product, refund, request, response, 'server', service, slow, support, technical, very, working.

🏁 Final & Insights

●	✅ Modular design using functions
          ✅Clean data improves accurate analysis 
●	🏆 Key achievements:
⮚	📂 Efficient ticket storage
⮚	🧹 Advanced text cleaning
⮚	📊 Priority-based analysis
⮚	🔍 Keyword-based insights
⮚	🧠 Unique word extraction
