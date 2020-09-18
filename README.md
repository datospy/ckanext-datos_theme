# ckanext-datos_theme

CKAN extension for datos.org.py(ckanext-datos-theme)

## Installation: To install the plugin, enter your virtualenv and load the source (into the /src directory where you installed CKAN):
```
$ git clone https://github.com/alesservin/ckanext-datos_theme.git
cd ckanext-datos_theme
(pyenv)$ python setup.py develop
```
This will also register a plugin entry point, so you now should be able to add the following to your CKAN .ini file:

Add datos_theme to the .ini file.
```
ckan.plugins = <OTHER_PLUGINS> datos_theme
```
Apply these changes to the .ini file.
```
ckan.site_logo = /base/images/datos_abiertos_py_horizontal-logo.jpg
```