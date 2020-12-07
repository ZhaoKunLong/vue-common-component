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
