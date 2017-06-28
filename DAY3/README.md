DAY 3-  CSS Variables

Task: Work with CSS variables
How to get it done and things I learnt:

- CSS variables are unique, they help to update css without going into css because they can be updated using Javascript.
- Before using CSS variables, they need to be declared in ":root{...}"  in your style tags or css doc.
- they are declared following the syntax  :root{  --base: 20px; --color: #fffff; }
- So, In this task, we are to edit the padding color, spacing and blur of an image using and controls. The min and max value have already been set.
- Next, You declare your css variables, so we can cause immediate change on the image. using Javascript
-  After declaring css variables, we give the image the min padding and background color and the blur filter.
- In JS, we create a variable, input that selects all the input for the controls in our html and then we create a function- handleUpdate
- This function selects our input parameter and sets a property equal to the chosen input and adds a suffix of the unit 'px' to the parameterin the range of the controls.
- with our function and variables already declared, we need to add an Event Listener, that Listens for an event of mouse movement or change in the controls to run the function.
- other things Learnt:
    - QuerySelector gives a nodelist which is similar to an array. However a  nodelist has fewer methods compared to and array.
    - Data attributes are made up by you however, you need to add a suffix e.g "data-sizing" or "data-key"
    - .dataset creates an object containing every data attributes