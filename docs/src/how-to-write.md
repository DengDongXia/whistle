# 文档规约

单文件的文档组织方式，通过脚本来合并文档


## 文件名

文件名对应文档左边的导航，pattern: /[\d\.]+_\w+\.md/
* `1_home.md`
  * `1.1_hello.md`
  * `1.2_world.md`
* `2_guide.md`

以便于脚本按约定文件名合并

## 标题

* 文档的主标题是 h2 (`##`)，标题后面追加 anchor, e.g.  `## home {#index}`
* 副标题 h4 (`####`) ，与主标题字体大小上有视觉差异
* 子标题通过 **加粗** 的方式


## 代码块

优先使用 \`\`\` 的方式，在其后追加代码语言类型，比如：\`\`\`js，避免代码块里面一些注释性的文本扰乱 md 的解析


## 中英文空格

更好的阅读效果，推荐中英文留空格

相关的插件
* vscode extension: pangu ，目前发现中文加粗有 bug