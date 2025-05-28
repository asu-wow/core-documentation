| **Name**        | **Description**                                         | **Type**      | **Required** | **Default** |
|-----------------|---------------------------------------------------------|---------------|--------------|-------------|
| **children**    | Content rendered inside the Accordion                   | ReactNode     | No           |             |
| **isExpanded**  | Flag to indicate whether the accordion item is expanded | boolean       | No           | false       |
| **isLazyLoad**  | If content is to be lazy loaded                         | boolean       | No           | false       |
| **leadingIcon** | Display icon before the title                           | CoreIconProps | No           |             |
| **onPress**     | Emits when the panel is pressed                         | (e) => void   | No           |             |
| **title**       | Title of the accordion                                  | string        | No           |             |
