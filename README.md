# Personal website

This site is created from the tempalte of [ai-folio](https://alshedivat.github.io/al-folio/).

Run the following commands to run locally, assuming you have had ruby installed already:

```bash
$ bundle install
$ bundle exec jekyll serve --lsi
```

When deploying to github, you might face problem like pages not deployed. If you run into such cases which I did myself, perform the following steps:  
Settings > Pages > Build and deployment > Source: Github Actions (beta), which includes jekyll already.
