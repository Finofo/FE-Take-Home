# Welcome!

Hello 👋
We are thrilled about the possibility of you joining our team. This take-home exercise is designed as a basic evaluation to help us understand your skills and how you approach tasks. It's a great opportunity for you to showcase your abilities and for us to see how we might work together.
Thank you for taking the time, and we look forward to speaking with you soon!

### Task Description

Create a basic application using React and TypeScript to display a list of fruits. The application should fetch data from an external API and display the fruits grouped by a specified field.

### Requirements

1. **Data Fetching**
   - Use the Fruityvice API (https://www.fruityvice.com/doc/index.html#api-GET) to fetch the list of fruits.
   - Base API url - https://www.fruityvice.com

2. **Layout**
   - The page should be divided into two sections:
     - **Left Section:** Displays the list of fruits.
     - **Right Section:** Displays the jar with selected fruits.

3. **Group By Functionality**
   - Include a select input with the label “Group by” containing three options: [None, Family, Order, Genus]. The default selection should be "None".
   - **None:** Display a flat list of fruits.
   - **Family, Order, Genus:** Display a collapsible list, with the collapsible header derived from the selected group by field (e.g., if “Group by” is set to Family, the header for Strawberry would be "Rosaceae").

4. **Fruit List**
   - There should be two possible views: Table and List.
   - List view: each fruit entry should be displayed in the format: {fruit name} ({amount of calories}).
   - Table view: show the following columns - name, family, order, genus and amount of calories.
   - Include an "Add" button next to each fruit, allowing the user to add the fruit to a jar. Note that it should be possible to add the same fruit multiple times.
   - Include an "Add" button next to the group name, allowing the user to add all fruits from the group to a jar.

6. **Jar Functionality**
   - The jar should display a list of added fruits.
   - Calculate and display the total amount of calories for the fruits in the jar.
   - The Jar should have the possibility to show a pie chart of the added fruits, with their calories.

### Additional Notes

- You may use any additional libraries as needed to improve the feel and features of the app.
- Consider best practices for data fetching and error handling to simulate real-world applications.
- Ensure the application is user-friendly and visually appealing.
- Commit your work to a public github repo and share the link with us
- Also share the link to a live, deployed version of the application.

### Evaluation Criteria

- Correct implementation of the specified functionality.
- Code quality, including readability, structure, and use of TypeScript.
- Effective use of React components and state management.
- Proper handling of data fetching, including loading states and error handling.

Feel free to add any relevant features or enhancements that you think would improve the application.
