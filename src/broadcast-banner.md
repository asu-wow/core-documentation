| Name        | Type           | Required | Default | Description |
|-------------|----------------|----------|---------|-------------|
| description | string         | no       |         |             |
| hasDismiss  | boolean        | no       |         |             |
| hasTag      | boolean        | no       | inset   |             |
| image       | CoreImageProps | yes      |         |             |
| Link        | CoreLinkProps  | no       |         |             |
| onDismiss   | (e) => ()      | no       |         |             |
| onLinkClick | (e) => ()      | no       |         |             |
| title       | string         | yes      |         |             |