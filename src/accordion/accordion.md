| Name              | Type                                 | Required | Default | Description                                                               |
|-------------------|--------------------------------------|----------|---------|---------------------------------------------------------------------------|
| children          | ReactNode                            | No       |         | Consumer can choose to render accordion via data object or use children   |
| collapseIcon      | CoreIconProps                        | No       | small   | Collapse icon for the accordion item                                      |
| expandIcon        | CoreIconProps                        | No       |         | Expanded icon for the accordion item                                      |
| isFlushed         | boolean                              | No       | false   | Configure all Accordion items to be flushed to the edge, default is false |
| isTitleAccent     | boolean                              | No       | false   | Configure title style for all Accordion Items                             |
| onSelectionChange | (e) => void                          | No       |         | Handler that is called when the selection of Accordion Item changes       |
| size              | large \| medium \| small             | No       | medium  | Determines the accordion title and spacing                                |
| titleElement      | 'h2' \| 'h3' \| 'h4' \| 'h5' \| 'h6' | No       | h2      | Element that will be used in the title of the Accordion Item              |