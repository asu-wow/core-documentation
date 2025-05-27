| Name         | Type               | Required | Default | Description                                                                   |
|--------------|--------------------|----------|---------|-------------------------------------------------------------------------------|
| badge        | string             | No       |         | Only applicable for multiple selection - shows number of item  selected       |
| icon         | CoreIcon           | No       |         | Icon to show                                                                  |
| isChecked    | boolean            | No       | false   | State to indicate whether the menu chip has any selected menu items           |
| isOpen       | boolean            | No       | false   | State corresponding to menu open / close                                      |
| menuId       | string             | yes      |         | Id for the menu element that this chip controls                               |
| menuType     | single \| multiple | No       | single  | Indicate when menu chip has single select option, or multiple  select options |
| onClick      | () => void         | No       |         | Callback function to be called when menu chip is clicked                      |
| selectedText | string             | No       |         | Only applicable for single selection menu chip. Shows item selected           |