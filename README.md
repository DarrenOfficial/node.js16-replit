# NodeJS 16 on replit

This will work on your previous nodejs project and/or new one. I recommend using bash instead of nodejs tho…



## Installation
Run this command in the **Shell**

```bash

npm init -y && npm i --save-dev node@16 && npm config set prefix=$(pwd)/node_modules/node && export PATH=$(pwd)/node_modules/node/bin:$PATH

```

then replace the start commands on package.json to this

```json
  "scripts": {
    "start": "node ."
  }
```
## License
[MIT](https://choosealicense.com/licenses/mit/)
