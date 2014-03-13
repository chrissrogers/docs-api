Credit cards and such

{% highlight haskell linenos %}
main = a `par` b `par` c `pseq` print (a + b + c)
  where
    a = ack 3 10
    b = fac 42
    c = fib 34
{% endhighlight %}
