| **Name**                | **Description**                                    | **Type**                                                                          | **Required** | **Default** |
|-------------------------|----------------------------------------------------|-----------------------------------------------------------------------------------|--------------|-------------|
| **count**               |                                                    | number                                                                            | Yes          |             |
| **initialCurrentPage**  |                                                    | number                                                                            | No           |             |
| **onNext**              |                                                    | () => void                                                                        | No           |             |
| **onPageNumberClick**   | Page number click handler function                 | (props: {pageNumber: number; shouldFocus: boolean; updatedUrl: string;}) => void; | Yes          |             |
| **onPrevious**          |                                                    | () => void                                                                        | No           |             |
| **pageSize**            |                                                    | number                                                                            | Yes          |             |
| **paginationLabel**     |                                                    | string                                                                            | No           |             |
| **pathname**            | url pathname                                       | string                                                                            | Yes          |             |
| **queryPageNumberName** | Page number query string parameter name in the url | string                                                                            | Yes          |             |
| **searchParams**        | url search params                                  | string                                                                            | Yes          |             |
