# git-username
Get git user email using node - js With git commands

# Commands
```
npm i 
```

or 

```
npm install 
```

# Usage
```js
    import gitUsername from "./main.js";

    try {
        const username = await gitUsername();
    } catch (error) {
        console.error(error);
    }
```
