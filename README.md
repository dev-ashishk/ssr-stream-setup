[![CircleCI](https://circleci.com/gh/dev-ashishk/ssr-stream-setup.svg?style=shield)](https://circleci.com/gh/circleci/circleci-docs)

# SSR-STREAM-SETUP

### Features/

- [Docker](https://docs.docker.com/) `(docker-engine >=v19.x)`
- [Express](https://expressjs.com/) ` >= v4.x`
- [React](https://reactjs.org/) ` >= v16.x`
- [Redux](https://redux.js.org/) ` >= v4.x`
- [Loadable-components](https://loadable-components.com/) ` >= v5.x `
- [Webpack](https://webpack.js.org/) ` >= v4.x`
- [Babel](https://babeljs.io/) ` >= v7.x`
- [SASS](https://sass-lang.com/)
- [Circle-CI](https://circleci.com/) 
- [Jest](https://jestjs.io/)
- [Enzyme](https://enzymejs.github.io/enzyme/)
- [PWA](https://web.dev/progressive-web-apps/)


### Prerequisite
Before proceeding futher install following prerequisite dependencies to start:

- `Node.js version >= v10.x`
#

### Installation:

Steps to follow

1. Clone ssr-stream-setup
2. Change the current directory to `ssr-stream-setup`
```
cd ssr-stream-setup
```
3. Run the install `npm install`

4. To start the server run:
```
npm run dev 
```
or for Production
```
npm run build && npm run start
```
> open <http://localhost:3000> in browser.

### Create Docker image

``` 
npm run docker -- -c build 
```
OR use the script in `./tools/build.sh`

### Deploy Docker containers

```
npm run docker -- -c deploy
```
Or use the script in `./tools/deploy.sh`
