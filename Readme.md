## We will learn HTML and CSS here in this course

### things to buid in this course
> cat phot app
> modern technique css variables
> Quize site
> webpage that respond to different screen sizes 
> build photo galay with flexbox
> magazine article layout with CSS grid

<!-- HTML -->

1) heading tages (h1 >> h2 >> h3 >> ....>>h6)
- there must be only one h1 tage per page
- use other lesser heading tags according to importance

2) Paragraph tag

3) comment in HTML 
<!-- message -->

### Step 5
HTML5 has some elements that identify different content areas. These elements make your HTML easier to read and help with Search Engine Optimization (SEO) and accessibility.

Identify the main section of this page by adding a <main> opening tag before the h1 element, and a </main> closing tag after the p element.

### Step 7
You can add images to your website by using the img element. img elements have an opening tag without a closing tag. A tag for an element without a closing tag is known as a self-closing tag.

Add an img element below the p element. At this point, no image will show up in the browser.

### Step 8
HTML attributes are special words used inside the opening tag of an element to control the element's behavior. The src attribute in an img element specifies the image's URL (where the image is located).

A link's text must be placed between the opening and closing tags of an anchor (a) element. For example, <a href="https://www.freecodecamp.org">click here to go to freeCodeCamp.org</a> is a link with the text click here to go to freeCodeCamp.org.

### Step 11
A link's text must be placed between the opening and closing tags of an anchor (a) element. For example, <a href="https://www.freecodecamp.org">click here to go to freeCodeCamp.org</a> is a link with the text click here to go to freeCodeCamp.org.

### Step 14
Add a target attribute with the value _blank to the anchor (a) element's opening tag, so that the link opens in a new tab.


### Step 16
Before adding any new content, you should make use of a section element to separate the cat photos content from the future content.

### Step 19
When you add a lower rank heading element to the page, it's implied that you're starting a new subsection.

### Strp 20 
figure tag is use to nested image inside it 
<figcaption></figcaption> tag is use ;to give caption to the figure 


### Step 25
Emphasize the word love in the figcaption element by wrapping it in an emphasis em element.

Step 32
The strong element is used to indicate that some text is of strong importance or urgent.

### Step 32
In the figcaption you just added, indicate that hate is of strong importance by wrapping it in a strong element.

### Step 37
The input element allows you several ways to collect data from a web form. Like img elements, input elements are self-closing and do not need closing tags.

### Step 38
> Input tage 
> type=""
> name=""
> placeholder

### Step 41
To prevent a user from submitting your form when required information is missing, you need to add the required attribute to an input element. There's no need to set a value to the required attribute. Instead, just add the word required to the input element, making sure there is space between it and other attributes.


Step 42
Use the button element to create a clickable button. For example, <button>Click Here</button> creates a button with the text Click Here.

### Step 42
Add a button element with the text Submit below the input element. The default behavior of clicking a form button without any attributes submits the form to the location specified in the form's action attribute.

### Step 43
Even though you added your button below the text input, they appear next to each other on the page. That's because both input and button elements are inline elements, which don't appear on new lines.

The button you added will submit the form by default. However, relying on default behavior may cause confusion. Add the type attribute with the value submit to the button to make it clear that it is a submit button.

### Step 45
label elements are used to help associate the text for an input element with the input element itself (especially for assistive technologies like screen readers). For example, <label><input type="radio"> cat</label> makes it so clicking the word cat also selects the corresponding radio button.

### Step 46

If we want to make any one radio button of 2 or more button availablewe have to make their name attribute same 

### Step 50
The fieldset element is used to group related inputs and labels together in a web form. fieldset elements are block-level elements, meaning that they appear on a new line.

### Step 51

> legend element

The legend element acts as a caption for the content in the fieldset element. It gives users context about what they should enter into that part of the form.

Add a legend element with the text Is your cat an indoor or outdoor cat? above both of the radio buttons.

### Step 54

Forms commonly use checkboxes for questions that may have more than one answer. For example, here's a checkbox with the option of tacos: <input type="checkbox"> tacos.

>!NOTE
> the value attribute for should be equal to id attribute of corresponding input element
```html
    <input id="loving" type="checkbox" > 
    <label for="loving" > Loving </label>
```

### Step 69
You can set browser behavior by adding self-closing meta elements in the head. Here's an example:
```html
<meta attribute="value">
```

Tell the browser to parse the markup into multiple languages by creating a meta element as a child of the head element. Set its charset attribute to UTF-8.