[toc]

# 代码跳转
## 依赖 tag 文件
* 查看tag栈情况: <tag-!>
* 回到跳转栈的位置,即栈顶:`:tag`
* 跳转到定义，即入栈:`<C-]>`
* 从上次跳转回来,即出栈:`<C-t>`  
<u>`<C-o>`只是回到上次的位置，而不会改变跳转栈</u>
* 当定义有多个位置时，查看其列表：`g<c-]>`
## nvim内置lsp
## 自定义lsp