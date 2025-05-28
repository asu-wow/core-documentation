| **Name**              | **Description**                                                           | **Type**                             | **Required** | **Default** |
|-----------------------|---------------------------------------------------------------------------|--------------------------------------|--------------|-------------|
| **children**          | Consumer can choose to render accordion via data object or use children   | ReactNode                            | No           |             |
| **collapseIcon**      | Collapse icon for the accordion item                                      | CoreIconProps                        | No           | small       |
| **expandIcon**        | Expanded icon for the accordion item                                      | CoreIconProps                        | No           |             |
| **isFlushed**         | Configure all Accordion items to be flushed to the edge, default is false | boolean                              | No           | false       |
| **isTitleAccent**     | Configure title style for all Accordion Items                             | boolean                              | No           | false       |
| **onSelectionChange** | Handler that is called when the selection of Accordion Item changes       | (e) => void                          | No           |             |
| **size**              | Determines the accordion title and spacing                                | large \| medium \| small             | No           | medium      |
| **titleElement**      | Element that will be used in the title of the Accordion Item              | 'h2' \| 'h3' \| 'h4' \| 'h5' \| 'h6' | No           | h2          |
