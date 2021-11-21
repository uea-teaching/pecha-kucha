---
title: Dave Greenwood
subtitle: Pecha Kucha
slideNumber: false
width: 1280
height: 720
margin: 0.4
title-slide-attributes:
  data-background-image: assets/HAL.jpg
---

# {data-background-image=assets/apostles.jpg}

::: {style="text-align: right;padding-right:0.5em;font-size:3em"}
Hello, world!
:::

::: notes
You might have guessed, I have not always been a computer scientist.
In the past, I travelled the world with a camera taking photographs for design and advertising clients.
:::

## {data-background-image=assets/face_intervals.jpg}

::: notes
Like all of us, I've also travelled through time.
My interest in cameras and images transitioned into an interest in computers and computer vision.
I became particularly interested in how computers understand pictures of people.
:::

## {data-background-image=assets/head_scan.jpg}

::: notes
Before coming to the University to lecture, I worked both for Disney Research and Facebook Reality labs.
Our focus was on Digital Humans - how we can represent ourselves in a digital world.
I still worked with cameras and images, objectively, for data collection.
:::

# Computer Science {data-background-image=assets/ENIAC.jpg}

::: notes
ENIAC was the first electronic, Turing-complete device, and performed ballistics trajectory calculations for the United States Army.
:::

## Equations

::: {style="font-size:0.75em;"}

$$
X_{u, v} = s_u s_v ~ \sum_{x=0}^{N-1} \sum_{y=0}^{N-1} I(x, y) ~
    cos \left[ \frac{\pi u (2x + 1)}{2N} \right]
    cos \left[ \frac{\pi v (2y + 1)}{2N} \right]
$$

:::

## Source code

```{.python data-line-numbers="3-5"}
class Net(nn.Module):
    def __init__(self):
        super(Net, self).__init__()
        self.conv1 = nn.Conv2d(1, 32, 3, 1)
        self.conv2 = nn.Conv2d(32, 64, 3, 1)
        self.dropout1 = nn.Dropout(0.25)
        self.dropout2 = nn.Dropout(0.5)
        self.fc1 = nn.Linear(9216, 128)
        self.fc2 = nn.Linear(128, 10)
```

::: notes
This is the constructor for a PyTorch model to classify hand written digits.
It uses one of the fundamental components of neural networks: convolutional layers.
I have highlighted the code for the convolutional layers.
:::

# Computer Vison {data-background-image=assets/matrix.gif}

## {data-background-video=assets/faces_not_real.mp4 data-background-video-loop="loop"}

# {data-background-image=assets/eclipse.jpg}

## {data-background-image=assets/dice.jpg}

::: notes
For cognitive load it requires 500% more effort to count than to recognise.
The greatest number of objects we can recognise is SIX.
Our energy conserving brains weigh up the effort to count or ignore - and choose ignore...
:::

## {data-background-image=assets/columbia_slide.png}

::: notes
Due to redundancy effect in working memory: speaking while having sentences on screen results in low recollection by audience.
The redundancy principle (or redundancy effect) suggests that redundant material interferes with rather than facilitates learning.
The Redundancy Principle in Multimedia Learning (2014) John Sweller. Richard E. Mayer
:::

## {data-background-image=assets/columbia_2003.jpg}

::: notes
Due to redundancy effect in working memory: speaking while having sentences on screen results in low recollection by audience.
The redundancy principle (or redundancy effect) suggests that redundant material interferes with rather than facilitates learning.
From the book - The Redundancy Principle in Multimedia Learning (2014) John Sweller. Richard E. Mayer
:::

# Distribution

All code available [here](https://github.com/uea-teaching/pecha-kucha).

::: notes
To wrap up the presentation, I will mention that I did NOT use PowerPoint.
I can't use powerpoint - the amount of buttons fills me with anxiety at hte very sight of them.
In fact, powerpoint fails to provide the tools I need - it does not have a means for showing source code, or a standard way of showing equations.
I prefer to write my material in a plain text format that anyone can view or edit.
I have made all my code available at the link so you can see for yourself.
:::
