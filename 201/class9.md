# 201 class 9 notes

**Why this matters**: This information matters because because it discusses web forms, which are an important way to interact with and get information from users, and events, which will allow your code to respond to user input. 

------------------------------------

## How To Structure A Web Form

Source: [https://developer.mozilla.org/en-US/docs/Learn/Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)

Source: [https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)

**1. Why are forms so important in web development?**

Because they are a powerful tool for user interaction and provide a way to collect user data or allow users to control a user interface.

**2. When designing a form, what are some key things to keep in mind when it comes to user experience?**

- Form validation: to make sure that the data users enter into forms is in the correct format to be successuflly processed and to help users fill out the form correctly and not get frustrated.

- Pairing form controls with text labels that describe their purpose will help both sighted and visually impared users.

**3. List 5 form elements and explain their importance.**

- `<form>` formally defines a form and is a container element specifically for containing forms. It will also support some attributes to configure the way a form behaves. Its attributes are optional, but standard practice is to at least include `action` and `method` attributes.

- `<label>` will contain the text fields in your form, for example, 'name' 'email' and 'message' in a contact form.

- `<input>` The most important attribute is the `type` attribute because it defines the way the `input` element appears and behaves.

- `<textarea>` is not a void element, which means it needs an ending tag, which impacts the way you define the default value. Using `input`, the value would otherwise be defined in quotes and without an ending tag.

- `<button>`allow users to send or 'submit' their data after adding information to a form.


-----------------------------------

## Intro to Events

Source: [https://developer.mozilla.org/en-US/docs/Learn/JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)

Source: [https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

**1. How would you describe events to a non-technical friend?**

Events are actions that happen on your site that your code will need to react to. For example, when a user clicks a button on your page, your code will need to do something, like display an information box.

**2. When using the `addEventListener()` method, what 2 arguments will you need to provide?**

- The name of the event

- A function to handle the event

**3. Describe the event object. Why is the target within the event object useful?**

THe event object `event` `evt` or `e` is the name of a parameter within an event handler function. It's useful because it automatically passes extra features and information to event handlers.

**4. What is the difference between event bubbling and event capturing?**

- Event bubbling is how the browser handles events targeted at nested elements. To do this, the event fires first on the innermost element targeted and then on successively less nested elements.

- Event capturing is like event bubbling but the order is reversed, where the event fires first on the least nested element and then on the successively more nested elements until the target is reached.


------------------------------------
### Things I Want To Know More About:
Nothing at the moment!