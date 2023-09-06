# Local Setup
- Clone the project
- Run `setup.sh`

# Local Development Run
For Backend
- `local_run.sh` It will start the flask app in `development`. Suited for local development

For Frontend
# client

## Project setup
`npm install`

### Compiles and hot-reloads for development
`npm run serve`

### Compiles and minifies for production
`npm run build`

### Lints and fixes files
`npm run lint`



# Folder Structure
-`Backend`
    - `db_directory` has the sqlite DB. It can be anywhere on the machine. Adjust the path in ``application/config.py`. Repo ships with one required for testing.
    - `application` is where our application code is
    - `.gitignore` - ignore file
    - `setup.sh` set up the virtualenv inside a local `.env` folder. U
    - `local_run.sh`  Used to run the flask application in development mode
    - `static` - default `static` files folder. It serves at '/static' path. 
    - `static/bootstrap` We have already added the bootstrap files so it can be used
    - `static/style.css` Custom CSS. You can edit it. Its empty currently
    - `templates` - Default flask templates folder
    - `Final_Placement.yaml` - YAML File for API
    - `Project Documentation` - Project Documentation
- `Frontend`
- `node-module` where all the nodes are installed and stored
- `public` 
- `scr ` codebase for frontend

Backend

```
├── application
│   ├── config.py
│   ├── controllers.py
│   ├── database.py
│   ├── __init__.py
│   ├── models.py
│   ├── validation.py
│   ├── api.py
│   └── __pycache__
├── db_directory
│   └── test.db
├── Final_Placement.yaml
├── local_run.sh
├── local_setup.sh
├── app.py
├── readme.md
├── static
│   ├── bootstrap
│   │   ├── css
│   │   └── js
│   └── style.css
└── templates
```

Frontend
```
`-- client
    |-- README.md
    |-- babel.config.js
    |-- jsconfig.json
    |-- package-lock.json
    |-- package.json
    |-- public
    |   |-- favicon.ico
    |   `-- index.html
    |-- src
    |   |-- App.vue
    |   |-- assets
    |   |   |-- Placement_logo.jpeg
    |   |   `-- logo.png
    |   |-- components
    |   |   |-- Login.vue
    |   |   `-- Register.vue
    |   |-- main.js
    |   |-- router
    |   |   `-- index.js
    |   `-- views
    |       |-- AddThreadView.vue
    |       |-- AssesmentView.vue
    |       |-- DashboardView.vue
    |       |-- AssesmentView.vue
    |       |-- LoginView.vue
    |       |-- MessageRecordsView.vue
    |       |-- MyAssesmentView.vue
    |       |-- MyThreadsView.vue
    |       |-- ScoreStatsView.vue
    |       |-- RegisterView.vue
    |       |-- ThreadDetailsView.vue
    |       |-- ViewScoreView.vue
    |       `-- SummaryView.vue
    `-- vue.config.js
```