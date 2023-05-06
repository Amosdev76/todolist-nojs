# todolist-nojs

html/css to do list with no javascript


it's an experimental to do list with only html/css

NOTES: 

1) the following css is not ready for production because only some browser can correctly read :has


 .todo:has(.todo__checkbox:checked) {
    color: #555555;
    background: #eeeeee;
    text-decoration: line-through;
    order: 1; 
    }
    
 it works with google chrome
 
 2) you can't add items dinamically without javascript but only with html code



you can find it online on :

https://todolistnojs.netlify.app/
