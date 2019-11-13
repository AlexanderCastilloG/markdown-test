<!--HEADING -->

# mi title
## my title h2
### my title h3
##### my title h4
##### my title h5
###### my title h6

<!-- italic -->
this is an *italic* text

<!-- strong -->
this is an **strong** text

<!-- strikethrough -->
this is an ~~text~~ tachado


<!-- UL -->
* apple
    * apple 2
* orange
    * orange 2
* etc

1. apple
    1. apple 2
2. orange
3. etc

<!-- Enlaces -->
[goole.com](https://www.google.com)

[goole.com](https://www.google.com "Custom tile")

<!-- Citas -->
>this  is a quote
---
___

<!--Para copiar código-->
```javascript
const mongoose = require('mongoose');

mongoose.set('useFindAndModify', false);

mongoose.connect('mongodb://localhost/node-notes-db', {
    use createIndex: true,
    useNewUrlParser: true
})
.then(db => console.log('DB is connected'))
.catch(err => console.error(err));
```

```python
print("Hello world");
```

```html
<h1>helloword</h1>
```

<!--tables -->
| Tables        | Are           | Cool  |
|---------------|---------------|-------|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |  $12  |
| zebra stripes | are neat      |  $1   |

<!--Imagenes Remota-->
![visual studio code logo](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/1200px-Visual_Studio_Code_1.35_icon.svg.png)

<!--Imagenes Locales -->
![visual studio code logo](./vscode.png "vscode logo")

<img src="./vscode.png" style="width:200px; height=200px;"/>


<!-- GITHUB MARKDOWN -->

* [x] Task 1
* [ ] Task 2
* [ ] Task 3
* [x] Task 4

