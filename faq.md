Frequently Asked Questions
==========================

Why are some features ‘locked’?
-------------------------------

We want to keep Beat Sage free for everyone, but our server costs are
high and continue to increase as more and more people use the service.
To both keep the service free and reward our loyal supporters, we are
offering some features only after we meet certain milestones of Patreon
subscribers.

What upgraded features do Patreon subscribers get?
--------------------------------------------------

Currently, Patreon subscribers get the following upgrades:

- For _Disciples_, **2x max level length** (up to 20 minutes)
- For _Sages_, **3x max level length** (up to 30 minutes)
- For _Gurus_, **3x max level length**, _and_ **immediate access to 360 Levels**!

Note that these may change over time. Stay tuned!

How do I activate my Patreon upgrades?
--------------------------------------

To activate these features, follow these three easy steps:

1. [Join our Discord server](https://discord.beatsage.com)
1. [Link your Discord account to your Patreon](https://www.patreon.com/settings/apps)
1. Activate upgrades via Step 0 above

If you have followed all of these steps and your upgrades are not working, please try clearing your cookies for beatsage.com ([instructions](https://www.lifewire.com/clear-cookies-for-one-site-4587347)). If that does not fix the issue, please reach out by DMing a dev on Discord or [directly messaging us on Patreon](https://www.patreon.com/messages)!

Do I have to be an active subscriber to receive the upgrades?
-------------------------------------------------------------

Yes, your Patreon subscription must be active to receive the upgrades.

Will Beat Sage always be free?
------------------------------

We would **strongly** prefer to keep Beat Sage free and open to the
public as opposed to charging per song or having subscription fees.
However, we are only able to keep Beat Sage freely available if our
level of Patreon support meets our server costs. If you like Beat Sage
and have the means, please consider [supporting us on
Patreon](https://www.patreon.com/beatsage).

What will my Patreon support be used for?
-----------------------------------------

In order, Patreon support will be used to (1) offset server costs, (2)
develop the features promised for our subscriber milestones, (3) improve
the overall quality of the Beat Sage AI, and (4) fund design and
development of speculative features for Beat Sage. Regarding (4), we
have some exciting ideas for where to take Beat Sage in the future.
Among these ideas are things like integrating Beat Sage directly into VR
headsets, building a leaderboard system, and adding support for other VR
rhythm games. If you would like to see any of these features, please
consider [supporting us on Patreon](https://www.patreon.com/beatsage).

Can I upload levels created by Beat Sage to beatsaver.com?
----------------------------------------------------------

You may upload your favorite Beat Sage maps to BeatSaver and share them with others.

Why doesn't a particular YouTube video work?
--------------------------------------------

The most common reason a particular YouTube video will not work with Beat Sage is that the video is not available in the US. Another reason is that our server has occasional difficulties communicating with YouTube. As a workaround, please try uploading an MP3!

What is the difference between ‘V2’ and ‘V2-Flow’?
--------------------------------------------------

When we built the new Beat Sage AI, we identified two different strategies for generating levels from the same neural network that produced fun but different results; we named these models "V2" and "V2-Flow". V2 will typically produce far more song events like bombs and obstacles. V2-Flow tends to produce fewer events and seems overall less creative, but it produces arrow block patterns which are typically more readable and work well for songs with fast tempos ("stream"). Feel free to experiment and choose which model fits your personal playstyle!

Will I always get the same level for a given song?
--------------------------------------------------

Beat Sage will now return a different level every time you use it. If
you don't like the first map that it produces for your song, feel free
to try it again! Note that while the block sequence will change the next
time you map the same song, the timing of the blocks will not change.

Why are some levels better than others?
---------------------------------------

While we strive for a Beat Sage AI that produces a human-quality level
for **any** song, the reality is that the current version of Beat Sage
was trained mostly on electronic music. Hence, Beat Sage will work best
for music with a strong beat, and may completely fail on other genres
such as rock or vocal-heavy music. We encourage you to try out many
songs from different genres, and please give us feedback by slashing the
purple block above if you are unsatisfied! Your comments will help us
improve our AI.

Why are you not offering an ‘easy’ mode?
----------------------------------------

While it may seem highly unusual, the sparsity of blocks in easier Beat
Saber difficulties is actually **more** difficult for our AI to handle.
In the future, we may solve this problem, and in that case we will offer
the Easy mode.

Someone tried to sell me a map that I think was made with Beat Sage, what do I do?
----------------------------------------------------------------------------------

We were disappointed to hear reports about this, so we created a
verification tool that can actually infer if a song was created with
Beat Sage versus a human-made map! You can check it out here:
[verify.beatsage.com](https://verify.beatsage.com). We hope this can
help protect folks from feeling helpless if this happens!

How does Beat Sage work?
------------------------

Beat Sage uses two neural networks to map an audio file into a plausible
Beat Saber level. These neural networks were trained on Beat Saber
levels created by humans. The first neural network listens to the audio
and predicts at what points in time blocks should be placed. The second
neural network looks at the predicted timings and maps each to a
timestamp to a block type (e.g. red up, blue down, red up + blue down).
If you want to learn more, you can read the [paper for Dance Dance
Convolution](https://arxiv.org/pdf/1703.06891.pdf), an earlier system
Chris built which is nearly identical in architecture to Beat Sage.

Why does the BPM say 120 for every song?
----------------------------------------

Beat Sage doesn’t reason about beats the same way humans do and as such
does not know the tempo for a given song. The generated level will not
be affected by this BPM value.

Why are some videos give me an error saying “Sorry, we couldn’t access that video”?
-----------------------------------------------------------------------------------

If a song is not available in the United States, our server will not be
able to process it because we cannot access it. As an alternative, you may upload an MP3 of the same song.

I enabled a song event but there were none in the level, what gives?
--------------------------------------------------------------------

By enabling song events (e.g. bombs), you simply gave the Beat Sage AI
the **option** to add these events to the generated level. Beat Sage
will sometimes choose to ignore this power and there's little us humans
can do to convince it otherwise!

Can I share videos of myself playing Beat Sage?
-----------------------------------------------

You are absolutely welcome (and encouraged) to share footage of you playing Beat Sage maps anywhere (YouTube, Twitch, etc.) and share on any social channels (Twitter, Instagram, etc.)! If you share on Twitter, tag [@BeatSage_AI](https://twitter.com/beatsage_ai) so we can retweet!

Where should I direct my comments, suggestions, or feedback?
------------------------------------------------------------

If you have feedback (positive or negative) on an individual song,
please give us feedback by slashing the purple block above. If you have
general feedback, please let us know by posting in the \#feedback
channel on [our Discord](https://discord.beatsage.com) or posting on
[our subreddit](https://www.reddit.com/r/beatsage/)!

Is Beat Sage an official service?
---------------------------------

Beat Sage was created by two enthusiastic users of Beat Saber, but is
not in any way affiliated with Beat Saber (the game), or Beat Games (the
company that works on it).

Can I build other clients and game mods which use Beat Sage?
------------------------------------------------------------

We are thrilled that many of you have expressed interest in building software which uses Beat Sage! We ask that you please contact us first on Discord so that we can make sure the application you have in mind agrees with our overall vision for Beat Sage. Since we aren't yet officially supporting an API, we reserve the right to modify our backend at any time which may break your 3rd-party application.
