# ebay-checkbox

## ebay-checkbox Usage

```marko
<ebay-checkbox/>
```

## ebay-checkbox Attributes

Name | Type | Stateful | Required | Description
--- | --- | --- | ---
`disabled` | Boolean | No | No |

Note: For this component, `class`/`style` are applied to the root tag, while all other HTML attributes are applied to the `input` tag.

## ebay-checkbox Events

Event | Data | Description
--- | --- | --
`checkbox-change` | `{ originalEvent, value, checked }` | selected value and checked status
`checkbox-focus` | `{ originalEvent, value }` |
