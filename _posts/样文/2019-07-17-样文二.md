---
layout: post
title:  "样文二"
date:   2019-07-17 10:30:13
categories: 样文
tags: 样文
---

#### 我的第二篇博客

> 这里应该是导语

这里是正文！！！

Jekyll uses Rouge by default for syntax highlighting, here are some tests.

Ruby:
{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Python with line numbers:
{% highlight python linenos %}
def print_hi(name):
    print("Hi, {}".format(name))

print_hi('Tom')
# prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

C with line numbers:
{% highlight c linenos %}
void print_hi(string name) {
  printf("Hi, %s", name);
}
print_hi("Tom");
/* prints 'Hi, Tom' to STDOUT. */
{% endhighlight %}