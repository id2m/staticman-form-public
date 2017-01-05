## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/id2m/staticman-form-public/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.


<form method="post" action="{{ site.staticmanUrl }}">
  <!-- <input name="options[redirect]" type="hidden" value="https://my-site.com"> -->
  <!-- e.g. "2016-01-02-this-is-a-post" -->
  <input name="options[slug]" type="hidden" value="2016-01-05-test">
  <input type="hidden" name="options[parent]" value="2016-01-05-test">
  <input type="hidden" name="options[origin]" value="https://id2m.github.io/staticman-form-public/">

  <label><input name="fields[name]" type="text">Name</label>
  <label><input name="fields[email]" type="email">E-mail</label>
  <label><textarea name="fields[message]"></textarea>Message</label>
  <input id="form-subscribe" type="checkbox" name="options[subscribe]" value="email" class="checkbox">
  <!-- <button type="submit">Go!</button> -->
  <label for="form-subscribe" class="form__field checkbox__label">I want to be notified of new comments</label>
  <input class="cta" type="submit" value="Send" />
</form>


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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/id2m/staticman-form-public/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
