| Name                | Type                                | Required | Default | Description                     |
|---------------------|-------------------------------------|----------|---------|---------------------------------|
| description         | string                              | No       |         | Body copy of alert              |
| ~~hasExternalLink~~ | boolean                             | No       |         | **_deprecated_**                |
| link                | CoreLinkProps                       | No       |         |                                 |
| ~~linkLabel~~       | string                              | No       |         | **_deprecated_**                | 
| placement           | inset \| page \| compact            | No       | inset   | Indicate the placement of alert |
| title               | string                              | Yes      |         | Title of alert                  |
| variant             | info \| success \| warning \| error | No       | info    | Alert type                      |