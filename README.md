# linkedevents-ui-theme
Linked events UI theme support for municipality specific components

## Installation
Get the experimental branch from City-of-Turku github, https://github.com/City-of-Turku/linkedevents-ui/tree/experimental/city-theme

## Configuration
Once you have this branch and the experimental branch from City-of-Turku, you will need to:
```Yarn add``` and ```Yarn link``` the branches together. 
Example: 
```
cd linkedevents-ui-theme
yarn link
cd ..
cd linkedevents-ui
yarn add ../linkedevents-ui-theme (../ used since it's local and not an npm package)
yarn link city_theme
```

## Startup
To start your experimental linkedevents-ui-turku: make a copy of your config_dev.json.example and name it config_dev.json. Inside, set
```"city_theme": "city_theme"```, then:
```
yarn
yarn start
```
