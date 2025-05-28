| **Name**         | **Description**                                                               | **Type**           | **Required** | **Default** |
|------------------|-------------------------------------------------------------------------------|--------------------|--------------|-------------|
| **badge**        | Only applicable for multiple selection - shows number of item  selected       | string             | No           |             |
| **icon**         | Icon to show                                                                  | CoreIcon           | No           |             |
| **isChecked**    | State to indicate whether the menu chip has any selected menu items           | boolean            | No           | false       |
| **isOpen**       | State corresponding to menu open / close                                      | boolean            | No           | false       |
| **menuId**       | Id for the menu element that this chip controls                               | string             | yes          |             |
| **menuType**     | Indicate when menu chip has single select option, or multiple  select options | single \| multiple | No           | single      |
| **onClick**      | Callback function to be called when menu chip is clicked                      | () => void         | No           |             |
| **selectedText** | Only applicable for single selection menu chip. Shows item selected           | string             | No           |             |
