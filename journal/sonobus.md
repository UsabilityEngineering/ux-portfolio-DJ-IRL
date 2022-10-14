<h1>Better Late Than Never</h1>
<h2> Remote Work for Musicians
c/o Avery Pound</h2>

I am half of the musical duo **iO**, with my friend Cooper. We started making music together in 2010. 
For much of our career we have lived in the same city, often in the same house. 
This made playing and recording music easy, as we could meet up often in real life.
Currently, there are 140 miles between us, and we meet up to play music more consistently than 
when we lived together. We meet remotely, to play what I carefully describe as *pseudo-live* music. 

<h3>Music and Latency ⏰ </h3>
*Latency* is the time is takes for some data to get from a source to its destination. 
In an average-to-small room, the latency from when a clap occurs and when your brain perceives the clap
is virtually nonexistent. You hear it so close to the time it happened that if someone repeats clapping
in a steady rhythm, you are able to synchronize with them and clap "on beat" along with them. 
As latency increases, the amount of time between the original clap and your perception of the sound increases. 

Imagine standing a football field away from someone. You start a steady rhythm with clapping.
The other person is attempting to clap along with you, at close to the exact same times as you are clapping.
But you don't hear them synchronizing; their claps do not align with yours. 
You yell to them "Hey! Try to clap in time with me!" They give you the thumbs up. 
You try again, and again you hear the same out-of-synch claps as before. 
Before you yell this person "What the hell is wrong with you?!" 
take a moment to realize you are experiencing *latency*!
Every step of this process takes time, and the more time you add the worse the problem gets.

1) The sound leaves your hands (you hear this almost instantly)
2) The sound hits the other person's ears (they hear it, some time after you heard it)
3) They clap, the sound leaves their hands (they hear it almost instantly, and in synch with your claps to their ears)
4) Their clap hits your ears (you hear theirs so long after yours that you halt the experiment)

Most people can detect latency between of about 15-20 milliseconds. 
Performers, musicians, and audiophiles can detect latency fine as 5-10 milliseconds. 

If you want to dive deeper into this topic, [here's a great resource](https://sonobus.net/sonobus_userguide.html#A-bit-of-Physics-Why-can’t-I-jam-with-my-friend-in-Sydney)

<h3> Better Late Than Never 💡</h3>

When there is so little room for error, one can understand why we did not seriously approach
the task of playing music live remotely (over the internet) for several years. 
Even on a good day for fast internet speeds, we can hope for a 40ms round-trip time for even basic 
requests for text to servers on the internet. Audio is infamous for being slow to read from memory and being 
incredibly CPU-intensive to process. Current average latency, even on great connections, 
far exceeds the acceptable limit of latency.
So why even bother with the idea? 

We compromised with a system of sending files back and forth, using shared cloud storage, 
and constantly updating each other via text messages or emails of what we were working on. 
This process was slow, error-prone, and allowed for long periods of work before feedback was received.
Demotivation was rampant during the years we operated like this, and a lot of work was lost.
We felt we had to admit that our best work was done in person,
and that there simply was no way around this obvious fact. 

While working in my audio program of choice, [Ableton](https://www.ableton.com/en/), I had an inkling of an idea. 
I wanted live audio as a track in my project. 
I had wanted this before, but I was inexplicably confident that I could receive live audio,
with whatever latency, and *make it work.*

<h3>We're Jammin' 🎶</h3>
After many naive approaches, we have gotten somewhat adept at the process.
We have found a handful of configurations for achieving useful results. 
I will focus on just one, used in a recent successful pseudo-live session.
The audio path is unexpectedly confusing, so I will explain it before going
into the software we use to accomplish the task.

Choosing a BPM between the two parties is vital. 
Cooper initiates the session by starting a [loop](https://en.wikipedia.org/wiki/Loop_(music)) from within his Ableton project. 
He mutes the audio on his side, and streams the audio to me. 
I then start a loop, with it synchronized to his. 
Now I can hear any music either of us make, performing in time together. 
I then gather all of this audio onto one track, and send that back to Cooper. 
Now Cooper can finally hear audio. 

While these loops stay in time, we can both make changes within our sequences 
and we will both hear those changes play in time together. 
It has it's limitations, but this is a great way for an electronic duo
to work on music remotely, and *kinda* live.

<h3>All Aboard the SonoBus 🚌</h3>
After trying a handful of competitors, we discovered SonoBus.<br> <br>
 <q>SonoBus is an easy to use application for streaming high-quality, <br>
	low-latency peer-to-peer audio between devices over the internet <br>
	or a local network.</q> - [SonoBus](https://sonobus.net) 
<br>

This program was easy to install, and came with a user-friendly wizard. 
Unexpectedly, this is a rare example of free software that runs well on 
Mac's new M-series processors. 

Upon opening the SonoBus software from within Ableton, we see this window. 

![sonobusFIrstScreen](https://user-images.githubusercontent.com/79026876/195743496-072aed65-0871-44f0-82f0-b5b936962877.jpg)


The "Press Connect button to start" is a little commanding, but informative. 
The "Please use headphones if you are using a microphone!" is a good warning. 
Cooper saw this and switched from monitoring audio on speakers to headphones. 
This reduces (hopefully eliminates) the possibility of *feedback,* a noisy and common problem.

In addition to the comforting text, there are some familiar symbols around the interface. 
From the bottom left to the bottom right, I was able to correctly assume the functionality: <br>
- microphone: this toggles muting my inputs
- some people with radiating lines: this let me toggle muting other people in the session
- metronome: useful for synchronizing projects
- 3 vertical dots: metronome settings
- red circle: the universal symbol for "record"
- file folder: this lets you access and share files from your local drive with everyone in the session
- FX: add sound effects to audio you are broadcasting 
- Out Level: Adjust and visually monitor the composite output level in decibels

--- 
![journalConnectScreen](https://user-images.githubusercontent.com/79026876/195743585-66ada5c9-61dc-48d2-af1c-d113109b1d04.jpg)

After clicking on "Connect," we see this page. 
A simple interface that does not ask much of the user. 
There's some more details in areas where you might want them, 
but 

--- 
![journalInSession](https://user-images.githubusercontent.com/79026876/195743610-a1c8c646-987a-45ab-aa91-42e339d332d5.jpg)


Such simple, and great design in some places. 
I'm a very technical person, 
I am a computer science student at Chico State. 
I will struggle with a difficult program for a long time,
tinkering and trying to get it to work exactly how I want. <br>
Cooper thinks technology often gets in the way of making music, 
and has banished many programs to the trash bin which do not
meet his high standards of usability. 

SonoBus passes all our tests, and even offered some features we were not 
seeking out, but really benefited from. 

Most importantly, it's intuitive interface meant that within a half-hour
of downloading the program on two separate operating systems 
we were jamming in rooms 140 miles apart. 

