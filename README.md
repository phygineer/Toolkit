# Toolkit
An electron app for software tools

___

### Getting Started

- Clone the repo: `git clone https://github.com/phygineer/Toolkit.git`
- Install dependencies: `npm install`
- Run the app: `npm start`


### To Do
- [ ] Decide on storage method
    - Data should be storaed on local machine on user's computer
    - We will need different kinds of storage for different types of data
        - App settings - stored in a JSON file  
        - Tool specific data  - stored in local database
    - Requirement is data should persist

- [ ] Create a roadmap for tools development

##### Commands History

```shell

npm init electron-app@latest toolkit

mv ./toolkit/* ./
mv ./toolkit/.gitignore ./
rm -r toolkit

npm start

npm run make

npm install --save-dev @electron-forge/publisher-github

npm i update-electron-app

npm run publish

    Please set GITHUB_TOKEN in your environment to access these features

```


##### Usefull Links

- [Electron Forge](https://www.electronforge.io/)
- [Update Electron App](https://github.com/electron/update-electron-app)
- [Auto updating from GitHub](https://github.com/electron/update.electronjs.org)
- [PublisherGitHubConfig](https://github.com/electron/forge/blob/ccf606325/packages/publisher/github/src/Config.ts)