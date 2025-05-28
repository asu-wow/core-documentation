| **Name**       | **Description**                                     | **Type**        | **Required** | **Default** |
|----------------|-----------------------------------------------------|-----------------|--------------|-------------|
| **hasError**   | Indicate error                                      | boolean         | No           | false       |
| **id**         | Unique id for the radio button.                     | string          | No           |             |
| **isChecked**  | boolean to check if radio button is selected or not | boolean         | No           | false       |
| **isDisabled** | Disable the radio button                            | boolean         | No           | false       |
| **isQuiet**    | Disables UI interactivity                           | boolean         | No           | false       |
| **label**      | Label to display for the radio button               | string          | Yes          |             |
| **name**       | Name attribute to group radio buttons together      | string          | Yes          |             |
| **onChange**   | Callback when the radio button's state changes      | () => void      | No           |             |
| **value**      | The value associated with the radio button          | string\| number | Yes          |             |
