| Name            | Type               | Required | Default | Description                                 |
|-----------------|--------------------|----------|---------|---------------------------------------------|
| actionOnNewLine | boolean            | no       |         | Place the action button on a new line       |
| actionText      | string             | no       |         | The label for an optional action button     |
| duration        | number             | no       | 3000    | Duration (in ms) before snackbar disappears |
| onAction        | () => void         | no       |         | Callback function                           |
| text            | string             | yes      |         | The main text content displayed             |
| variant         | single \| multiple | no       | single  | Single line for shorter text                |