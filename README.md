## Overview

Burst is an experimental and the first tool to help convert your Bubble applications into code, making it easier to migrate to a code-based environment.

### Progress so far

- **Elements converted**
    - [x]  Groups
    - [x]  Texts
    - [x]  Buttons
    - [x]  Multiline Input
    - [x]  Input
    - [x]  Images
- **Current converter:** This is the first release for the public converter with support for all elements except Images
- **Next components**
    - [ ]  Checkbox
    - [ ]  Dropdown
    - [ ]  Repeating Groups
    - [ ]  Icon
    - [ ]  Link

### Known Issues

- **Ordering discrepancies:** Sometimes, the Bubble JSON doesn't reflect the visual arrangement in the editor so the generated code may be wrongly ordered.
- **Naming conventions:** You have to  properly label or rename all your elements for smoother code conversion.
- **Style limitations:** There’s currently no support for Bubble's style libraries or components.
- **Color definitions:** Define colors explicitly (e.g., use `#ffffff` instead of "Primary color").
- **Font consistency:** All converted code currently uses a single font so for now, your application font won’t be reflected in the conversion

### How To Use

- Go to the settings page of your Bubble application, under the General tab you’ll find the option to export your application. This will download a file on your system.
- Open and copy the content of the file then paste into the converter.
- You’ll see a list of pages with supported elements that have been identified from your app in a dropdown. Choose the one that you will like to convert.
- Run the conversion and view the converted code in a sandbox.

### Feedback

If you would like to give feedback about a conversion, you can:

- Submit an issue with details of your application’s JSON, the page you tried to convert and the sandbox link.
- Send me an [email](mailto:tammilore@gmail.com)
- Record a [Jam](https://jam.dev/) or a Loom video

### Things To Note

- Use sample applications that have simple pages including only the elements currently supported by the converter.
- Conversions that encounter issues may be logged sometimes to help identify and fix problems.
- Only the Bubble JSON shared by you is accessed, it does not have unlimited access to your live application.
- Burst is still in its early stages, so expect some imperfections.
