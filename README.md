# VueJS_2.x_snippets
VueJS 2.x snippets, tricks, helpers that I've found useful in my projects

## Vuetify
### Run a function when a dialog is visible on the screen
```
watch: {
    dialog(visible) {
        if(visible) {
            console.log("Dialog Window Opened!!");
        }
    },
},
```

