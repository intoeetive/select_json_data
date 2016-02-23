**Select from JSON data**

This fieldtype for ExpressionEngine 2.x allows to build custom select field with data based on JSON feed.

You can set field as single- or multiple-select. Options are searchable.

In the settings, you'll need to define JSON source URL, 'root' element (which contains the data you'll want to loop through), then elements to be used as field option value and option label.

On the front-end you'll use field as tag pair, with variables inside the pair being keys for element sub-items.

E.g. 

{json_select}{id} => {name} => {slug}<br />{/json_select}