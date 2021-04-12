# React State Management: Complex Forms
## Instructions

Build the RSVPForm component in RSVPForm.jsx to be a form with these fields in this order:

1. "Name" input field.
1. Dropdown with the following age ranges: Prefer not to say, 0-19, 20-39, 40-59, 60+
1. "New Member" checkbox, set to unchecked by default.
1. "Comment" input field.
1. Submit button.

Upon submission, log each value together, in a single statement, to the console and clear the fields in the form.

## Example
For example, imagine the following is input into the form:

1. Name: John
1. Age: 60+
1. New Member: checked
1. Comment: left empty

The following should be what is logged to the console.

` "John", "60+", true, "" `

    Note: 
    Remember that you can log multiple items by passing multiple arguments into a console.log() statement, such as console.log("John", "60+").