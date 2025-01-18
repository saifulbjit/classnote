#### Authentication:
- None
- Public: 
	- website = True
- User
#### Type:
- html
- json

#### Render Qweb
- request.env
	- using `sudo()`
- request.render
- locate in server if required controller is similar to server provided ones
	- login api (`web/login`):
- request.session.authenticate

#### Inspecting `request.env`
- custom login
	- cors
	- methods
	- generate jwt
- use jwt:
	- jwt.decode(algorithms)
---
web - internal user
my - customer portal

---
vendor: customer rank

---
Topics Covered until now:
- ORM API
- defnine module data
- qweb report
- performance: profiling (to read)
- Web controllers
- view record, view architechture (partial)
- CLI
- Coding Guidelines (follow conventions closely)
- 