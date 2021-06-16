# Blah

## Welcome to GitHub Pages

LALALALAL

You can use the [editor on GitHub](https://github.com/peterjkz/PP_SBDC_test/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.


### de rrn file

Kolommen zijn gebaseerd op "afstand" : na 50, 100, ... karakters .
Het RRN hangt in een tekst (string) in de eerste kolom.

bekijk de file :
```shell
head -n5 OVL_20201001
```

### opkuisen van de file
Eerst

time : geeft de verwerkingstijd

```shell

time awk -F " " '{print $1}' OVL_20201001.csv > OVL20201001_1e_kolom.csv

head -n5 OVL20201001_1e_kolom.csv

time cut -c3-13 OVL20201001_1e_kolom.csv > OVL20201001_RRN.csv

head -n5 OVL20201001_RRN.csv

![image](https://user-images.githubusercontent.com/11255455/122234123-e79e0b00-cebc-11eb-8bd8-b02457ba170e.png)

```

```javascript

a = 10;
b = 5;
a*b 
for(i; ...)
```



### Markdown
Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/peterjkz/PP_SBDC_test/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
