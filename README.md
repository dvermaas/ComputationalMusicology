# Computational Musicology: Portfolio

[click here](https://dvermaas.github.io/ComputationalMusicology/) to go to the portfolio webpage.

**What is your corpus, why did you choose it, and what do you think is interesting about it?**

Synthwave (also called outrun, retrowave, or futuresynth) is an electronic music microgenre that is based predominantly on the music associated with action, science-fiction, and horror film soundtracks of the 1980s. Other influences are drawn from the decade's art and video games. Synthwave musicians often espouse nostalgia for 1980s culture and attempt to capture the era's atmosphere and celebrate it (from Wikipedia).

I chose this corpus because I am currently listening to a lot of synthwave music. I also listen to all my music on Spotify, so I can use my playlists to build my corpus up quickly. I am also currently working on a synthwave rhythm-game in unity, so exploring this corpus could also help with this side project.

I have selected the following artists, which should represent the following subgenres:

* Downtown binary: chill-synth
* Jan Hammer: soundtrack synth
* The midnight: pop/dance synth
* Home: Vaporwave
* Carpenter Brut: Hardcore-ish synth

**What are the natural groups or comparison points in your corpus and what is expected between them?**

There are five artists in the corpus, each representing a synthwave subgerne. The natural point of comparison is therefore to analyse the differences between tracks of these different artists. I intend to explore what features are the best at showing the differences between the artists, and test if training a good performing classifier on labels within the same genre is possible.

A secondary objective of this research is to see if subgenre detection is possible, which is why each artist has a different subgenre. This secondary objective is much more subjective. This is because unlike heavy metal, synthwave has much less agreed upon subgenres. I personally do not think there are very significant differences between most of these subgenres, but we will see if the data agrees with that statement. The conclusions of the secondary objective will be less objective, but I do think they will indicate if subgenre detection is likely or unlikely to be possible.

**How representative are the tracks in your corpus for the groups you want to compare?**

I will use a couple of playlists for each artist to build the corpus, making sure all artists take up an (close to) equal share of the corpus. This will ensure that all artists are equally represented. For subgenre detection representativeness is debatable. It is almost universally agreed upon that Home is one of the OG's of Vaporwave. Jan Hammer is also a very respected soundtrack artist in the scene. The other genres are probably more debatable. But the same goes for the more niche subgenres of hardcore rock, so I believe the experiment will still be compelling.

**Identify several tracks in your corpus that are either extremely typical or atypical. Why do you think that they are so typical or so strange?**

Turbo Killer by Carpenter Brut is one atypical outlier. It is by far the most intense/speedy track in the entire corpus, even by Carpenter Brut standards. I also think that Resonance from Home may be an outlier. It has very odd sounds, even for vaporwave standards, I do not think there is anything that sounds close to this track. Respirate (Downtown Binary Remix) is the final outlier in this corpus. This is obviously because it is a remix of a song not originally created by Downtown Binary, but I think it still retains the Downtown Binary style, therefore I expect it to be interesting in analysis.

**Source & Reproducibility**

The whole project uses Spotify API as the source, and by hitting the Github "Source code" button, all code used to generate all visualizations can be verified on accuracy and methodology. The compmus package can be installed like this:  "remotes::install_github('jaburgoyne/compmus')"
