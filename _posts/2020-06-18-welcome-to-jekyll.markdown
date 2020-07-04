---
layout: single 

date:   2020-06-18 12:09:53 -0500


---
## Suh

I'm going to use this system to blog about my nerdy stuff...
Need to catalog how I set stuff up correctly so I don't forget every time.

Save the earf.

# Issues with installation

Had a bit of an issue installing this thing.
The recommended installation did not work.

First installed RVM using

`curl -sSL https://get.rvm.io | bash -s stable --ruby`

Then ran
`source /Users/username/.rvm/scripts/rvm`

And then I was able to install jekyll using
`gem install jekyll bundler` 

Leaving this here for reference..

# Jekyll reference stuff

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}
