| **Name**                | **Description**                                    | **Type**                                                                          | **Required** | **Default** |
|-------------------------|----------------------------------------------------|-----------------------------------------------------------------------------------|--------------|-------------|
| **count**               |                                                    | number                                                                            | Yes          |             |
| **initialCurrentPage**  | Current page index                                 | number                                                                            | No           |             |
| **onNext**              | Callback when next page is clicked                 | () => void                                                                        | No           |             |
| **onPageNumberClick**   | Page number click handler function                 | (props: {pageNumber: number; shouldFocus: boolean; updatedUrl: string;}) => void; | Yes          |             |
| **onPrevious**          | Callback when previous is clicked                  | () => void                                                                        | No           |             |
| **pageSize**            | Total page size                                    | number                                                                            | Yes          |             |
| **paginationLabel**     | Accessibility label for pagination                 | string                                                                            | No           |             |
| **pathname**            | url pathname                                       | string                                                                            | Yes          |             |
| **queryPageNumberName** | Page number query string parameter name in the url | string                                                                            | Yes          |             |
| **searchParams**        | url search params                                  | string                                                                            | Yes          |             |
