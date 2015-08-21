---
layout:     post
title:      "Writing Good Code - Part 1"
subtitle:   "Good and bad coding styles"
date:       2015-08-21 12:00:00
author:     "Sourabh Rohilla"
header-img: "img/post-bg-06.jpg"
---

<h3>Code is read much often than it is written.</h3>

<p>And its not just other people who are reading your code. You’ll be refactoring your code continuously. More so, your code should be clear and readable. Documenting your code is also important (more on that later). 
Here are the most common mistakes that ruin readability of your code big time. These coding elements seem convenient while writing, but makes a code look bad and unreadable.</p>

__Naming your variables and functions__ : Variables names should be descriptive. Say, you want to calculate total value of a shopping transaction given a dictionary containing prices of items. Similarly, try to name your methods using verbs, which conveys the task they do.

{% highlight python %}
def bill_calculation(d):
	d = {
		"eggs":1,
		"biscuits":2,
		"milk":3
		}
	s=0
	for i in d.values():
		s+=i
		return s
{% endhighlight %}

Compare this with -

{% highlight python %}
def calculate_shopping_total(shopping_cart):
	shopping_cart = {
		"eggs":1,
		"biscuits":2,
		"milk":3
		}
	bill_value = 0
	for item_price in shopping_cart.values():
		bill_value+=item_price
		return bill_value
{% endhighlight %}

See? its not that hard, but it turns your code into a story.



