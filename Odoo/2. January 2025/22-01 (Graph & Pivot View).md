#### Graph
- view example in purchase module
- measures
- arch: `graph`
	- only stored field
	- categorical fields
	- purpose of multiple fields
	- disable linking
	- `type="measure"`
		- specifies default
	- date type field:
		- `interval`: 
			- `day`, `week`, `month`, `quarter`, `year`
- attributes (can be change from ui):
	- type: default graph type
	- stacked: default is True 
		- affects _Bar_ & _Line_ Chart
	- order: `asc`, `desc`

#### Pivot
- [Docs](https://www.odoo.com/documentation/17.0/developer/reference/user_interface/view_architectures.html#pivot)
- expand row, cols
- flip axis
- arch: `pivot`
	- specify `type` in `field` to show in the view
	- `disable_linking`
	- multiple `measure` in pivot (unlike graph)
	- `display_quantity`
	- `default_order` 
- first col and row is main, others are sub


#### Aggregate in tree view
- specify in the `field`
- two types (on numerical)
	- sum
		- `sum="Some Help Text"`
	- average
		- `avg="Some Help text"`
- if specified both, it shows only the first one