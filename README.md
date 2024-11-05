# Input_Form
HTML input forms use various tags to gather user data. Key tags include &lt;input>, which supports different data types (e.g., text, email, checkbox), &lt;textarea> for multi-line input, &lt;select> for dropdowns, and &lt;button> for actions. Tags like &lt;label>, &lt;fieldset>, and &lt;legend> improve accessibility and organization within forms.
HTML input forms use various tags to capture and structure user data in a consistent way. Here’s an overview of the most common tags used:

<form>: Defines the form itself and wraps all the input elements. It includes attributes like action (the URL where form data is sent) and method (defines how data is sent, e.g., POST or GET).

<input>: Used to capture data in various formats depending on the type attribute:

type="text": Single-line text input.
type="password": Hides input characters, commonly used for passwords.
type="email": Accepts only email-formatted text.
type="number": Allows only numeric input, often with min/max values.
type="radio": Creates radio buttons for selecting one option from a group.
type="checkbox": Creates checkboxes for selecting multiple options.
type="submit": Submits the form data to the server.
type="button": A button for custom JavaScript actions, but doesn’t submit data by itself.
<textarea>: Provides a multi-line text input, useful for comments or descriptions.

<select> and <option>: Creates a dropdown menu. The <select> tag wraps multiple <option> tags, each representing a choice.

<label>: Defines labels for input elements, improving accessibility and user experience. It’s associated with an input using the for attribute, matching the input’s id.

<fieldset> and <legend>: Groups related inputs together and adds a title to the group (the <legend>), which is useful for organizing complex forms.

<button>: Similar to <input type="button"> but more flexible, allowing for nested elements like icons or text. It can be used with type="submit", type="reset", or type="button" for different behaviors.

Each of these tags contributes to a functional and accessible form, helping gather and validate user information effectively.
