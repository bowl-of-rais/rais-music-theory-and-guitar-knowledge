[Major Scales](Major%20Scales.md)

[Minor Scales](Minor%20Scales.md)

[Chromatic Scale](Chromatic%20Scale.md)

[Pentatonic Scales](Pentatonic%20Scales.md)

[Scales on the Guitar](Scales%20on%20the%20Guitar.md)

----

## What are scales and keys?

In short, both a scale and a key tell us a set of notes that 'make sense together', or are usually used in the same piece of (Western) music. Scales usually refer to an ordered version of that set. 

> Tonality (from "Tonic") or key: Music which uses the notes of a particular scale is said to be "in the key of" that scale or in the tonality of that scale. (Berlin, Sclater, Sinclair, 2006) 

>Scale: A **particular arrangement** of pitches that has some practical use in music. THe relationship of the pitches to one another gives a scale its characteristic quality.
>*- Fretboard Mastery (Troy Stetina)*


## Scales as a sequence of steps

One way of thinking about scales is to see them as a sequence of notes with a certain distance in between - mostly whole and half steps. The specific scale is then defined by the **root note**, i.e. the note on which we start to build our sequence, and the type of scale, i.e. what the sequence of steps look like.

For instance, the step sequence of any major scale looks like this:
$$
	1 - 1 - \frac{1}{2} - 1 - 1 - 1 - \frac{1}{2}
$$
So, if we want to figure out the notes of the G major scale, we just have to start at G and find the following notes according to the sequence. We move a whole step up from the G to A, then another whole step up to B, then a half step up to C, and so on. The result looks like this:

```vextab
tabstave notation=true tablature=false
notes G-A-B/4 C/5 | D-E-F#-G/5
```

The sequence for (natural) minor scales is:
$$
	1 - \frac{1}{2} - 1 - 1 - \frac{1}{2} - 1 - 1
$$
As an example, here is the E minor scale:

```vextab
tabstave notation=true tablature=false
notes E-F#-G-A/4 | B/4 C-D-E/5
```

There are however different variants of minor scales, see [Minor Scales](Minor%20Scales.md).


## Relationship between Major and Minor Scales

The choice of using G major and E minor as example scales might seem random. And yes, G major was kind of a random choice, but not E minor - the two scales are actually related. 

Both scales use the same notes, they just start the sequence on different notes. They are **relative keys**.

As a rule, the **relative minor** of a major scale starts on its 6th step, while the **relative major** of a minor scale starts on its 3rd step.


## Scales and the Circle of 5ths

Now, the scale above uses all basic seven notes from the [Musical Alphabet](Musical%20Alphabet.md), with a small change: instead of F, we have F#. In fact, this idea is true for all major and minor scales: they consist of the seven basic notes, the only difference is how those are altered with accidentals.

This is another way to think of scales: instead of a sequence of steps, they can be defined by specific notes having accidentals. Those two approaches produce the same result.

To figure out what accidentals belong to a specific scale, we can use the (infamous) **circle of 5ths**. Here's an attempted breakdown:

- we have 12 major and 12 minor scales (because we have 12 notes)
- this means we have 12 sets of accidentals that are applied to the 7 basic notes to get those scales
- we can arrange those in a circle:
	- we start with no accidentals at the top
	- each step clockwise adds a #
	- each step counterclockwise adds a b
	- the two directions run into eachother at the bottom
- we now can try to find the matching root notes for the major and minor scales
- as it turns out, neighboring root notes are always the same distance apart - specificially, the [interval](../Chords%20and%20Harmonies/Intervals.md) of a perfect 5th
- this is why this is called the circle of 5ths!

![](600px-Circle_of_fifths_deluxe_4.svg.png)
