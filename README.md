Use it with

`npm install --save markdown-it-samp`

```javascript
import MarkdownIt from 'markdown-it'
import MarkdownItSamp from 'markdown-it-samp'

const md = new MarkdownIt()
md.use(MarkdownItSamp)

console.log(md.render('´´´\nresult\n´´´\n')) // <pre><samp>result</samp></pre>
```

I'll provide a better readme, tests, etc in future days.
