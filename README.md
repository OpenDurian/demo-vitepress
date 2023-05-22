

<p align="center">
  <a href="https://www.opendurian.com/" target="_blank">
     <img width="200" src="/docs/assets/images/OPD-logo.svg">
  </a>
</p>

<h1 align="center">
  <a href="https://www.opendurian.com/" target="_blank">OpenDurian Co., Ltd.</a>
</h1>

# Design Component CSS
Common styles for OPD web UI, generated from Figma Design Tokens

  
## How to install
- This project was host on our Github Package Registry, you will need a github access token to access it. If you don't have one, let create first.
- create `.npmrc` file at the root project using command below

    ```
    npm.pkg.github.com/:_authToken=TOKEN
    ```
  
 - replace `YOUR_GITHUB_ACCESS_TOKEN` with your **Gitlab Access Token** with scope `api`
 - You can get it [here](https://github.com/settings/apps)) 
 - If you cannot access the link above you can manually follow these step below
   - Click on your GitHub profile on the top right corner
   - Click Setting
   - Go to **Developer settings** > ** Personal access tokens **
 - Set token name as you want
 - Copy **access token** to replace `YOUR_GITHUB_ACCESS_TOKEN` in your `.npmrc` file 
 - Then You can install it with NPM or Yarn


### **NPM**
```sh
npm install @OpenDurian/demo-vitepress
```
or
### **Yarn**
```sh
yarn add @OpenDurian/demo-vitepress
```


