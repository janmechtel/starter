---
layout: blog
category: blog
published: false
title: 'How to visualize 100,000 learners'
---
## EIDU or why do I need to visualize 100,000 people

Joing [EIDU](https://www.eidu.com) in early 2022 we served around 25,000 learners. An impressive number at the time. Less than 12 months later we crossed 100,000 active learners for the first time.

I saw the number quite often and 100,000 is not a particularily large number, but equally often I wondered whether the aggregation made the number so much less emotional. 100,000 pre-school kids would actually be quite a sight, if you put them all in one place.

But maybe we could at least represent them individually in one place? 

## Unit Representation
- **pixel** - 1 pixel for each child? 2560 x 1440 screen resolution would make a total 3,686,400 
- **real photo** - That would require consent and is quite private information. But maybe with opt-in?
- **Avatar** - Being an avid gamer i thought about using avatar and I found the great library [Dicebear](https://www.dicebear.com/) to generate them.
- **AI generated photo** - With stable diffusion i thought it's possible to generate pictures of non-existant children. 

## Layout Inspiration

First I search inspiration for some layouts. The one I liked best is https://justifiedgrid.com/ but also the one where you make a up a big picture from many small ones is quite nice.

![Screenshot_20230526_234803.png]({{site.baseurl}}/media/Screenshot_20230526_234803.png)
![pictures of people in different layouts]({{site.baseurl}}/media/Screenshot_20230526_234803.png)

## Pixplot

Then I fell in love with [Pixplot](https://dhlab.yale.edu/projects/pixplot/) which in turn was inspired by the amazing  [Google Arts Experiments TSNE viewer](https://artsexperiments.withgoogle.com/tsnemap/)

Here is my current result using Pixplot to visualize ~4,000 children. Let's see when this experiment reaches the next stage.

![Screenshot_20230526_235523.png]({{site.baseurl}}/media/Screenshot_20230526_235523.png)

P.S.: As of writing this EIDU already grew to >160,000 learners.
