# fruitymesh-playbook
This Repo has the configuraiton file playbook.yml for the [Fruitymesh ](https://github.com/PanaDel/fruitymesh) documentation built by Antora

Execute following command to build documentation with search activated:
````
DOCSEARCH_ENABLED=true DOCSEARCH_ENGINE=lunr antora playbook.yml
````

The playbook.yml uses a custom UI-BUNDLE (ui: bundle: url:) for the generated Documentation.
This UI-BUNDLE is created from a seperate [UI repository] (*** ADD LINK HERE ***)

For more information on Antora follow the [official Antora documentation](https://docs.antora.org/antora/2.0/)
