# vue-common-component

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
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
