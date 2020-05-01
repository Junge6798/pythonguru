---
title: Hello World
date: 30th April, 2020 08:00:00
parent: /toc/section-one/
tags:
 - helloworld
description: Hello World program in Python
permalink: /toc/section-one/hello-world/
prev_link: /toc/section-one/features/
next_link: /toc/section-one/repl/
---

# Hello World Program

Writing a `Hello World` program in Python is as simple as writing a single line in
a file as

```python
print('Hello World')

# output
Hello World
```

## Do it yourself

Create a file name as `hello.rb` in your favorite editor or through command line editor like `vim`.

Although, you can give any name to file. I have used `hello`.
By convention, Python source files have `.py` file extension.

Then, type following line in the file:

```python
print('Hello World')  # or print("Hello World") using double quotes
```

Run the program in the terminal or shell as:

```shell
python3 hello.rb
```

{% include util/show-output.html id="pythonhello" caption="Output" %}
{% include util/output.html id="pythonhello" output="Hello World" lang="python" %}

##### Congrats! You just wrote your first program in Python.

## Key points to understand

- File extension of Python program is `.py`
- To print string into the standard output (i.e monitor), you can use `print`.
- `#` is used as comment operator
- Single and double quotes can be used to define String.
