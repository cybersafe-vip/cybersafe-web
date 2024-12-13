# cybersafe-web
Website for CyberSafe

## Cloning the website
```shell
git clone https://github.com/cybersafe-vip/cybersafe-web
```

## Installing system dependencies
In the root of your project install the necesarry Node.js dependencies.
```shell
npm i -D postcss postcss-cli autoprefixer
```

## Installing site dependencies
In the root of your project install the necesarry site dependencies
```shell
npm install
```

## Running the website
Serve the site in development mode, which is the default:
```shell
# In development mode (which has guidlines etc visible in the web)
hugo serve -D
# In production mode
Hugo server --environment production
```
