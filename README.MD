# CSS Utils
## CSS Forms
Tired of Styling HTML Forms? Simply include this form.css in to your HTML file.
### Note
* All the input fields, labels, buttons should we wrapped inside div with a class **'form-group'** or **'form-inline-group'** based on the usecase
* forms should given a class of **'form'**

### Form Style 1
This has a simple Styling.
* All the input type has a class name of **'input'**
* Label have a class name of **'label'**
* select element has a class name of **'select'**
<br> <br>
<img src="./images/form-style-1.JPG" />

### Form Style 2
This has a Modern Styling.
* All the input type has a class name of **'input-2'**
* Label have a class name of **'label-2'**
* select element has a class name of **'select-2'**
<br> <br>
<img src="./images/form-style-2.JPG" />

### Inline Forms
* Inline form elements has to wrapped inside a div having class name as **'form-inline-group'**
<br> <br>
<img src="./images/inline-form.jpg" />  

### Buttons
* Buttons have a class of **'btn'**
* To make a Button to take full width wrap it inside a **'form-group'**
* To change background color add one these class along with **'btn'**
    * **'btn-blue'**
    * **'btn-pink'**
    * **'btn-purple'**
    * **'btn-grey'**
    * **'btn-success'** 
    * **'btn-danger'** 
    * **'btn-warning'** 
<br> <br>
<img src="./images/button.jpg" /> 

* To change sizeof button add one these class along with **'btn'**
    * **'btn-sm'**
    * **'btn-lg'**
<br> <br>
<img src="./images/button-size.jpg" /> 

### Sample Code
```html
<h1 >Message Form</h1>
<form class="form" >
    <div class="form-group">
        <input class="input-2" type="text" placeholder="Enter your Name"  required>
    </div>

    <div class="form-group">
        <input type="text" placeholder="Type a Message" class="input-2" required>
    </div>
    <button class="btn" type="submit" >Send</button>
</form>
```


