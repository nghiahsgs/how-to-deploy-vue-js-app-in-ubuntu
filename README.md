# how-to-deploy-vue-js-app-in-ubuntu
how to deploy vue js app in ubuntu


# Step 1: Create a project use vue-cli
npm install -g @vue/cli
vue create test_vue

# Step 2: Add file vue.config.js in root project
```
cd test_vue
```
```
module.exports = {
    // options...
    devServer: {
        disableHostCheck: true
    }
}
```
# Step 3: Serve server
```
npm run serve
```

# Step 4: Install nginx and config for port vue
```
https://github.com/nghiahsgs/how-to-config-nginx-for-many-website
```
