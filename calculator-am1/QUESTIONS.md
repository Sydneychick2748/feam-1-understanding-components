# Understanding Components

**Answer the following questions**

1. Which folder holds the components?
   components are stored in the src/components folder.
2. Which component is the parent of all other components?
   The top-level component, App
3. Where would you add a folder for images? Another way to ask is, which folder will be the parent of the images folder?
   You would add a folder for images inside the public directory. The public directory is the parent of the images folder.
4. Does App have any grandchildren? How do you know?
   no Because you look at the import app has and see if they have any imports to make them grandchildren
5. What do you notice about the css files?
   that each component has there own css file that is begin imported
6. How are the css files connected to the js files? (Look at the top of the js files for clues)
   they are imported into the file that wants to used the file
7. Look at the HTML file. What do you notice?
   there is no html and there is only
   <div id="root"></div>
