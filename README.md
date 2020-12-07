# vue-common-component
> This is a vue project,to create some common vue component 

## run 
```shell
   cd vue-common-component
   npm install 
   # run dev
   npm run dev
   # run serve
   npm run start
```

## docker run with nginx 
```shell
    # generate the statics html
    npm run build:start 
    docker run --name vue-common-component -p 80:80 -v /dist/:/etc/nginx/html -d nginx
```

### note
> this is the git flow tip
Which branch should be used for bringing forth production releases?
   - develop
   - master
Branch name for production releases: [master]

Which branch should be used for integration of the "next release"?
   - develop
Branch name for "next release" development: [develop]

How to name your supporting branch prefixes?
Feature branches? [feature/]
Bugfix branches? [bugfix/]
Release branches? [release/]
Hotfix branches? [hotfix/]
Support branches? [support/]
Version tag prefix? []
Hooks and filters directory? [E:/repos/vue-common-component/.git/hooks]
