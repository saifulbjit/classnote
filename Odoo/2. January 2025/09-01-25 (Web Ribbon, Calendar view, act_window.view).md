- `<widget>`: 
	- `web_ribbon`
- calender view
	- `date_start`: required
	- `quick_create`
		- `event_open_popup`
	- `mode`
	- `color="state"`
		- for color segmentation
	- `date_stop`
	- `date_delay`
	- disable drag to increase length:
		- don't specify date_stop, date_delay

> [!tip]
> `hide_time="1"` to show the date only for datetime field

- `ir.actions.act_window.view`
	- set `sequence` to specify the priority of the view in ui
- override action
	- use same id
- `form_view_id` attribute
	- `%(<xml id>)d`
- `avatar_field`
- 