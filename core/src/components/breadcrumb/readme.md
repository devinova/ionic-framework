# ion-breadcrumb

Breadcrumb


<!-- Auto Generated Below -->


## Properties

| Property    | Attribute   | Description                                                                                                                                                                                                                                                                               | Type                   | Default     |
| ----------- | ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------- | ----------- |
| `active`    | `active`    | If `true`, the breadcrumb will take on a different look to show that it is the currently active breadcrumb. Defaults to `true` for the last breadcrumb if it is not set on any.                                                                                                           | `boolean`              | `false`     |
| `color`     | `color`     | The color to use from your application's color palette. Default options are: `"primary"`, `"secondary"`, `"tertiary"`, `"success"`, `"warning"`, `"danger"`, `"light"`, `"medium"`, and `"dark"`. For more information on colors, see [theming](/docs/theming/basics).                    | `string \| undefined`  | `undefined` |
| `disabled`  | `disabled`  | If `true`, the user cannot interact with the breadcrumb.                                                                                                                                                                                                                                  | `boolean`              | `false`     |
| `download`  | `download`  | This attribute instructs browsers to download a URL instead of navigating to it, so the user will be prompted to save it as a local file. If the attribute has a value, it is used as the pre-filled file name in the Save prompt (the user can still change the file name if they want). | `string \| undefined`  | `undefined` |
| `href`      | `href`      | Contains a URL or a URL fragment that the hyperlink points to. If this property is set, an anchor tag will be rendered.                                                                                                                                                                   | `string \| undefined`  | `undefined` |
| `mode`      | `mode`      | The mode determines which platform styles to use.                                                                                                                                                                                                                                         | `"ios" \| "md"`        | `undefined` |
| `rel`       | `rel`       | Specifies the relationship of the target object to the link object. The value is a space-separated list of [link types](https://developer.mozilla.org/en-US/docs/Web/HTML/Link_types).                                                                                                    | `string \| undefined`  | `undefined` |
| `separator` | `separator` | If true, show a separator between this breadcrumb and the next. Defaults to `true` for all breadcrumbs except the last.                                                                                                                                                                   | `boolean \| undefined` | `undefined` |
| `target`    | `target`    | Specifies where to display the linked URL. Only applies when an `href` is provided. Special keywords: `"_blank"`, `"_self"`, `"_parent"`, `"_top"`.                                                                                                                                       | `string \| undefined`  | `undefined` |


## Shadow Parts

| Part          | Description                                                          |
| ------------- | -------------------------------------------------------------------- |
| `"native"`    | The native HTML anchor or div element that wraps all child elements. |
| `"separator"` | The separator element between each breadcrumb.                       |


## Dependencies

### Depends on

- ion-icon

### Graph
```mermaid
graph TD;
  ion-breadcrumb --> ion-icon
  style ion-breadcrumb fill:#f9f,stroke:#333,stroke-width:4px
```

----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*