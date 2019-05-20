# fruitymesh-playbook
This Repo has the configuraiton file playbook.yml for the Fruitymesh Open-Source documentation built by Antora

Execute following command to build this UI with search activated:
````
EARCH_ENABLED=true DOCSEARCH_ENGINE=lunr antora playbook.yml
````
The playbook.yml uses a custom UI-BUNDLE (ui: bundle: url:) to use for the generated Documentation
