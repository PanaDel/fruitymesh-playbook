# fruitymesh-playbook
This Repo has the configuraiton file playbook.yml for the Fruitymesh Open-Source documentation built by Antora

Execute following command to build this UI with search activated:
````
DOCSEARCH_ENABLED=true DOCSEARCH_ENGINE=lunr antora playbook.yml
````
The playbook.yml uses a custom UI-BUNDLE (ui: bundle: url:) to use for the generated Documentation.
This UI-BUNDLE is created from a seperate repository *** ADD LINK HERE ***

For more information on Antora follow the [official documentation](https://docs.antora.org/antora/2.0/)
