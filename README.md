# create_books_2
因为一些原因制作的书籍第二弹。


## 制作pdf
xelatex处理

```
xelatex main.tex
```

## 制作epub
```
pandoc main.tex -o main.epub --metadata-file=epub.yaml
```