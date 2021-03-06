---
layout: post
title:      "Ya'll gonna do a learn, a learn, and another learn today. "
date:       2018-05-01 00:07:35 -0400
permalink:  yall_gonna_do_a_learn_a_learn_and_another_learn_today
---

Hey guys! It's been longer than I'd like to admit since I've posted...way...way longer. But I am here! Hello. I am going to attempt to teach you some code which will also serve as a refresher for me. Let's do the thing.

**The Oxford Comma Lab**

This lab had me stumped. So I did some googling and felt even more stumped. I decided to ask a friend for help. He made everything click because he's an angel and or a coding wizard. Now I will pass his blessings on to you. Buckle up, guys. You're going to learn something today. 

The lab's purpose was simple: *"Write a method called reverse_each_word that takes in a string argument of a sentence and returns that same sentence with each word reversed in place.”*

This is the code that got the lab to pass:

```
def oxford_comma(array)
 if array.length == 1
   return "#{array[0]}"
 elsif array.length == 2
   return array.join(" and ")
 elsif array.length >= 3
   array[-1] = "and #{array[-1]}"
   return array.join(", ")
 end
end
```

What does this all mean? I'll break it down.

```
def oxford_comma(array)
 if array.length == 1
   return "#{array[0]}"
```

This means if the array is one string long, it will just return the single string at the first index, or `#{array[0]}`

The next line is basically the same thing. The exception is that the condition is now: if the array.length is two strings, join them with the word "and".

```
return array.join(" and ")
```

The final condition is if there are three strings in the array, put "and" plus the last word in the array at the last index spot. Then, join it with commas. The last index will be one string. 

```
 elsif array.length >= 3
   array[-1] = "and #{array[-1]}"
   return array.join(", ")
```

The last thing is so the "and ... " displays correctly. So the last word is basically replaced with and plus itself. 


....Get it? Kind of? Re-read it if need be. It took me a while. 

Initially, my friend showed me how he solved this lab using conniption statements (something I don't know) and ternary operators (something I do know!), but in his own words: " I dont know if you want to dive down those rabbit holes just yet" (he's right). Maybe once I get to that point I can come back and explain his simpler, more complex solution. For now, this works perfectly. My lab is passing and I can move forward. Hope you enjoyed reading this! 


