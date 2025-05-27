| Name       | Type            | Required | Default | Description                                         |
|------------|-----------------|----------|---------|-----------------------------------------------------|
| hasError   | boolean         | No       | false   | Indicate error                                      |
| id         | string          | No       |         | Unique id for the radio button.                     |
| isChecked  | boolean         | No       | false   | boolean to check if radio button is selected or not |
| isDisabled | boolean         | No       | false   | Disable the radio button                            |
| isQuiet    | boolean         | No       | false   | Disables UI interactivity                           |
| label      | string          | Yes      |         | Label to display for the radio button               |
| name       | string          | Yes      |         | Name attribute to group radio buttons together      |
| onChange   | () => void      | No       |         | Callback when the radio button's state changes      |
| value      | string\| number | Yes      |         | The value associated with the radio button          |