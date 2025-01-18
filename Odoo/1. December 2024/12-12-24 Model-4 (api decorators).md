-> `api.onchange` decorator
- return warning
```python
	# Warning format
	return {
		"warning": {
			"title": "",
			"message": ""
		}
	}
```
- Dont use ORM methods in `onchange` function. will raise `UnexpectedBehaviorError`. (except `update`)

> - `default=False` in `fields.Char` ? _think about it_
> - `fields.Date.today(), fields.Datetime` static method

-> `api.constraint` decorator
- need to iterate over `self` 
- raise `ValidationError` if some conditions fails
- `self.search()` 
	- returns recordset
	- limit
	- order
- `self.search_count()`

-> `api.ondelete()`
- `at_uninstall=False`
- `UserError`

