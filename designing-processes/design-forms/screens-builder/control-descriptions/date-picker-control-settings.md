---
description: >-
  Add a Date Picker control that allows the form user to select dates from a
  ProcessMaker Screen through an interactive calendar.
---

# Date Picker Control Settings

## Control Description <a id="control-description"></a>

The Date Picker control allows the form user to click the control and select a date from a calendar pop-up. After the user selects a date from the control, the calendar hides and the control shows the selected date using the `mm/dd/yyyy` text format.

{% hint style="info" %}
This control is not available for [Display](../types-for-screens.md#display)-type ProcessMaker Screens. See [Screen Types](../types-for-screens.md).
{% endhint %}

## Add the Control to a ProcessMaker Screen <a id="add-the-control-to-a-processmaker-screen"></a>

{% hint style="info" %}
Your user account or group membership must have the following permissions to add a control to a ProcessMaker Screen:

* Screens: View Screens
* Screens: Edit Screens

See the ProcessMaker [Screens](../../../../processmaker-administration/permission-descriptions-for-users-and-groups.md#screens) permissions or ask your ProcessMaker Administrator for assistance.
{% endhint %}

Follow these steps to add this control to the ProcessMaker Screen:

1. [Create](../../manage-forms/create-a-new-form.md) or [open](../../manage-forms/view-all-forms.md) the ProcessMaker Screen. The ProcessMaker Screen is in [Editor mode](../screens-builder-modes.md#editor-mode).
2. View the ProcessMaker Screen page to which to add the control.
3. Go to the **Controls** panel on the left side of the ProcessMaker Screen.
4. Drag the **Date Picker** icon![](../../../../.gitbook/assets/date-picker-control-screens-builder-processes.png)from the **Controls** panel anywhere within the ProcessMaker Screen canvas represented by the dotted-lined box. Existing controls on the ProcessMaker Screen canvas adjust positioning based on where you drag the control.
5. Place into the ProcessMaker Screen canvas where you want the control to display on the page.

   ![](../../../../.gitbook/assets/date-picker-control-placed-screens-builder-processes.png)

6. Configure the Date Picker control. See [Inspector Settings](date-picker-control-settings.md#inspector-settings).

Below is a Date control in Preview mode.

![Date control in Preview mode](../../../../.gitbook/assets/date-control-preview-screens-builder-processes.png)

## Delete the Control from a ProcessMaker Screen

{% hint style="warning" %}
Deleting a control also deletes configuration for that control. If you add another control, it will have default settings.
{% endhint %}

Click the **Delete** icon![](../../../../.gitbook/assets/delete-screen-control-screens-builder-processes.png)for the control to delete it.

## Inspector Settings <a id="inspector-settings"></a>

{% hint style="info" %}
### Don't Know What the Inspector Panel Is?

See [View the Inspector Panel](../view-the-inspector-pane.md).

### Permissions Required to View Control Settings

Your user account or group membership must have the following permissions to edit a ProcessMaker Screen control:

* Screens: View Screens
* Screens: Edit Screens

See the ProcessMaker [Screens](../../../../processmaker-administration/permission-descriptions-for-users-and-groups.md#screens) permissions or ask your ProcessMaker Administrator for assistance.
{% endhint %}

Below are Inspector settings for the Date Picker control:

* **Field Name:** Specify the unique internal data name of the control that only the Process Owner views at design time. This is a required setting. Use the **Field Name** value for this control to reference it in [**Show If** setting expressions](expression-syntax-components-for-show-if-control-settings.md).
* **Field Label:** Specify the field label text that displays. **New Date Picker** is the default value.
* **Placeholder:** Specify the placeholder text that displays in the field when no value has been provided. This setting has no default value.
* **Background Color:** Select to specify the background color of the Date Picker control. Selecting a background color also selects the **Background Color** checkbox.
* **Text Color:** Select to specify the text color that displays in the control. Selecting a text color also selects the **Text Color** checkbox.
* **Show If:** Specify an expression that dictates the condition\(s\) under which the Date Picker control displays. See [Expression Syntax Components for "Show If" Control Settings](expression-syntax-components-for-show-if-control-settings.md#expression-syntax-components-for-show-if-control-settings). If this setting does not have an expression, then this control displays by default.

## Related Topics <a id="related-topics"></a>

{% page-ref page="../types-for-screens.md" %}

{% page-ref page="../view-the-inspector-pane.md" %}

{% page-ref page="./" %}

{% page-ref page="text-control-settings.md" %}

{% page-ref page="line-input-control-settings.md" %}

{% page-ref page="select-control-settings.md" %}

{% page-ref page="radio-group-control-settings.md" %}

{% page-ref page="checkbox-control-settings.md" %}

{% page-ref page="textarea-control-settings.md" %}

{% page-ref page="submit-button-control-settings.md" %}

{% page-ref page="page-navigation-button-control-settings.md" %}

{% page-ref page="multi-column-button-control-settings.md" %}

{% page-ref page="record-list-control-settings.md" %}

{% page-ref page="image-control-settings.md" %}

{% page-ref page="file-upload-control-settings.md" %}

{% page-ref page="file-download-control-settings.md" %}

{% page-ref page="expression-syntax-components-for-show-if-control-settings.md" %}
