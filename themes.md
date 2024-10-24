# Instructions

## Using CLI
https://github.com/rbardini/resumed

### Create Sample Resume
`resumed init {{resume-name}}`
- Edit your resume-name.json. 
- Add new keys if your theme extends the schema (ex americano theme supports work keywords)

### Validate the Json
`resumed validate {{resume-name}}`


### Install Theme
`npm install -g resumed {{theme}}`

### Render your resume in html in the desired theme (has to be installed first)
`resumed render daniela -t {{theme-latte}}`

## Workflow
This allows to easily version resumes. Ex:
daniela-company1.json
daniela-company1-long.json

You can easily switch themes!

## Export
You need the original resume-cli
`npm install -g resume-cli`
`npm install -g resume jsonresume-theme-americano`

`resume export {{resume-name}} --theme {{theme-name}} --format pdf

## Deployment
- Once you render your resume you'll get a `resume.html` file created.

- Rename your json to resume.json and create a new gist on github

- TADA: registry.jsonresume.org/{{gh-username}} will be hosted and publicly available

- To set a theme, just add to your resume.json
{ "meta": { "theme": "{{theme-name}}" } }

- You can create a repository with a github action to update the gist more easily

- You can access more raw formats of your resume too:
registry.jsonresume.org/{{gh-username}}.json/yaml/txt

## Themes I like
- jsonresume-theme-americano -> https://www.npmjs.com/package/jsonresume-theme-americano
- jsonresume-theme-elegant-maksymgendin
- jsonresume-theme-kendall-web
- @4lch4/jsonresume-theme-stackoverflow

jacrys
ace
even
pumpkin
onepage-plus
professional
elegant
jsonresume-theme-macchiato-plus
