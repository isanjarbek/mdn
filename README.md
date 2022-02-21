# Tutorials
Content structure and file syntaxes 

Folders and files structure:

```
tutorials
    javascript
          -- 01-introduction
                - 01.getting-started.mdx
                - 02.fundamental-variables.mdx
                - 03.array-methods.mdx
          -- 02-advanced-array-methods
                - 01.getting-started.mdx
                - 02.fundamental-variables.mdx
                - 03.array-methods.mdx
    react-js
          -- 01-introduction
                - 01.getting-started.mdx
                - 02.fundamental-variables.mdx
                - 03.array-methods.mdx
          -- 01-getting-pro
                - 01.getting-started.mdx
                - 02.fundamental-variables.mdx
                - 03.array-methods.mdx
    index.md

```

# File Structure

File ning boshiga qoyish kere bogan code:

```
---
title: Title,
date: 'Yanvar 1, 2020'
tags: ['functions', 'javascript']
content: ['instalation', "what-is-javascript"]
---

# Instalation
...

# What is Javascript
...

```

# Index Md file da tutorials content

```
---
content: [
    {
        id: 1,
        title: "Javascript",
        description: "Complex functions in simple ways were written in the articles",
        link: '/getting-started'
    },
    {
        id: 2,
        title: "React JS",
        description: "Complex functions in simple ways were written in the articles.",
        link: '/use-state'
    }
]
---
```


# Code uchun SyntaxHighlighter ishlatamiz

```
<SyntaxHighlighter language="javascript">
  {`
    const doStuff = () => {
      return console.log('hello word')
    }
  `}
</SyntaxHighlighter>
```

# MDX Syntaxes

![image](https://user-images.githubusercontent.com/83394723/147534812-4e144a87-1c43-4923-9dd1-add15d2b3454.png)

![image](https://user-images.githubusercontent.com/83394723/147534874-4ca9a4da-6e16-4054-9fce-b4ef01daeb0c.png)

![image](https://user-images.githubusercontent.com/83394723/147534939-18f68985-f9ed-415a-a2c1-d09deda42130.png)

## Havola qo'yish
[] ichiga sayt nomi
() sayt linki

This site was built using [GitHub Pages](https://pages.github.com/).

## Rasm qo'yish

```![rasmga nom](rasm linki)```

## List 
![image](https://user-images.githubusercontent.com/83394723/147535217-3d92a7f0-99f9-4e82-8e2d-aa7f1b358232.png)

## Bildirishnoma

```@umarnazarov Hello, I am tagging you!```

## Izoh 

```<!-- Bu gap shu yerda qolsin :) -->```

## Qoshimcha syntax'lar [Markdowmark](https://www.markdownguide.org/basic-syntax/)
