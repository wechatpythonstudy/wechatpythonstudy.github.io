
# MathJax

When $$a \ne 0$$, there are two solutions to $$ax^2 + bx + c = 0$$ and they are

$$x_1 = {-b + \sqrt{b^2-4ac} \over 2a}$$

$$x_2 = {-b - \sqrt{b^2-4ac} \over 2a} \notag$$

<!--more-->

You need set `mathjax: true` in the *_config.yml* or the markdown’s front matter to **enable** it.
{:.warning}

**After MathJax enabled**, you can set `mathjax_autoNumber: true` to have equations be numbered automatically, You can use `\notag` or `\nonumber` to prevent individual equations from being numbered.
{:.info}

**markdown:**

```tex
When $$a \ne 0$$, there are two solutions to $$ax^2 + bx + c = 0$$ and they are
$$x_1 = {-b + \sqrt{b^2-4ac} \over 2a}$$
$$x_2 = {-b - \sqrt{b^2-4ac} \over 2a} \notag$$
```

**front matter:**

    ---
    ...
    mathjax: true
    mathjax_autoNumber: true
    ---

**hello:**

    ---
    ...
    mathjax: true
    mathjax_autoNumber: true
    ---


```
wobu cao ni ba
```

`hello  c `
