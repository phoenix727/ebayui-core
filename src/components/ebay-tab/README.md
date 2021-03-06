# ebay-tab

## ebay-tab Usage

```marko
<ebay-tab>
    <ebay-tab-heading>Tab 1</ebay-tab-heading>
    <ebay-tab-heading>Tab 2</ebay-tab-heading>
    <ebay-tab-heading>Tab 3</ebay-tab-heading>
    <ebay-tab-panel>Panel 1</ebay-tab-panel>
    <ebay-tab-panel>Panel 2</ebay-tab-panel>
    <ebay-tab-panel>Panel 3</ebay-tab-panel>
</ebay-tab>
```

## ebay-tab Attributes

Name | Type | Stateful | Required | Description
--- | --- | --- | --- | ---
`index` | String | Yes | No | 0-based index of selected tab heading and panel
`fake` | Boolean | No | No | Whether to use link behavior for tab headings
`activation` | String | Yes | No | whether to use automatic or manual activation when navigating by keyboard, "auto" (default) / "manual"

> *Note:* When using fake tabs there is no `preventDefault` applied, and therefore the link in the tab heading will work as a normal and navigate to the URL provided in the `href`.

## ebay-tab Events

Event | Data | Description
--- | --- | ---
`tab-select` | `{ index }` |

## ebay-tab-heading Tag

### ebay-tab-heading Usage

```marko
<ebay-tab-heading>Tab 1</ebay-tab-heading>
```

## ebay-tab-heading Attributes

Name | Type | Stateful | Required | Description
--- | --- | --- | ---
`href` | String | No | No | For use with `fake` tab component

## ebay-tab-panel Tag

### ebay-tab-panel Usage

```marko
<ebay-tab-panel>Panel 1</ebay-tab-panel>
```
