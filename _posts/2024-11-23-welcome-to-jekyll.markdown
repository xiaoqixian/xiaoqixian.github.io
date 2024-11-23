---
layout: post
title:  "Welcome to Jekyll!"
date:   2024-11-23 11:31:33 +0800
categories: diary
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

### Maxwell Equations

$$
\begin{align}
    \oint_{\partial S} \mathbf{E} \cdot d\mathbf{l} &= -\frac{\partial}{\partial t} \int_{S} \mathbf{B} \cdot d\mathbf{A} \tag{Faraday's Law} \\
    \oint_{\partial S} \mathbf{B} \cdot d\mathbf{l} &= \mu_0 \int_{S} \mathbf{J} \cdot d\mathbf{A} + \mu_0 \varepsilon_0 \frac{\partial}{\partial t} \int_{S} \mathbf{E} \cdot d\mathbf{A} \tag{Ampere's Law} \\
    \oint_{S} \mathbf{E} \cdot d\mathbf{A} &= \frac{1}{\varepsilon_0} \int_{V} \rho \, dV \tag{Gauss's Law for Electric Fields} \\
    \oint_{S} \mathbf{B} \cdot d\mathbf{A} &= 0 \tag{Gauss's Law for Magnetic Fields}
\end{align}
$$

