## What is EMMA?
While many AI models are trained to predict a single, definitive answer for each given query, in real life, we often encounter many situations where there are no black or white answers! We introduce, EMMA, a machine advisor that goes beyond such one-dimensional decison to uncover answers and belief structures in complex situations.


### How does EMMA work?

EMMA materializes the beliefs of the model for an input statement, uncovering different assumptions and perspectives. It then builds a network of beliefs, and that structure is critiqued using self-feedback (such as structural consistency, self-beliefs) and human feedback (such as thumbs down). Together with this critique, the network of beliefs is then improved using maxsat based reasoning to generate the most consistent belief network as output.


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

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/nikett/emma/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
