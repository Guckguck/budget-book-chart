## Adding Helm Charts to Budgetbook Repo
- helm create budget-book-chart
- helm install budget-book-chart ../budget-book-chart -n budget-book-chart --create-namespace

## Configuring the Helm Charts
- Remove everything within the template folder
- Add Chart.yaml and values.yaml to the root directory
- Create a folder for each Microservice (frontend, auth, exspense, statistics) within the template folder
- Within each Microservice create two files named deployment.yaml and service.yaml
- Fill these files with needed informations like variables and secrets and reference them
