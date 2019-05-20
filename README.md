# fruitymesh-playbook
This Repo holds configuration file playbook.yml for the [Fruitymesh ](https://github.com/PanaDel/fruitymesh) documentation built by Antora.

Three Repositories are needed for this to work:
1. [this repository](https://github.com/PanaDel/fruitymesh-playbook)
2. [the UI-repository]( *** ADD LINK HERE *** )
3. [the Fruitymesch repository](https://github.com/PanaDel/fruitymesh) 

Antora(playbook.yml file) uses the ui-bundle and the software documentation Asciidoc files to build a .html [documentation site]( *** ADD LINK HERE *** )

Execute following command to build documentation with search activated:
````
DOCSEARCH_ENABLED=true DOCSEARCH_ENGINE=lunr antora playbook.yml
````

The playbook.yml uses a custom UI-BUNDLE (ui: bundle: url:) for the generated Documentation.
This UI-BUNDLE is created from a seperate [UI repository] ( *** ADD LINK HERE *** )
This Repository can be edited to change the UI look.
*** **Node Version 8 must be used for gulp commands to work inside the UI-repo**  *** ( include this information in the UI-REPO when it is done)

Follow the [official Antora documentation](https://docs.antora.org/antora-ui-default/) for further information on how to customise the UI.

Use: ````gulp bundle```` to create a ui-bundle.zip from the UI Repository and include it in your CI-Jobs so your playbook.yml can always use the latest version of the UI.

For more information on Antora follow the [official Antora documentation](https://docs.antora.org/antora/2.0/)
