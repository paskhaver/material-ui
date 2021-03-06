---
filename: /packages/material-ui/src/internal/SwitchBase.js
---

<!--- This documentation is automatically generated, do not try to edit it. -->

# SwitchBase



## Props

| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| <span class="prop-name">checked</span> | <span class="prop-type">union:&nbsp;bool&nbsp;&#124;<br>&nbsp;string<br> |  | If `true`, the component is checked. |
| <span class="prop-name required">checkedIcon *</span> | <span class="prop-type">node |  | The icon to display when the component is checked. |
| <span class="prop-name">classes</span> | <span class="prop-type">object |  | Useful to extend the style applied to components. |
| <span class="prop-name">disabled</span> | <span class="prop-type">bool |  | If `true`, the switch will be disabled. |
| <span class="prop-name">disableRipple</span> | <span class="prop-type">bool |  | If `true`, the ripple effect will be disabled. |
| <span class="prop-name required">icon *</span> | <span class="prop-type">node |  | The icon to display when the component is unchecked. |
| <span class="prop-name">id</span> | <span class="prop-type">string |  | The id of the `input` element. |
| <span class="prop-name">indeterminate</span> | <span class="prop-type">bool |  | If `true`, the component appears indeterminate. |
| <span class="prop-name">indeterminateIcon</span> | <span class="prop-type">node |  | The icon to display when the component is indeterminate. |
| <span class="prop-name">inputProps</span> | <span class="prop-type">object |  | Properties applied to the `input` element. |
| <span class="prop-name">inputRef</span> | <span class="prop-type">func |  | Use that property to pass a ref callback to the native input component. |
| <span class="prop-name">name</span> | <span class="prop-type">string |  |  |
| <span class="prop-name">onChange</span> | <span class="prop-type">func |  | Callback fired when the state is changed.<br><br>**Signature:**<br>`function(event: object, checked: boolean) => void`<br>*event:* The event source of the callback. You can pull out the new value by accessing `event.target.checked`.<br>*checked:* The `checked` value of the switch |
| <span class="prop-name">type</span> | <span class="prop-type">string | <span class="prop-default">'checkbox'</span> | The input component property `type`. |
| <span class="prop-name">value</span> | <span class="prop-type">string |  | The value of the component. |

Any other properties supplied will be [spread to the root element](/guides/api#spread).

## CSS API

You can override all the class names injected by Material-UI thanks to the `classes` property.
This property accepts the following keys:
- `root`
- `checked`
- `disabled`
- `input`

Have a look at [overriding with classes](/customization/overrides#overriding-with-classes) section
and the [implementation of the component](https://github.com/mui-org/material-ui/tree/v1-beta/packages/material-ui/src/internal/SwitchBase.js)
for more detail.

If using the `overrides` key of the theme as documented
[here](/customization/themes#customizing-all-instances-of-a-component-type),
you need to use the following style sheet name: `MuiSwitchBase`.

## Inheritance

The properties of the [IconButton](/api/icon-button) component are also available.

