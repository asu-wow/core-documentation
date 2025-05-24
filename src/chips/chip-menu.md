| Name         | Type               | Required | Default | Description                                                                   |
|--------------|--------------------|----------|---------|-------------------------------------------------------------------------------|
| badge        | string             | no       |         | Only applicable for multiple selection - shows number of item  selected       |
| icon         | CoreIcon           | no       |         | Icon to show                                                                  |
| isChecked    | boolean            | no       | false   | State to indicate whether the menu chip has any selected menu items           |
| isOpen       | boolean            | no       | false   | State corresponding to menu open / close                                      |
| menuId       | string             | yes      |         | Id for the menu element that this chip controls                               |
| menuType     | single \| multiple | no       | single  | Indicate when menu chip has single select option, or multiple  select options |
| onClick      | () => void         | no       |         | Callback function to be called when menu chip is clicked                      |
| selectedText | string             | no       |         | Only applicable for single selection menu chip. Shows item selected           |