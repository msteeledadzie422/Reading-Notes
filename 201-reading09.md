# HTML Forms

1. Web forms are one of the main points of interaction between a user and a web site or application. Forms allow users to enter data, which is generally sent to a web server for processing and storage (see Sending form data later in the module), or used on the client-side to immediately update the interface in some way (for example, add another item to a list, or show or hide a UI feature).

2. Before starting to code, it's always better to step back and take the time to think about your form. Designing a quick mockup will help you to define the right set of data you want to ask your user to enter. From a user experience (UX) point of view, it's important to remember that the bigger your form, the more you risk frustrating people and losing users. Keep it simple and stay focused: ask only for the data you absolutely need.

3. Form Element: Formally defines a Form
   Label Element: Defines the text fields of a form
   Input Element: On the <input> element, the most important attribute is the type attribute. This attribute is extremely important because it defines the way the <input> element appears and behaves
   Textarea Element: The input field for a message
   Button Element: How the user sends or submits their data
   
# Learn JS

1. Events are fired inside the browser window, and tend to be attached to a specific item that resides in it. This might be a single element, a set of elements, the HTML document loaded in the current tab, or the entire browser window. There are many different types of events that can occur.
   
   For example:
    - The user selects, clicks, or hovers the cursor over a certain element.
    - The user chooses a key on the keyboard.
    - The user resizes or closes the browser window.
    - A web page finishes loading.
    - A form is submitted.
    - A video is played, paused, or finishes.
    - An error occurs.

2. The name of the event we want to register this handler for, and the code that comprises the handler function we want to run in response to it.

3. Sometimes, inside an event handler function, you'll see a parameter specified with a name such as event, evt, or e. This is called the event object, and it is automatically passed to event handlers to provide extra features and information. Most event objects have a standard set of properties and methods available on the event object; see the Event object reference for a full list. Some event objects add extra properties that are relevant to that particular type of event. For example, the keydown event fires when the user presses a key. 

4. When an event is fired on an element that has parent elements (in this case, the <video> has the <div> as a parent), modern browsers run three different phases — the capturing phase, the target phase, and the bubbling phase.

   In the **capturing phase**: The browser checks to see if the element's outer-most ancestor (<html>) has a click event handler registered on it for the capturing phase, and runs it if so. Then it moves on to the next element inside <html> and does the same thing, then the next one, and so on until it reaches the direct parent of the element that was actually clicked.

   In the **target phase**: The browser checks to see if the target property has an event handler for the click event registered on it, and runs it if so. Then, if bubbles is true, it propagates the event to the direct parent of the clicked element, then the next one, and so on until it reaches the <html> element. Otherwise, if bubbles is false, it doesn't propagate the event to any ancestors of the target.

   In the **bubbling phase**: the exact opposite of the capturing phase occurs: The browser checks to see if the direct parent of the clicked element has a click event handler registered on it for the bubbling phase, and runs it if so. Then it moves on to the next immediate ancestor element and does the same thing, then the next one, and so on until it reaches the <html> element.
  
  




