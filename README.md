# jqtree-meet-checkbox

This example enable checkboxes in the excellent <a href="https://mbraak.github.io/jqTree/">jqTree</a> plugin.

## How it works
The example uses `onCreateLi` option to prepend checkbox to each node. 
Checkbox is added only when `can_check` property of the node is `true`.

Initial check state is set using `is_checked` property. 
Every time the checkbox's state is toggled, the related node's `is_checked` property also gets updated accordingly.

## License
MIT License
