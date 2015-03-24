=== WPDataDisplay ===
Contributors: alantygel
Tags: data
Requires at least: 3.8.1
Tested up to: 3.8.1
Stable tag: trunk
License: GPL2

This plugin creates a custom post type that displays data of several database tables based on a unique ID.

== Description ==
This plugins is used to display custom data using custom post types. It allows users to upload databases and generate posts to display this data. Each row of the database generates one post following the specifications of a template that states where each field appears.

How to use:

1) Create a table in your database with the prefix wp_datadisplay. This table needs one column called ID.
2) In the plugin setting, create the datadisplay template.
3) Click on generate posts.
