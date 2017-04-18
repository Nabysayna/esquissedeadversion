## Usage

### Quick start
**Make sure you have Node version >= 5.0 and NPM >= 3**

```bash
# change directory to our repo
cd dir_name

# install the repo with npm
npm install

# install TypeScript typings
npm run typings-install

# start the server
npm start

# use Hot Module Replacement
npm run server:dev:hmr
```
go to [http://0.0.0.0:3000](http://0.0.0.0:3000) or [http://localhost:3000](http://localhost:3000) in your browser


### Installing
* `npm install` to install all dependencies
* `npm run server` to start the dev server in another tab

### server
```bash
# development
npm run server
# production
npm run build:prod
npm run server:prod
```

<br>
## Other commands
### test
```bash
npm run test  -- Check the examples in page2 module.
```
### docs

```bash
npm run typedoc  
```
### build files
```bash
# development
npm run build:dev
# production
npm run build:prod
```

### hot module replacement
```bash
npm run server:dev:hmr
```

### watch and build files
```bash
npm run watch
```