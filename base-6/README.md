# Heximal

I think our decimal number system, is not the most optimal for our [subitizing](https://en.wikipedia.org/wiki/Subitizing) minds to handle.

Yes, we have 10 fingers, but you can learn to use those fingers to count in different bases.

I think the decimal model has made it more difficult to understand large numbers, and the only reason we hold onto it is out of tradition.

In attempt to understand which base would be better, I did analysis on the *popularity* of numbers.

Presumibly, the popularity of number, should correspond with its order.

Sure, a few numbers can be more favorable to others, considered popular or lucky, but those would be considered anomalies. We'd expect most numbers should continue to be in order.

Why should 10 be more popular than 9?

Why should 100 be more popular than 99?

Why should 1000 be more popular than 999?

My hypothesis is that people will understand numbers better if they were closer to [subitizing limits](https://en.wikipedia.org/wiki/Subitizing).

## Research

I looked up number popularity on [Google Ngram](https://books.google.com/ngrams)

[Here are the results](stats.md)

Notice that 10 appears in the position of the number 6.

Intrigued by this, I wondered if this effect can be seen with other multiples.

And indeed, I found that 10 usually appears close to position 6 in [all multiples that I've tried](stats-multiples.md).

I looked, it even works for [numbers spelled out in english](stats-english.md).

It's as if people naturally want to associate "10" with the sixed number position.

## Interpretation

This was interesting to me, but not the answer I was originally looking for.

Human subitizing limits get up to around the number 4. So I thought base 4 or 5 would be most "natural". Indeed, historically people used [tally marks](https://en.wikipedia.org/wiki/Tally_marks), and those only went up to about 5.

But then I realized two additional factors, that swayed my opinion:

### Subitized Grouping

We are very good at counting in subitized groups. For example how many lines do you see here?:

![Sticks](sticks1.png)

Most of the time, you're not going to count each stick one at a time.

You usually group the sticks into groups of two or three, and can quickly count each group:

![Sticks](sticks2.png)

![Sticks](sticks3.png)

I feel that base 6 helps with counting in such grouped ways.

If 6 were the base, the number of sticks here would be 10. This means you can count:

2, 4, 10, 12, 14, 20, 22, 24, 30, ...

or:

3, 10, 13, 20, 23, 30, 33, 40, 43, ...

With 10s appearing so frequntly, counting by 2 or by 3 feels signficantly easier.

### Finger Counting

With ten fingers on our hands, it is easy to count up to 10.

Various alternative ways of finger counting can be created for counting with other bases, but they usually aren't as simple.

I'd want a way to be able signal a number to a friend from the distance, with no confusion.

And base 6 provides a very simple way to do this.

[View video how to count in base 6](https://www.youtube.com/watch?v=VXw40fzWeu0).

## Other bases?

### Why not base 12?

The dozenal society have been promoting base 12 since 1944, and has been collecting donations for their effort to spread the word.

But as I've shown earlier, the popularity of number 10 is significantly smaller, closer to number 4 to 6.

Using base 6, we get most of the benefits of base 12, in addition to matching the natural popularity of the number.

Finally, finger counting is much easier in base 6 than base 12, as shown above.

### Why not base 5?

Looking at the popularity of base 10, sometimes it went lower than base 6, towards base 4 and 5.

Indeed, base 5 appears a lot in nature:

* Starfish, some fruit, and most animals fingers have 5 appendages.
* Sqrt(5) appears in the formula for the golden ratio. The golden ratio appears in the pentagram and pentagon.
* Per the [Abel-Ruffini Theorem](https://en.wikipedia.org/wiki/Abel%E2%80%93Ruffini_theorem), a "quadratic-like formula" is not possible for any powers at the 5th root or higher. So 5 restarting to 10, makes sense as 4 being the maximal root.

However, base 5 is pretty inconvenient to use.

* 1 / 2 in base 5 = 0.22222222...
* 1 / 3 in base 5 = 0.13131313...
* 1 / 4 in base 5 = 0.11111111...
* 1 / 5 in base 5 = 0.1

Compare to base 6:

* 1 / 2 in base 6 = 0.3
* 1 / 3 in base 6 = 0.2
* 1 / 4 in base 6 = 0.13
* 1 / 5 in base 6 = 0.11111111...
* 1 / 6 in base 6 = 0.1

The 0.11111... is appears in all integer bases, and is impossible to get rid of.

Base 6 looks much more attractive here, due to all of the subitizable numbers (2, 3, 4), having a short decimal point.

To match base 5's Golden Ratio, the [Plastic number](https://en.wikipedia.org/wiki/Plastic_number) calculation:

![Plastic calculation decimal](plastic_dec.svg)

Looks a bit better in base 6:

![Plastic calculation heximal](plastic_hex.svg)

To match the starfish and animals having 5 appendages, most insects have 6 legs. :)

In any case, 5 is a factor of the decimal base. If there were any benefit to using it, we would have noticed it by now.

## Conclusion

From my research it sounds like humans are best at working with the heximal number system.

I hence will be trying to promote the heximal number system to others.

I will start by learning the multiplication table in using the heximal base system. I've already [created a quizlet page to start learning](https://quizlet.com/305883769/multiplying-base-6-result-up-to-100-flash-cards/).

As I learn new things about the heximal number system, I will write them here.

## See also

* [I built an Analog clock webpage](clock.htm) ([Here is a screenshot](clock.png))
* [Heximal Times Table](times-table.md)
* [Here's a list of various constants and sequences in Heximal](list-of-numbers)

## External Links

* [Base 6 Wiki](https://en.wikipedia.org/wiki/Senary).
* [Redefining basic units of measurement in base 6](http://shacktoms.org/base-six/base-six.htm).
* [Base 6 - The Base Not Taken](http://wiki.c2.com/?BaseSix)
