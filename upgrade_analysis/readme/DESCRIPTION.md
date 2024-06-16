This module provides the tool to generate the database analysis files
that indicate how the Odoo data model and module data have changed
between two versions of Odoo. Database analysis files for the core
modules are included in the OpenUpgrade distribution so as a migration
script developer you will not usually need to use this tool yourself. If
you do need to run your analysis of a custom set of modules, please
refer to the documentation here:
<https://doc.therp.nl/openupgrade/analysis.html>

This module is just a tool, a continuation of the old
openupgrade_records in OpenUpgrade in previous versions. It's not
recommended to have this module in a production database.