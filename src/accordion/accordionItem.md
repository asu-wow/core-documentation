| Name        | Type          | Required | Default | Description                                             |
|-------------|---------------|----------|---------|---------------------------------------------------------|
| children    | ReactNode     | No       |         | Content rendered inside the Accordion                   |
| isExpanded  | boolean       | No       | false   | Flag to indicate whether the accordion item is expanded |
| isLazyLoad  | boolean       | No       | false   | If content is to be lazy loaded                         |
| leadingIcon | CoreIconProps | No       |         | Display icon before the title                           |
| onPress     | (e) => void   | No       |         | Emits when the panel is pressed                         |
| title       | string        | No       |         | Title of the accordion                                  |