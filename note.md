排錯紀錄：

1. 使用 `hexo serve` 時失敗。

1-1. 安裝 lodash
來自錯誤訊息：
```zsh
ERROR Script load failed: themes/minos/scripts/10_i18n.js
Error: Cannot find module 'lodash'
...
```

1-2. 安裝 cheerio
來自錯誤訊息：
```zsh
ERROR Script load failed: themes/minos/scripts/99_tags.js
Error: Cannot find module 'cheerio'
...
```

1-3. 安裝 
npm install hexo-log



```zsh
ERROR Script load failed: themes/minos/scripts/10_i18n.js
Error: Cannot find module 'hexo/lib/plugins/generator/post'
```

1-4.
```zsh
ERROR Script load failed: themes/minos/scripts/01_check.js
TypeError: require(...) is not a function
```