---
layout: default
permalink : /
---



The pickle is **the best food on earth!** 
It goes well with just about anything from a hamburger, as a side, in a salad or my go-to afternoon snack. 
Pickles are also very low in calorie—for the average size pickle, it is only around 8 calories. And some snack-size pickles are 5 calories.

If you have ever wondered **WTF you’re eating when indulging in a pickle**, I’m about to give you the lowdown and **answer all your questions**. 
<!--Inserting images using markdown is very limited and does not allow you to change alignment. Use HTML instead. -->
![pick]({{site.base_url}}/img/gangsta-pickle-pickle-appreciation-day.gif)


---




# The Basics Any and Every Self-Respecting Pickle-Conoisseur Should Know

What do pickles, vinegar, tempeh, chocolate and wine have in common? Yes, they're all delicious—and they're all fermented. And that means they all have major health perks.
Ever wonder about the history of a pickle? No? Well here it is. 
![pick]({{site.base_url}}/img/pick.png)
The earliest known examples are cucumbers that are known to have been pickled sometime around 2030 BC in Mesopotamia, when inhabitants from northern India brought cucumber seeds to the Tigris valley. Romans pickled their pickles in vinegar, oil, brine and sometimes even honey. Can you say yum?
They've also had some famous fans throughout history. Cleopatra, Julius Caesar, and Napoleon Bonaparte have all touted the power of a good pickle.



---
# Six Reasons Why You Can’t Trust People Who Hate Pickles
<div align="center">
<figure >
<img src="{{site.base_url}}/img/luffy_sad.jpg" alt="luffy" width="40%" height="40%"/>
<figcaption>When someone tells me they don't like pickles</figcaption>
</figure>
</div>

## 1. The pickle is the cucumber’s cooler cousin

<div align="center">
<img src="{{site.base_url}}/img/pickle-dill-with-it.gif" alt="luffy" />
</div>

## 2. Pickles can be sour, sweet, fried, sliced, big, small, and more

Almost anyway you want it, you can have it. If you like a crunchy texture then have a fried pickle like these. If you like more sugary foods, then have a sweet pickle. If you like everything bitter, then have a sour pickle, and so on. There’s pretty much a pickle out there for everyone, so you haters don’t have an excuse.

## 3. Pickles are an ancient delicacy


<div class="row">
<div class="column">
<img src="img/tigris.jpg" alt="Snow" style="width:100%">
</div>
<div class="column">
<img src="img/egypt--thebes--tomb-of-nakht--banquet-scene--tombs-of-the-nobles.jpg" alt="Forest" style="width:100%">
</div>
 <div class="column">
<img src="img/tsukemono.jpeg" alt="Mountains" style="width:100%">
</div>
</div> 

If you don’t like pickles, you’re totally behind the times because these puppies are embedded in rich history. According to the NY Food Museum, pickles date back to 2400 BC with the Mesopotamians. You don’t mess with the past.

## 4. If it weren’t for pickles, Christopher Columbus may have never discovered America.

That’s right, pickle lovers discovered America. On his voyage to America, Columbus rationed pickles in order to prevent his troops from getting scurvy. He even made a pit stop at Haiti to pickle more cucumbers on his way to America. A diss to a pickle is a diss to America.

## 5. Napoleon was a huge fan of pickles.

Napoleon Bonaparte believed pickles were integral for the health of his troops. He loved pickles so much that he put up the equivalent of $250,000 as a prize to whoever could figure out the best way to pickle and preserve foods for his troops. He was once one of the most powerful people of the world, so I’d take his judgment over you pickle haters any day.


## 6. Pickles are scientifically proven to make you happier. 

Well, that one I may have made up. But if you aren’t happier when you plop a delicious pickle in your mouth, I definitely cannot trust your judgment.

### Quotes that will be echoed through history 

> *"It takes a sour woman to make a good pickle"*
>
> *"When something is important enough, you do it even if the odds are not in your favor."*






### Pickling is actually a verb!

```python
# Python3 program to illustrate store
# efficiently using pickle module
# Module translates an in-memory Python object
# into a serialized byte stream—a string of
# bytes that can be written to any file-like object.

import pickle

def storeData():
	# initializing data to be stored in db
	Omkar = {'key' : 'Omkar', 'name' : 'Omkar Pathak',
	'age' : 21, 'pay' : 40000}
	Jagdish = {'key' : 'Jagdish', 'name' : 'Jagdish Pathak',
	'age' : 50, 'pay' : 50000}

	# database
	db = {}
	db['Omkar'] = Omkar
	db['Jagdish'] = Jagdish
	
	# Its important to use binary mode
	dbfile = open('examplePickle', 'ab')
	
	# source, destination
	pickle.dump(db, dbfile)					
	dbfile.close()

def loadData():
	# for reading also binary mode is important
	dbfile = open('examplePickle', 'rb')	
	db = pickle.load(dbfile)
	for keys in db:
		print(keys, '=>', db[keys])
	dbfile.close()

if __name__ == '__main__':
	storeData()
	loadData()

```


#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```

