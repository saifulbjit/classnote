- limitations of `sql_constraints`
	- not suitable for complex constraints
	- only use when first creating the model
- python constraints
	- api.constraints
- create, write -> super call
	- command list
- delegation inheritance
	- `has a` type relationship (classical inheritence: `is a` type)
	- inherits only the fields
	- not recommended for multi level
- onchange <-> depends (compute)
	- do not use `dot path` in `onchage` dependencies
- `related`, `depends` param in `fields.Char()`
- caching, prefetching