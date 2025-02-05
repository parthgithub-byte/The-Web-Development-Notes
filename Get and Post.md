# Get and Post
To send the HTML content within a form, we need the HTML methods **get** and **post**.
Let's consider the previous code on forms:  
```html
    <form>
        <fieldset>
            <input type="text" id="name">
            <label for="name">Enter your name</label>
            <br>
            <textarea name="" id="address" cols="30" rows="2"></textarea>
            .
            .
            .
            <label for="eng">English</label><br>
            <input type="checkbox" name="" id="hin">
            <label for="hin">Hindi</label><br><br>

            <input type="submit" value="Submit the form">
        </fieldset>
    </form>
```  

## Get Method:
```html
    <form method="get">
        <fieldset>
            <input type="text" id="name">
            <label for="name">Enter your name</label>
            <br>
            <textarea name="" id="address" cols="30" rows="2"></textarea>
            .
            .
            .
            <label for="eng">English</label><br>
            <input type="checkbox" name="" id="hin">
            <label for="hin">Hindi</label><br><br>

            <input type="submit" value="Submit the form">
        </fieldset>
    </form>
```  
Data is updated in the URL link and thus given to the server via link itself. Suppose originally the url was : `http://127.0.0.1:5500/.git/demo.html`, then after updating the info, it becomes something like this: `http://127.0.0.1:5500/.git/demo.html?gender=on`. Even more info maybe updated in various forms though the URL link.

## Post Method:
```html
    <form method="post" target="blank">
        <fieldset>
            <input type="text" id="name">
            <label for="name">Enter your name</label>
            <br>
            <textarea name="" id="address" cols="30" rows="2"></textarea>
            .
            .
            .
            <label for="eng">English</label><br>
            <input type="checkbox" name="" id="hin">
            <label for="hin">Hindi</label><br><br>

            <input type="submit" value="Submit the form">
        </fieldset>
    </form>
```  
Here, the URL is static. The data is loaded directly and a submitting blank page appears by dafault. Here, I mentioned the target to be blank to not open the page in the same tab. What appears inplace of the blank space depebds entirely on the server code.  
When updating the data, for the radio attributes or the checkboxes, to send the options, we can send the selected ones using the `value` of the respective option.  
```html
            <input type="radio" name="gender" id="male" value="male">
            <label for="male">Male</label> <br>
            <input type="radio" name="gender" id="female" value="female">
            <label for="female">Female</label> <br>
            <input type="radio" name="gender" id="other" value="other">
            <label for="other">Other</label> <br>
```
Thus, the value attribute makes a categorical sense on the backend.
