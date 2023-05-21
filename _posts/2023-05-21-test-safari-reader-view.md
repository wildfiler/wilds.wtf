---
layout: post
title: "Will reader view work?"
date: 2023-05-21 09:24:00 +0200
---

I want to enable reader view in safari browser on my phone.
<!--more-->

Text after spoiler. I hope it will trigger reader view in safari. Anw I wounder, how many paragraphs of text should be in article to trigger it?

I'm not sure if code block will help or not. But I'll try:

{% highlight ruby %}
module Pod
  class UnknownAttribute < NoMethodError
    attr_reader :object, :name

    def initialize(object, name)
      @object = object
      @name = name
      super("unknown attribute '#{name}' for #{@object.class}.")
    end
  end
end
{% endhighlight %}

I think it will work. All ruby code works, why this shouldn't?.. Let's try to highlight some lines in ruby code:

{% highlight ruby linenos %}
module Pod
  class UnknownAttribute < NoMethodError
    attr_reader :object, :name

    def initialize(object, name)
      @object = object
      @name = name
      super("unknown attribute '#{name}' for #{@object.class}.")
    end
  end
end
{% endhighlight %}

Nope, you can't highlight lines, documentation is lying!

Ok, hope it will be enough.
