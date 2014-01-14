workspace-mechanic-preferences
==============================

My take on Eclipse preferences using Workspace Mechanic plugin

* all_tasks.json - for those who prefer to use url in configuration
* close_old_open_editors.epf - keep maximum of 15 editors. There is really no need for more.
* do_not_activate_plugins_on_startup.epf - This improves startup time and does not load plugins and modules you might not even use. These additions will be loaded anyway when you first open a related editor or view.
* guess_method_arguments.epf - Instructs Eclipse to well, guess method arguments.
* replace_on_autocompletion.epf - I like it. You can always hold down ctrl to insert but I usually need to replace.
* save_actions.epf - no code should be saved without formatting. And if you have portions of code you don't want to format then those should be annotated with //formatting@off See formatting options
* smart_semicolon_braces.epf - I have no idea why these are not enabled by default
* spaces_for_tabs_in_xml.epf - I just don't like tabs
* type_filters.epf - I don't need everything Java has to offer so I filter out some things
* use_utf8_encoding.epf - Use UTF-8 for workspace default, properties, jsp, css, html, xml
