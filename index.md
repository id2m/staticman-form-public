## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/id2m/staticman-form-public/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.



## form with staticman

<form method="post" action="{{ site.staticmanUrl }}">
  <input name="options[redirect]" type="hidden" value="https://id2m.github.io/staticman-form-public/confirmation-envoi.html">
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


## formspree

<form method="POST" action="https://formspree.io/lacasebiocoutras.adm@gmail.com">
  <input name="email" placeholder="Your email" type="email">
  <textarea name="message" placeholder="Your message"></textarea>
  <button type="submit">Send</button>
</form>

## simple form
<!-- <form action="https://getsimpleform.com/messages?form_api_token=c1c4dbc5cbcc6f1322b861a9e057d6d6" method="post"> -->
  <!-- the redirect_to is optional, the form will redirect to the referrer on submission -->
  <!-- <input type='hidden' name='redirect_to' value='<the complete return url e.g. http://fooey.com/thank-you.html>' /> -->
  <!-- all your input fields here.... -->
  <!-- <input type='text' name='test' /> -->
  <!-- <input type='submit' value='Test form' /> -->
<!-- </form> -->

<!-- <form action="https://getsimpleform.com/messages?form_api_token=c1c4dbc5cbcc6f1322b861a9e057d6d6" method="post">
    <li class="contact-li">
        <input type="email" placeholder="Your email" id="email"/>
        <input type="submit" value="Subscribe" id="submit"/>
    </li>
</form> -->
<!-- https://github.com/Redgadget/form-jekyll/blob/gh-pages/index.html -->
<div class="wrap">
  <p>This subscribe form works, eventhough the website is static!</p>
  <form id="contact-form" class="form" action="https://getsimpleform.com/messages?form_api_token=c1c4dbc5cbcc6f1322b861a9e057d6d6" method="POST" enctype="multipart/form-data">
      <li class="contact-li">
          <input type="email" placeholder="Your email" id="email" class="contact-input" name="email" tabindex="2"/>
      </li>
      <input type="submit" value="Subscribe" id="submit"/>
    <input type="hidden" name='redirect_to' value="https://id2m.github.io/staticman-form-public/confirmation-envoi.html"/>
  </form>x    
</div>


---
---



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
