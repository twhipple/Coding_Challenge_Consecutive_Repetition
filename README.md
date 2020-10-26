

# Code Challenge: 

![](https://raw.githubusercontent.com/twhipple/Coding_Challenge_Simple_Time_Difference/main/Images/yasin-hasan-k5R9SGDAGJc-unsplash.jpg)

*Alarm clocks and time. Source: Yasin Hasan, Upsplash.com*


## Coding Challenge Consecutive Repetition

This Repo is about another coding challenge that relates to a find the longest consecutive repetition within a string of characters. This is another Kata found in CodeWars and is a level 6 kyu. I tried many different attempts as you will see. It's almost embarrassing how long it took me when in reality it shouldn't have been that difficult. I tried dictionaries - but it was difficult to sort a dictionary by both a character and a number. I tried from itertools import groupby but found the output to be difficult to manipulate. And I tried looking up a way to use regular expressions to group the characters. In the end, I needed to get some help from a friend in order to get back on track.

For a given string s find the character c with longest consecutive repetition and return:

(c, l)

where l is the length of the repetition. If there are two or more characters with the same l return the first in order of appearance.

For empty string return:

('', 0)


## Examples:

chars1 = "aaaabb" # ('a', 4)
chars2 = "bbbaaabaaaa" # ('a', 4)
chars3 = "cbdeuuu900" # ('u', 3)
chars4 = "abbbbb" # ('b', 5)
chars5 = "aabb" # ('a', 2)
chars6 = "ba" # ('b', 1)
chars7 = "" # ('', 0)


## Additionally

This seeemed like a pretty straight forward solution to me. There was something about the output that was troubling me - and ultimately took me down many a wrong path. Ultimately, I just needed to set ups some variables and iterate through the string in order to solve it.

This kata was written by: suic

Thank you to Codewars for helping me practice my Python skills.

![](https://raw.githubusercontent.com/twhipple/Coding_Challenge_Simple_Time_Difference/main/Images/aron-visuals-BXOXnQ26B7o-unsplash.jpg)

*This code challenge too some time! Source: Aron Visuals, Upsplash.com*


