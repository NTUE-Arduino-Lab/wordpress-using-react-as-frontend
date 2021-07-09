This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app) + Eslint + stylelint + Prettier

## Before clone this project:（下載專案前請看！）

windows 的電腦，請在終端機先進行以下操作

`git config --global core.autocrlf false`

### 原因：

windows 系統 和 unix-based 系統，預設的文件換行符號有以下的差異，會導致 prettier 出現不必要的錯誤

* windows 系統: cr + lf

* unix-based 系統: lf

---

## After clone this project（關於專案規劃與要修改的內容）

### 1. 專案規劃上較為特殊之處

* mu-plugins 資料夾：撰寫 wordpress REST api 之處

* public/assets 資料夾：放置靜態圖片與資料的位置

* 以上兩個資料夾，會於 build 指令執行後，複製至適當的位置


### 2. 需要修改的內容

修改 `package.json` 內容

```
{
    "homepage": "ALIAS-OF-SITE/wordpress/wp-content/themes/NAME-OF-THEME/REACT-PROJECT-NAME/build",
    ...
}

```

* `ALIAS-OF-SITE` 請改成虛擬目錄下的別名

* `NAME-OF-THEME` 請改成 custom theme 的資料夾名稱

* `REACT-PROJECT-NAME` 請改成 custom theme 下 React 專案的名稱

---

## 以下為原始的 Readme 內容

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
