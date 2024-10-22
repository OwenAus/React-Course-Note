## It's All About Components!

So React apps are in the end built by combining Components.

## <font color=blue>**Components, Props. **</font>

### index.html

```js
<body>
  <div id="root"></div>
  <script type="module" src="/src/index.jsx"></script>
</body>
```

### 43 import components, file, png

```js
import App from "./App.jsx";
import "./index.css";
import reactIMG from "./assets/react-core-concepts.png";
```

```js
const entryPoint = document.getElementById("root");
ReactDOM.createRoot(entryPoint).render(<App />);
```

## Output a dynamic value in JSX

To be precise,you can now add any JavaScript expression of your choice
between those curly braces.

## import a png

```js

```

## Making Comonents Reusable with Props[]

Prop like a parameter of object , defined by calling function .

And that's why React offers another crucial concept, that's related to components called props.
