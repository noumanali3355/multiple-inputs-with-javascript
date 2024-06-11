## Dynamic Social Media Form

## Overview
This HTML and JavaScript code creates a dynamic form that allows users to add multiple input fields for social media platforms and their corresponding usernames or handles. The form data is stored in a JavaScript object for further processing.

## Features

- Add multiple input fields for social media platforms and usernames/handles
- Select social media platforms from a dropdown list
- Enter usernames or handles for each selected platform
- Remove individual input fields
- Stores form data in a JavaScript object

## Usage
- Open the HTML file in a web browser.
- Click the "Add" button to create a new input field.
- Select a social media platform from the dropdown list.
- Enter a username or handle for the selected platform.
- Repeat steps 2-4 to add more input fields.
- Remove individual input fields by clicking the "-" button.
- The form data is stored in the userInputs object in JavaScript.

## JavaScript Object Structure
The userInputs object stores the form data in the following format:

```bash
{
  "Facebook_1": "username1",
  "Instagram_2": "handle2",
  "Twitter_3": "username3",
  ...
}
```

Where the key is the social media platform name followed by an underscore and a unique ID, and the value is the corresponding username or handle.

## Note
This code is for demonstration purposes only and may require modifications for production use.