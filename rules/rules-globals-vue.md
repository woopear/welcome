# Rules to struc of project

---

_TODO list in repo of github_

- This name of card  
  | backlog | progress | bug | test | finish

---

_RULES of folder and files rename_

- General

```
//juste App.vue is camelcase
files and folder in src = lowercase
```

- Component unique

```
//this name of folder and files component unique
ex:
one menu = TheMenu
```

- Folder component or files .vue

```
//this name of folder and files component
ex:
folder => MyComponent
files => MyComponent.vue
```

- Folder and Files js

```
//this name of folder and files js
ex:
folder => myFolderJs.js
files => myFileJs.js
```

- Folder and Files ts

```
//this name of folder and files ts
ex:
folder => myFolderTs.ts
files => myFileTs.ts
files of type => myFile.T.ts
```

- Folder and Files css scss (asset)

```
//this name of folder and files ts
ex:
folder => myfolder
files => my-component.scss or my-component.css
```

---

_RULES struc folder of project_

- folder component

=> with api composition

```
ex :
=> TheHeader (folder)
  - TheHeader.vue (file)
  - TheHeader.ts (file)
  - TheHeader.T.ts (file)
```

=> with not api composition

```
ex :
=> TheHeader (folder)
  - TheHeader.vue (file)
```

- Struc global

```
Struc is "struc" of VUE CLI

//JUSTE
- folder of views for component is => views
- folder for functions divers is => libs
- folder for functions globals of component is => hooks
- folder for config divers is => config
```

---

_This Code_

- JS

```js
const myVariable = 'my variable';

const myObject = {};

class MyClass {}

function myFunction() {}
or;
const myFunction = () => {};

import LibImport from 'myLib.js';
```

- TS

```js
//rules of js + this rules here

enum MyEnum {
    ENUM1="my enum one"
    ENUM2="my enum two"
    //etc ...
}

interface MyInterface {
    propriete: string;
    propriete2: boolean;
    //etc ...
}

type mytype = string

```

- class in html

```html
<div class="my_class_box">
  <h1 class="my_class_title"></h1>
  <div class="my_class_box_sub_title">
    <h3 class="my_class_sub_title"></h3>
  </div>
</div>
```

---
