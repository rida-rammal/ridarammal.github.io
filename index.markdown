---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---


<img style="float: left; padding-right:1%" src="img/me.png">

The pickle is the best food on earth. It goes well with just about anything from a hamburger, as a side, in a salad or my go-to afternoon snack. Pickles are also very low in calorie—for the average size pickle, it is only around 8 calories. And some snack-size pickles are 5 calories.


If you have ever wondered WTF you’re eating when indulging in a pickle, I’m about to give you the lowdown and answer all your questions. 



---




# The Basics Any and Every Self-Respecting Pickle-Lover Should Know

What do pickles, vinegar, tempeh, chocolate and wine have in common? Yes, they're all delicious—and they're all fermented. And that means they all have major health perks.

Ever wonder about the history of a pickle? No? Well here it is. The earliest known examples are cucumbers that are known to have been pickled sometime around 2030 BC in Mesopotamia, when inhabitants from northern India brought cucumber seeds to the Tigris valley. Romans pickled their pickles in vinegar, oil, brine and sometimes even honey. Can you say yum?

![alt text](img/pick.png)

## Quotes that will be echoed through history 

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

