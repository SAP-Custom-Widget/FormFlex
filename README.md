<img src="https://github.com/SAP-Custom-Widget/FormFlex/blob/main/icon.png?raw=true" width="100">

## SAP/SAC Custom Widget: FormFlex


![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Monthly active users](https://img.shields.io/jsdelivr/gh/hm/SAP-Custom-Widget/FormFlex?label=active%20users)
![GitHub Issues](https://img.shields.io/github/issues/SAP-Custom-Widget/FormFlex)
![GitHub followers](https://img.shields.io/github/followers/SAP-Custom-Widget)

A dynamic and flexible form builder custom widget for SAP Analytics Cloud (SAC).

[⬇️ Click Here to Download : `FormFlex.json`](https://sap-custom-widget.rohitchouhan.com/?dl=FormFlex)

> **📖 Developer Guide**: [Click here to read the Developer Guide on SAP Community](https://community.sap.com/t5/technology-blog-posts-by-members/introducing-formflex-the-ultimate-dynamic-form-builder-for-sap-analytics/ba-p/14333443) to learn how to use.
> 
> **📖 Youtube Video Guide Below**
> 
> [![Watch the video](https://img.youtube.com/vi/kSbA5hlTRjc/mqdefault.jpg)](https://www.youtube.com/watch?v=kSbA5hlTRjc)

### Installation
- Download the `FormFlex.json` from GitHub or above link.
- Go to your SAC Portal, then Stories → Custom Widget tab.
- Click on the + icon and select the downloaded file.
- Done! You can now use it in your app.

### Methods
- **setFormConfig**: Dynamically sets the form fields configuration
  - Param: `configJson` (Selection[]) - JSON array of field configurations
- **getFormValue**: Gets the current value of a specific form field
  - Param: `fieldId` (string) - The ID of the field
  - Returns: `string`
- **setFormValue**: Sets the value of a specific form field
  - Param: `fieldId` (string) - The ID of the field
  - Param: `value` (string) - The value to set
- **getAllValues**: Returns a JSON string containing all form values
  - Returns: `Selection`
- **isButtonClicked**: Checks if a specific submit button was the last one clicked.
  - Param: `buttonId` (string) - The ID of the button to check
  - Returns: `boolean`

### Events
- **onSubmit**: Event triggered when user click any submit button.

### Contributors
<table>
  <tr>
    <td><img src="https://github.com/rohit-chouhan.png" width="60" alt="Rohit Chouhan" /></td>
    <td>
      <sub>Developed by</sub><br/>
      <strong><a href="https://rohitchouhan.com/" target="_blank">Rohit Chouhan</a></strong>
    </td>
  </tr>
</table>

🌸💖 If you’d like to show some love, you can send a small donation here: 👉 [rohitchouhan.com/donate](rohitchouhan.com/donate) ✨

> 🌟 You can explore more ultimate custom widgets right here ✨
👉 [sap-custom-widget.rohitchouhan.com](https://sap-custom-widget.rohitchouhan.com) 💡

### Report bugs or issues
You are welcome to open a _[ticket](https://github.com/SAP-Custom-Widget/FormFlex/issues)_ on GitHub if any problems arise. New ideas are always welcome.

> Copyright © 2026 | Developed by **[Rohit Chouhan](https://rohitchouhan.com)**
