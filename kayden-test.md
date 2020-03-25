---
title: Test Markdown (Kayden)
---



## Famous Quotes
Here is an amusing quote from my buddy [Abraham](https://www.brainyquote.com/authors/abraham-lincoln-quotes/):
> If I were two-faced, would I be wearing this one?

And now, for a great quote on acting from the infamous [Robin Williams](https://www.brainyquote.com/authors/robin-williams-quotes/):
> I enjoy performing for heavily armed people. It's easier than going to Georgia.


## Penguins

I like penguins. 

![Image of a cute penguin](assets/images/penguin.jpg "Penguins are great")


## Tables are fun

Text                        | Simplified Text (In Italics)
---                         | ---
Due to the fact that	    | *because*
In the event that           | *in case, if*
At this point in time	    | *right now, now, at the moment*
Obtain	                    | *get*
Subsequent	                | *following, next*
In the vicinity of          | *near, around, close to*

### Conciseness Helps Web Readers
When I'm browsing, especially documentation, I don't have time to *read* your website. It should be effortless, efficient reading. Conciseness accomplishes this.

Here's an inconcise quote:

> At this point in time we can't ascertain the reason as to why the screen door was left open.

and here is the concise version:

`Right now we can't figure out why the screen door was left open.`

Here's a second inconcise quote:

> There is a desire on the part of many of us to maintain a spring break for the purpose of getting away from the demands of our studies.

and here is its concise version:

`Many of us want a spring break so we can escape our studies' demands.`


## Code Blocks Make Me Happy

My code, below, uses the python `urllib.request` and `BeautifulSoup4` modules to print a random instruction from WikiHow.

```py
page = urllib.request.urlopen("https://www.wikihow.com/Special:Randomizer")
page_soup = BeautifulSoup(page, 'html.parser')

def step_identifier(tag_id):
    return tag_id and tag_id.startswith('step-id-')

current_step = page_soup.find_all(name="li", id=step_identifier, limit=i+1)[i]

attempts = 0
current_instruction = current_step.find(class_="whb")
while not current_instruction.string and attempts < 5:
    current_instruction = current_instruction.find_next(class_="whb")
    attempts += 1

if current_instruction.string:
    current_instruction = current_instruction.string
else:
    current_instruction = str(current_instruction)

print(current_instruction)
```

This code prints Janelle's birthday.

```js
let age = Math.floor(
        Math.abs(
            new Date().getTime() - new Date(2019, 11, 31).getTime()
        ) / 1000 / 60 / 60 / 24  // Convert milliseconds to days (since Janelle has one birthday per day)
    );
console.log(age)
```


**I have completed the activity. There we go, I guess.**