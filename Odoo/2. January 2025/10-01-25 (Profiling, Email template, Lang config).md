- #### Profiling
	- for as low time as possible
	- open

- #### Email template:
	- model: `mail.template`
	- dynamic value
	- view template from templates in Technical menu
	- html code as email body
	- dynamic value:
		- `t-field`
	- conditional
		- `t-if` `t-else`
	- `send_mail` from backend
		- catch template with ref and call `send_mail` with object id

- Setup outgoint mailserver
	- [Tutorial](https://www.cybrosys.com/blog/how-to-configure-outgoing-and-incoming-mail-servers-in-odoo-17)

- lang config export and use
	- `.po` file