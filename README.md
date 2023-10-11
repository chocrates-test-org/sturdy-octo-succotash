<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

## Pre-Requisites
Before following the steps below, please anble CoPilot in your editor and clone this repository locally
Instructions for enabling CoPilot can be found in this [document](https://docs.github.com/en/copilot/getting-started-with-github-copilot?tool=vscode)

## Step 1: Seeing AI code suggestions in a Javascript file!

GitHub Copilot provides suggestions for numerous languages and a wide variety of frameworks, but works especially well for Python, JavaScript, TypeScript, Ruby, Go, C# and C++. The following samples are in JavaScript, but other languages will work similarly.

Let's try this out utilizing Javascript for Copilot.

### :keyboard: Activity: Add a Javascript file and start writing code

1. From inside the editor in the VS Code explorer window, create a new file.
2. Name the file `skills.js`
3. Verify your new file looks like:
   ![Screen Shot 2023-03-09 at 9 21 34 AM](https://user-images.githubusercontent.com/26442605/224105906-d1beb531-b747-4c7a-85ba-a12526488422.png)
4. In the `skills.js` file, type the following function header.

   ```
   function calculateNumbers(var1, var2)
   ```

   GitHub Copilot will automatically suggest an entire function body in grayed text. Below is an example of what you'll most likely see, but the exact suggestion may vary.
   ![Screen Shot 2023-04-27 at 10 23 06 AM](https://user-images.githubusercontent.com/26442605/234941079-b4bf3e9d-fc70-4b20-b74c-0ee753ba344e.png)

5. Press `Tab` to accept the suggestion.

### :keyboard: Activity: Push code to your repository from the editor

1. Use the VS Code terminal to add the `skills.js` file to the repository:

   ```
   git add skills.js
   ```

2. Next from the VS Code terminal stage and commit the changes to the repository:

   ```
   git commit -m "Copilot first commit"
   ```

3. Finally from the VS Code terminal push to code to the repository:

   ```
   git push
   ```

**Wait about 60 seconds then refresh your repository landing page for the next step.**
