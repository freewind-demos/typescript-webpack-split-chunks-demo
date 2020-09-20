TypeScript Webpack Split Chunks Demo
=================================

使用webpack的`splitChunks`选项，可以将最后打包的文件分成多个chunk，比如将vendors与自己写的代码分开打包。

注意：生成的index.html中将会包含两个`<script>`依次导入所需要的文件。

```
<script type="text/javascript" src="vendors~main.d665857207647b96a5ac.js"></script>
<script type="text/javascript" src="main.c03b329367b0447f8f94.js"></script>
```

```
npm install
npm run demo
```

It will open page on browser automatically.
