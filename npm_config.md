### install yarn
```
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
sudo apt update && sudo apt install yarn
```

### install npmrc
sudo npm i -g npmrc

### login to npm registry
npm adduser digz6666

### init npmrc?
npmrc digz6666

### init (from git repo root path)
npm init --scope=@astvision

### build & publish
```
yarn build
yarn npm:publish
```

### publish to npm registry (not working for this)
npm publish --access public

### unpublish
npm unpublish '@astvision/react-easy-crop' -f
