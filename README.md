# Hang In There: Liliana Weimer, Naomi Ware

A boilerplate repo.

This is the first paired project from Turing's Mod 1. We are attempting to create a dynamic webpage that allows users to access a random inspirational poster or create one of their own.




## Set Up

1. One teammate: fork this repository
2. Go to settings and turn on GitHub Pages for this repository
3. All teammates: clone down this repository
4. `cd` into the repository
5. Run `open index.html` to view it in the browser

You can find this project at https://github.com/nware1066/hang-in-there-boilerplate

## Progression

### Iteration 0 - Main Page

During this Iteration, we discussed the project requirements and agreed on how we would communicate and share the workload, as well as setting limits on how long we would wait to request help if we were struggling.

You can check the notes on our discussion here https://gist.github.com/lilianaweimer/96f81662a0d46525d5d4969b511e8419

If you would like a more detailed look at what we were doing, you can read the instructions for our project below

![screenshot of main page showing poster](/readme-imgs/homepage.png)

- When the page loads, we should see a poster with a randomly selected image, title, and quote



### Iteration 1 - Switching Views

We started filling out the framework elements of the project, such as querySelectors and eventListeners. We were able to get the page to display random posters and have most of the buttons functioning so that users could move between sections of the webpage.

If you would like a more detailed look at what we were doing, you can read the instructions for our project below

Form page:
![screenshot of form](/readme-imgs/form.png)

Saved posters page (once working with extra saved posters):
![screenshot of saved posters page](/readme-imgs/saved.png)

- When a user clicks the "Make Your Own Poster" button, we should see the form, and the main poster should be hidden
- When a user clicks the "View Saved Posters" button, we should see the saved posters area, and the main poster should be hidden
- When a user clicks the "Nevermind, take me back!" or "Back to Main" buttons, we should only see the main poster section
- In summary: Be able to switch between the three views (main poster, form, and saved posters) on the correct button clicks

_Hint: go check out the HTML and CSS files to see how the form and saved posters sections are being hidden in the first place_

## Iteration 2 - Creating a New Poster

In this Iteration we tested our ability to work together when the project was challenging. After several attempts we were able to successfully create and display a custom poster. We found pulling user input into the code to be particularly challenging.
We then enjoyed being able to create on our functioning webpage.

If you would like a more detailed look at what we were doing, you can read the instructions for our project below


Form being filled out:
![screenshot of form](/readme-imgs/form.png)

Once poster is saved:
![screenshot of result](/readme-imgs/form-result.png)


- On the new poster form view, users should be able to fill out the three input fields and then hit the save button
- When the save button is clicked, several things will happen:
  - Save the submitted data into the respective arrays (image URL into the images array, etc) so that future random posters can use the user-created data
  - Use the values from the inputs to create a new instance of our Poster class
  - Change back to the main poster view (hiding the form view again)
  - Display the newly created poster image, title, and quote in the main view

## Iteration 3 - Saving & Viewing Posters

In this Iteration we were challenged to allow users to save their posters in a separate area of the webpage. This required a great deal of searching the internet for options and asking for support before we were able to make it work and we learned several new skills.

If you would like a more detailed look at what we were doing, you can read the instructions for our project below

Saved posters view:
![screenshot of saved posters section](/readme-imgs/saved.png)

- When a user clicks the "Save This Poster" button, the current main poster will be added to the `savedPosters` array.
- If a user clicks the "Save This Poster" more than once on a single poster, it will still only be saved once (no duplicates)
- When a user clicks the "Show Saved Posters" button, we should see the saved posters section
- All the posters in the `savedPosters` array should be displayed in the saved posters grid section

## Iteration 4 - Deleting Saved Posters

- From the saved posters view, if a user double clicks a saved poster, it will be deleted

_Hint: How will you update the data model to achieve this?_

## Optional Extensions - Gettin' fancy

Here's a list of possible extensions to implement - but **ONLY IF** your team has completed all the previous iterations **AND** have cleaned up your code to make it DRYer and more readable.

You are welcome to add your own extensions. Be sure they are thoughtful in terms of UX/UI, and that they do not break any prior functionality.

- Implement data validation and error handling into the form (disable button, provide error messages if data entered is not correct, etc)
- In the main poster view, allow users to click each piece of the poster (image, title, quote) to update just that piece with another random item from the appropriate array
- When a user single clicks a saved poster, create a modal to view it larger
- Allow users to drag and drop saved posters into whatever order they want them to appear


Project spec & rubric can be found [here](https://frontend.turing.io/projects/module-1/hang-in-there.html)
