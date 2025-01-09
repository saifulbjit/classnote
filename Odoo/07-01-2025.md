#### Page No in qweb
- `span` with class `page` in layout
- `span` with class `topage` (for page count)

#### Report button:
- `type` = `object`
- `name` to a function
- use `ref` to the xml id of the action and call `report_action(self)`
	- `data` context variable

#### Timestamp:
- `context_timestamp(datetime.datetime.now())`
	- we can use datetime functions in it

#### Action from Kanban View
- return action from a python func
- binding a view in the `action['views']`
- binding direct action (using action defined in xml record)
	- `type`=`action`
	- `name="%(xml id)"`
- python file:
	- `type`=`object`
	- `name=<python function>`

#### Misc.
- inside kanban view:
	- `t-esc` to `object.field.raw_value` or `value`
- `emp_salary_certificate_report_wizard`
	- `report_action(self, data=custom_data)`
	- `ir.config_parameter`
		- `get_param('web.base.url')`
	- using the data in report xml