# 配置webstorm 插件
.ignore Coderpillr Theme WakaTime
## 配置npm
```javascript
    npx create-react-app part1
    cd part1
    npm start
```

### 配置React

```javascript
ReactDOM.render(<App />, document.getElementById('root'))
`这是将其内容渲染到div 元素中，其 id 值为 'root'，该元素在文件public/index.html中定义。

默认情况下，文件 public/index.html 并没有什么能够展示在浏览器的HTML标签内容。 您可以尝试在文件中添加一些 HTML。 但是，在用 React 开发时，需要渲染的内容通常需要定义为 React 组件。`
```

```javascript
您可能已经猜到，该组件将被渲染为div-标签，div中又包含一个p-标签，p标签包含的文本为Hello world 。

严格来说，这个组件被定义成了一个 JavaScript 函数。如下所示，这是一个不接收任何参数的函数 :


```