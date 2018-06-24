# Metaphorical Connections

This serves as the data repository for the paper the paper [Challenges in finding metaphorical connections](http://www.aclweb.org/anthology/W18-0901) from the NAACL Workshop on Figurative Language Processing 2018.

Included in `metaphorical-connections.csv` are 186 poems collected on Amazon Mechanical Turk in March and April 2018 and their category as determined by the evaluation. 

Each worker was given a metaphorical prompt and asked to write a four-line poem on the theme the prompt presented, as well as to use poetic stylistic elements such as rhyme, alliteration, and line breaks. Originally 200 poems were collected, but 14 were removed for plagiarism. Not all poems are exactly four lines long. Despite this, we kept and analyzed all poems that were not plagiarized.

The 10 metaphorical prompts used were:

* Anger is wood
* Compassion is blood
* Death is a rose
* God is a breath
* Grace is a garden
* Hate is a mist
* Hope is a ship
* Immortality is a room
* Peace is a rock
* Surrender is a book

Two evaluators looked at all poems and marked whether or not they believed the poem successfully communicated the idea of the metaphorical prompt. The evaluators had a 97% agreement rate and 24% of all poems were marked as success by both evaluators. Additionally for poems marked as unsuccessful, evaluators marked which of 5 different ways a poem did not communicate the idea of the metaphorical prompt:

* off topic
* no connection
* attributional connection
* offset connection
* incoherent connection

The evaluators had a 75% agreement rate for this categorization. Because evaluators could disagree, some poems are marked as being in two categories. For a given poem, if only one category is marked this means the evaluators agreed.

## Examples

This is a poem that *successfully* writes on the theme anger is wood. It relates several aspects of wood, such as growing into a tree and becoming hard to move due to its roots, to aspects we can associate with anger.

```
the anger grew, like a tree
this large, immovable object had taken root
casting shade on even the happiest parts of my life
I could let it consume me, or cut it down 
```

This is a poem that *unsucessfully* writes on the theme anger is wood. In this case, there is no explicit mention or relation to wood; this poem is only about anger.

```
My anger is solid and vast
The ghosts of my present, the ghosts of my past
I can't break through the tunnel of time
My anger is vicious, my anger is mine
```

This is a poem that *successfully* writes on the theme surrender is a book.

```
Surrender is a book
it's pages contain paragraphs of regret
chapters of inaction
an epilogue of defeat
```

This is a poem that *unsuccessfully* writes on the theme surrender is a book. Note that it relates surrender and book by suggesting that one should 'surrender to a book, as opposed to finding ways in which surrender and book might be similar.

```
When life gets tough
And you just want to get away
Grab a book and a blanket
And surrender for the day"
```

## Citation

For more information about the experiment, please consult the paper [Challenges in finding metaphorical connections](http://www.aclweb.org/anthology/W18-0901) by Katy Gero and Lydia Chilton.

```
@inproceedings{gero2018challenges,
  title={Challenges in Finding Metaphorical Connections},
  author={Gero, Katy and Chilton, Lydia},
  booktitle={Proceedings of the Workshop on Figurative Language Processing},
  pages={1--6},
  year={2018}
}
```
