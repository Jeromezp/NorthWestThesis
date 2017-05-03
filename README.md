# NorthWestThesis
西北农林科技大学本科生毕业论文Latex模板

## 目录结构如下
- `figures` 资源文件存放目录
- `pagers` 论文章节目录
- `refs` 参考文献目录
- `utils` 引用其他宏目录
- `master.tex` 入库目录文件

## 使用方式
1. 使用编译软件打开`master.tex`
2. 使用`xelatex`编译器,进行编译
3. 编译后产生`master.pdf`

## 其他说明
1. `pagers`目录中存放着相应章节页面，只需在对应章节填写相应的内容
2. `pagers\message.aux`存放封面的相关信息，只需要进行按注释要求填写
3. `refs\thesis-ref.bib`存放参考文献数据，按格式写即可

## TODO
- 进一步将样式和内容分离
- 优化文档结构
- 自定义宏
