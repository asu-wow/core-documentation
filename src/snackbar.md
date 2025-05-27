| Name            | Type               | Required | Default | Description                                 |
|-----------------|--------------------|----------|---------|---------------------------------------------|
| actionOnNewLine | boolean            | No       |         | Place the action button on a new line       |
| actionText      | string             | No       |         | The label for an optional action button     |
| duration        | number             | No       | 3000    | Duration (in ms) before snackbar disappears |
| onAction        | () => void         | No       |         | Callback function                           |
| text            | string             | Yes      |         | The main text content displayed             |
| variant         | single \| multiple | No       | single  | Single line for shorter text                |