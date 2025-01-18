### Chatter Implementation
- `mail` dependency in manifest
- `tracking=True` in field
- `_inherit=['mail.thread']`
- Add this snippet as the last child component inside form
```xml
<div class="oe_chatter">  
    <field name="message_follower_ids" />  
    <field name="message_ids" />  
</div>
```

#### Add Activity
- `mail_activity_mixin` in `_inherit` list
- add `<field name="activity_ids" />` inside `oe_chatter` div

### Python Expression
- [Docs](https://www.odoo.com/documentation/17.0/developer/reference/user_interface/view_architectures.html#python-expression)
- parent

### Views & Widgets
- Form view
	- nested tree view for one2many field
- statusbar
- radio

### Action Button:
- button box
- stat button:
	- `oe_stat_button`
	- `statinfo` widget in a field with name to a computed field
- > `sudo()` search