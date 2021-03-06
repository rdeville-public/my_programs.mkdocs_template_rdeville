<!-- BEGIN MKDOCS TEMPLATE -->
<!--
WARNING, DO NOT UPDATE CONTENT BETWEEN MKDOCS TEMPLATE TAG !
Modified content will be overwritten when updating
-->

# Release Notes

<!-- END MKDOCS TEMPLATE -->

## π v1.0

### π v1.0.5 <small>(08/12/2021)</small>

  * β¬π Upgrade documentation content to use v1.0.5-RD.4 from
    mkdocs_template_rdeville

### π v1.0.5 <small>(08/12/2021)</small>

  * β¬π Upgrade documentation content from v1.0.4-RD.2 template

### π v1.0.4 <small>(07/12/2021)</small>

  * π¨ Fix pylint and shellcheck warning
  * β¬π§ Upgrade dependencies and config
  * β¬ Update template dependencies and configuration
  * ο§  Fix link from rdeville.private to public

### π v1.0.3 <small>(13/05/2021)</small>

  * π Update documentation content.
  * π§ Update extra content through yaml `_dataΒ·` files
    * Add new content
    * Add documentation in template files
  * β¨ Improve `plugins.py` behaviour
    * Convert `.format()` string into `f""` string
    * Fix configuration management
  * β¬π Upgrade pinned python dependencies

### π v1.0.2 <small>(29/04/2021)</small>

  * ππ Update copyright in license content
  * β¨ Improve handling of copyright in plugins.py script
  * π₯ Remove useless file from tracked tree

### π v1.0.1 <small>(29/04/2021)</small>

  * ππ± Fix wrong assets path in `docs/personal_template/create.md`
  * π Update `plugins.py` to latest release

### π v1.0.0 <small>(29/04/2021)</small>

First initial release of MkDocs Template

  * β¨ Add bunch of features:
    * `setup.sh` script to automatically install template,
    * `template` folder holding basic template files, script
      `docs/_data/plugins.py` to dynamically setup `mkdocs.yml` configuration
      and schema and template for files read by the script
  * π§ Add bunch of configuration files:
    * Syntax and workflow configuration files such as `.editorconfig`,
      `.yamllint`, `pyproject.toml`
  * π· Add CI which test the scripts (bash and python), build the
    documentation and deploy it
  * ππ± Add the documentation describing the usage of the template with needed
    assets.
  * π Add licenses, MIT and Beer-Ware.

