#ES Project : EERC, IIIT-Hyderabad.

This repository contains code for the portal being developed as part of the ES project. 


##Coding conventions


###For forms

Create separate file for each form, with the name [form-x].php

Here is an example format for the form file: 

```
<form action="form-x-backend.php">

<input type="text" name="username" placeholder="Enter your full name" />

.
.
.

</form>
```

Note: Do not put `<html>` or other header tags in the form files. Just the form element. 

####THIS SECTION HAS BEEN MODIFIED
Earlier, it was mentioned that `All form files should be created in root directory (with the js and css folders)`.
However, now the directory structure has been changed due to new information that was brought to attention.

Forms have several sub components, each of which can be put in a separate folder. 
So, here's what the final structure looks like:
```
|-js (directory)
|-css (directory)
|- <all other files>
|-form1_mudhouse (directory)
    |-1st_subComponent (directory)
        |-page1.php (the form file)
        |-page2.php
    |-2nd_subComponent  (directory)
    
... Similarly for all forms
```
Please let me know if there are questions.

###For Javascript

Will be added.


###For CSS

Will be added.


###For PHP

Will be added.
