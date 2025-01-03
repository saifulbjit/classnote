#### Demo Data:
- [Define Module Data](https://www.odoo.com/documentation/17.0/developer/tutorials/define_module_data.html)
- mention in menifest
- Demo data loaded only when the app is installed

#### Kanban View
- field definition
- `templates`
	- `t` & `t-name` 
		- `kanban-box`:
			- clasess: 
				- global click
		- `kanban-menu`
			- can use bootstrap classes
				- `row`, `col-6`
			- if `type="object"` that means it has onclick event
			- context updating in action
			- > `base.group_user` for internal users
		- `kanban-tooltip`
			- `t-esc`
- header
	- button
		- display
			- always
- root attribute
	- `on_create` an action
	- `default_order`
	- `default_group_by`
	- `archivable` : bool
	- `record_draggable`
	- `bannre_route`
		- controller usage
	- `progressbar`

---
_Ref_
1. [Kanban Docs](https://www.odoo.com/documentation/17.0/developer/reference/user_interface/view_architectures.html#kanban)