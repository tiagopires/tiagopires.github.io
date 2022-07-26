---
title: "Fazer o setup de Autopilot para dispositivo Windows"
date: 2022-07-26T18:00:30-04:00
categories:
  - blog
tags:
  - Intune
  - Autopilot
---

Neste primeiro artigo vamos explorar primeiro como fazer o setup para Autopilot. Tem vindo a ser mais comum chamarmos um computador de dispositivo.

<H2>Registar dispositivos</H2>

O primeiro passo para fazer o setup de Autopilot será registar os dispositivos windows no serviço do Autopilot. Normalmente o caso comum é já termos alguns dispositivos mas acontece que não estão enrolled no Intune e portanto não os conseguimos ver na consola.

Este passo server exatamente para isso.

**Permissões / Roles de Azure:** Para efetuar todas estas alterações e setup é necessário que seja feito com um utilizador que tenha no minimo a role de *Intune Administrator*
{: .notice--info}





You'll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

```ruby
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
```

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
