Readme (delete the above when you're ready to submit, and modify the below so with your links and descriptions)
---

## WPI Gordon Library Book Borrowing Tracker
This project is a simple library loan management web application that allows users to add, modify, and delete loan entries. Each entry includes details such as the item name, author, library section, borrowed date, due date, and the calculated number of days remaining until the item is due. CSS positioning is handled with flexbox, which provides a clean layout for the form and table.

Instructions:
- Start the server with node server.js.
- Open a browser and navigate to http://localhost:3000.
- Use the input form to add new loans.
- Use the Delete button to remove entries or the Modify button to edit existing ones.
- The table will update automatically with the current loan data, including recalculated days remaining.

## Technical Achievements
- **Tech Achievement 1**: Using a combination of server-side JavaScript and Fetch API to implement a single-page app that dynamically updates a loan table with a derived daysRemaining field whenever data is added, deleted, or modified.
- **Tech Achievement 2**: Implementing full CRUD functionality (add, delete, and modify operations) on server-side data, with immediate client-side rendering of updates in the table.

### Design/Evaluation Achievements
- **Design Achievement 1**: Used CSS flexbox to center and separate the contents of the webpage in an organized manner.
- **Design Achievement 2**: Used Google Font "Merriweather" for the styling of the entire page.
- **Design Achievement 3**: Used ID selectors for the results table buttons and class selectors for flexbox.
- **Evaluation Achievement**:
    1. Provide the last name of each student you conduct the evaluation with.
       Ngo, Rivera.
    2. What problems did the user have with your design?
       They both found that the modification design could have been cleaner without using console, and that individually being asked to modify each tab (even if they didn't want to) was tiring.
    3. What comments did they make that surprised you?
       Ngo commented that the loan form wasn't as intuitive (which I thought it was!) and that the prompts could have been more specific, especially for the "item". Rivera suggested that the table could have been sorted by urgency (ordered by derived field "days remaining"), which I did think about briefly but was surprised that someone else thought about that too.
    4. What would you change about the interface based on their feedback?
       I would definitely take both of their suggestions to make the modification ability cleaning and more efficient to use. Following Rivera's comment, if I had more time, I would also add the ability to filter the table, or at the very least default sort them by the number of days remaining on the item.
       
