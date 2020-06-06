# vue-native-app

app-vue-native-example

## install dependencies

1. ubuntu 20.04

```bash
sudo snap install node --channel=14/stable --classic
sudo npm install -g @vue/cli @vue/cli-init --scripts-prepend-node-path
sudo npm install -g --unsafe-perm nativescript --scripts-prepend-node-path


```

## create tns project

```bash
gustavo@terminator-T2900:~/git-projects/vue-native-app$ tns create
Do you want to help us improve NativeScript by automatically sending anonymous usage statistics? We will not use this information to identify or contact you. You can read our official Privacy Policy at
? http://www.telerik.com/company/privacy-policy No

# Let’s create a NativeScript app!

Answer the following questions to help us build the right app for you. (Note: you
can skip this prompt next time using the --template option, or the --ng, --vue, --ts,
or --js flags.)

? First, what will be the name of your app? shark-app-vue

? Next, which style of NativeScript project would you like to use: Vue.js

? Finally, which template would you like to start from: Tabs

```


## running

```bash
cd shark-app-vue
tns preview
```