

# Code Challenge: 

![](https://raw.githubusercontent.com/twhipple/Code_Challenge_Consecutive_Repetition/main/Images/wilhelm-gunkel-invYnIE2Mv8-unsplash.jpg)

*Counting the number of repeated letters, over and over. Source: Wilhelm Gunkel, Upsplash.com*


## Coding Challenge Consecutive Repetition

This Repo is about another coding challenge that relates to a find the longest consecutive repetition within a string of characters. This is another Kata found in CodeWars and is a level 6 kyu. I tried many different attempts as you will see. It's almost embarrassing how long it took me when in reality it shouldn't have been that difficult. I tried dictionaries - but it was difficult to sort a dictionary by both a character and a number. I tried from itertools import groupby but found the output to be difficult to manipulate. And I tried looking up a way to use regular expressions to group the characters. In the end, I needed to get some help from a friend in order to get back on track.

For a given string s find the character c with longest consecutive repetition and return:

(c, l)

where l is the length of the repetition. If there are two or more characters with the same l return the first in order of appearance.

For empty string return:

('', 0)

![](https://raw.githubusercontent.com/twhipple/Code_Challenge_Consecutive_Repetition/main/Images/nicole-ferzoco-nY2ksaM92co-unsplash.jpg)

*I felt like I was going around in consecutive circles with this kata! Source: Nicole Ferzoco, Upsplash.com*


## Examples:

* chars1 = "aaaabb" # ('a', 4)
* chars2 = "bbbaaabaaaa" # ('a', 4)
* chars3 = "cbdeuuu900" # ('u', 3)
* chars4 = "abbbbb" # ('b', 5)
* chars5 = "aabb" # ('a', 2)
* chars6 = "ba" # ('b', 1)
* chars7 = "" # ('', 0)


## Additionally

This seeemed like a pretty straight forward solution to me. There was something about the output that was troubling me - and ultimately took me down many a wrong path. Ultimately, I just needed to set ups some variables and iterate through the string in order to solve it. The last two examples also took some additional work, but not near as much as getting started!

This kata was written by: suic

Thank you to Codewars for helping me practice my Python skills.

![](https://raw.githubusercontent.com/twhipple/Code_Challenge_Consecutive_Repetition/main/Images/letters-2-Stephen%20Tainton.jpg)

*This code challenge took a lot of time looking at strings of letters! Source: Stephen Tainton, Upsplash.com*


