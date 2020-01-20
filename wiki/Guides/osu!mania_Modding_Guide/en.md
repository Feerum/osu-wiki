# osu!mania Modding Guide

This guide/tutorial will go through how to mod a beatmap in osu!mania. Modding is a relatively simple process and with enough practice, can lead to becoming a Beatmap Nominator.
So let's start!

## Part 1. Where to start? (Modding Page Layout)

*If familiar with the modding page layout and what each button does, please move to Part 2.*

To start modding a map, pick a beatmap from the [pending beatmap listing](https://osu.ppy.sh/beatmapsets?m=3&s=pending) or ask any osu!mania mappers if they have anything they want to rank, and when on the Beatmap page, press on Discussion. This will open the Discussion page, where modding takes place.

The discussion page is filled with a lot of buttons, which are all explained below:

First, let's start with the following row of buttons:
![](Diffs.jpg)
- **[xK] (Difficulty Name)** - This opens a list of difficulties to choose from to mod. The x represents the amount of columns the map has.
- **Mine** - Only your (the modder) posts will be displayed.
- **Notes** - Only notes the mapper left on the discussion page will be displayed.
- **Resolved** - Only resolved issues will be displayed.
- **Pending** - Only pending issues will be displayed.
- **Praises** - Only praises will be displayed.
- **All** - Everything will be displayed.
- **Filter by user** - Only posts by a specific user will be displayed.

Furthermore there are 3 buttons lower down on the page:
![](HypeNomi.jpg)
- **Hype Beatmap** - Hypes are used as a way to promote maps and signal interest in seeing the map ranked. Hypes are required to move a beatmap into qualified as before a Beatmap Nominator can nominate a beatmap, it must reach at least 5 Hype. Each user can only hype a beatmap once, and hypes are given out every 7 days, up to a maximum of 10 hype.
- **Watch/Unwatch** - Watching a map will cause notifications to appear whenever something happens in the beatmap discussion. Should you already follow a beatmap discussion, you can also unfollow it by clicking on the button again.
- **Beatmap Page** - Goes back to the beatmap information and scores page.

Beatmap Nominators/Moderators get additional buttons, but these are not important for this tutorial.

Before posting, make sure the correct tab is selected based on what changes are going to be suggested. A total of 3 different options are available:
- **General (All difficulties)** - Posts here will be displayed for all difficulties, which is usually reserved for mentioning things which affect the complete mapset, such as timing point suggestions or metadata. Hyping a beatmap also occurs here.
- **General (This difficulty)** - Posts here will be only visible on the difficulty set above. Posts here reflect the complete difficulty instead of singular points, such as feedback on the complete difficulty or spread problems with previous/following difficulties.
- **Timeline** - This is where the bulk of modding occurs. All problems/suggestions for sections or notes in the difficulty chosen above belong here. Copy/pasting a timestamp from the editor to the discussion page is required before making a post, so the mapper knows what section is being discussed.

Writing something into the text field on the modding discussion page shows three more general buttons, along with two situational buttons depending on what section is chosen. These are important for how important an issue is. Here is a quick explaination of each before going into more detail below:

#### General
- **Praise** - Allows the modder to point out parts of the map they enjoyed using a timestamp or the entire difficulty if they desire.
- **Suggestion** - Marks a post as a normal suggestion.
- **Problem** - Marks a post as a problem.

#### Situational
- **Hype** - Only visible when on the General (All difficulties) section of the modding discussion page. This costs 1 hype and increases the hype of the map by 1. A map needs 5 hype before it can be checked by Beatmap Nominators.
- **Note** - Only visible if you are the owner of the beatmap. This will leave public notes for people to see, mainly used to point out anything that seems odd, or any future plans with the set.

When a post is marked as a **suggestion** it is for changes that are subjective and not unrankable. Pattern changes, specific note placements, and other changes which could improve the map. This is mainly used if the modder finds certain patterns uncomfortable, or finds a note that seems out of place but isn't sure.

When a post is marked as a **problem** it is for changes that are required for the rankability of the beatmap and are objectively needed for ranked. Do not post subjective changes as a problem, only when something clearly violates the Ranking Criteria or is extremely unfitting, such as SVs on a section where nothing happens which could justify them, unsnapped notes, or completely mistimed BPM.

You can visit the [Beatmap Discussion](https://osu.ppy.sh/help/wiki/Beatmap_Discussion) page for more details.

## Part 2. Let's start modding!
To start modding, open the difficulty of a beatmap in the editor. Then choose **the same** difficulty from the drop-down menu on the beatmap discussion page, to be sure posts go to the correct difficulty.

**Before we start**: Not all points brought up below have to be covered in each mod. If unsure with something, such as metadata or timing, leave it out. However, it is good to practice to learn how to cover all of the points below, as it is required to have experience in all to become a Beatmap Nominator. Even if mistakes are made, experience and learning is still gained from it.

### 2.1 The AiMod
The best suggestion when entering a beatmap difficulty for the first time is **checking the AiMod**.

This can be done by pressing on “File” on the top-left corner of the screen and choosing “Open AiMod”. Alternatively, simply press CTRL+Shift+A, which also opens the AiMod.

The AiMod lists issues with the beatmap as a whole as well as the specific difficulty open. It displays issues in two categories. **Warning** and **Error**. A warning will be displayed if there is a minor issue, something that can be easily fixed. However, some of these are not against the Ranking Criteria and are not an issue.
For example, “Kiai Time is toggled on for less than 15 seconds.” will show up ocassionally as the section the kiai covers (which is usually a chorus) can be less than 15 seconds overall, which is not against any ranking criteria. 
Some things that show up as a **warning** are against the Ranking Criteria however, for example, unsnapped notes.
Collating all of the important issues that AiMod raises into one **General (This difficulty)** post is a good place to start. If there are none, move on.

### 2.2 The Timing
After checking the AiMod, **checking the timing** of a beatmap . A correct timing is mandatory for a beatmap to get ranked, as well as for general playability purposes.

To check that a beatmap is correctly timed, first you check if the BPM is correct. Mostly this isn't an issue, but it's good to check nevertheless. The best way to check this is by checking if the beats of the song land on a white beat line consistently and don't drift either early or late. Increasing the hitsound volume and setting the playback rate of the map slower can help with this. If the beats of the song drift early, then decrease the bpm, otherwise if they drift late, then increase the bpm until they match.

Next, check the offset. Most timing problems occur when setting the offset. An offset which is wrong for more than 5ms is unrankable, so it's important to make sure it's accurate. This is done by making sure the main beat of the song lines up with the main white line exactly, and increase the offset if the song is early, and decrease if the song is late.

The offset is the timing points position. It should **always**  start on the very first beat of the map. If this is not the case, point it out as problem on the beatmap discussion. However, there are special cases where it does not start at the very first beat, for example it can start in the minus, if it is required for the storyboard.

### 2.3 The Metadata
**Cecking the Metadata of the beatmap** is important for beatmap rankability, however because of its awkwardness, it often gets skipped. The “Metadata” is conatained in the “General” Tab of the “Song Setup” window, which includes, Song Title, Artist, etc.

It is usually skipped due to the effort required finding **official sources** for a proof of the Metadata, one of the main issues being when the artist and title are written in a different language, such as Japanese, Korean or Russian. It’s not required to understand other languages for this, just as long as the Metadata is exactly the same as in the official source on the internet.

Whilst this part can be skipped, it can be a huge help for the mapper and BNs if the Metadata is checked and a post is made about it. Even when the Metadata is already correct, posting good sources for confirmation also helps.

If unsure of a legitimate source for metadata, the [Metadata Heap](https://discord.gg/9Y4EdyM) discord is open for such questions.

### 2.4 The Song Setup
Whilst in the **Song Setup Screen**, let's go through the other tabs.

On the **Difficulty** page, check if the OD/HP for the beatmap follow the **official guidelines** from the Ranking Criteria. Keep in mind that Guidelines have to be followed or the mapper needs to explain why they have chosen something different. Point it out as a problem if the OD/HP does does not follow the Ranking Criteria!

Besides that, make sure the HP/OD used in the beatmap are appropriate for its difficulty / patterning and match up with the rest of the set. If the beatmap uses a lot of long notes for example, the OD rate should be kept rather low.

The **Audio** and **Colors** pages are not that important as a modder.

Moving on to **Design.** This is only important if the beatmap has a storyboard. Should the map have one, make sure that **Widescreen Support** is ticked. If the storyboard has a lot of flashing lights, it also required to have **Display Epilepsy Warning** enabled, so whenever the map gets played by a user, they first see this warning.

The last page is the **Advanced Section**. This one is also not important as a modder.

### 2.5 Spread Modding
The next important thing which should always be checked is the overall spread of the beatmap.

But first things first: **Don't ever use Star Rating as a spread measure**. Do not take that into account. The Star Rating is pretty broken in osu!mania. It takes mostly the note density as measure. Means: More Notes = More Star Rating. Especially on higher BPM it can happen really fast that the difficulties skip from 3* to almost 5* because of the note density, while it’s still perfectly fine according to the Ranking Criteria.

So remember: **Do not use Star Rating as a measure for spread**.

Alright. Now that's clarified, how exactly do you check the spread?

The best way is to go into the editor of one difficulty of the beatmap you are checking right now, and then going to “File” in the top-left corner, to “Open Difficulty…” and then select “For Reference”. Then you select the next difficulty in the spread. If you are checking an Easy, open the Normal. If Normal, open the Hard and so on. Now you have the next difficulty shown in the editor right next to the one you are checking right now.

All you have to do now is compare the pattern difficulty between these two beatmaps. Let’s look at an example:

You are checking an **Easy difficulty** of a beatmap of 180 BPM. The Easy difficulty consists mostly of 1/1 pattern with occasional 1/2 patterns and rare jump usage.

In the **Normal difficulty** you can spot several 1/4 patterns with a length of 5 Notes. You spot them especially in parts which were mapped in simple 1/1 pattern in the Easy Difficulty.

You can imagine that the jump from 1/1 to 1/4 is pretty high in several places, which is not alright. The difficulty is increasing way too quickly because you can’t expect from a beginner which just learned the game to play different types of 1/4 patterns.

You can point this out as a problem in the “General (This difficulty)” tab on the beatmap discussion page. First of all you have to state the problem, then you give the mapper several examples in the beatmap by posting the timestamps, explaining that the spread is not acceptable. Finally you give the mapper a solution. Either by reducing or increasing one of the difficulties, or creating another difficulty altogether if the spread is too large.

You basically do this with every difficulty in the beatmap set, taking also the ranking criteria into account.

**Note**: Should the beatmap have a length of over 5 minutes and still have several difficulties mapped, it does not have to follow any spread rules. This is also stated in the general Ranking Criteria.

### 2.6 Pattern Modding
Now we're getting into the real deal! The most important part of modding is modding the patterns of a beatmap. The patterns are the heart of every beatmap. Without them, no map.

If you are already experienced in playing osu!mania, you will have a clear advantage. You should be able to play the difficulty you are planning to mod, however **this is not required**! If you know how a pattern “feels”, you can often mod it without being able to play it, though experience from playing will definitely help.

Before you start modding patterns you should play the difficulty at least once to see what feels uncomfortable, odd or  if the beatmap has some errors somewhere. By playing the difficulty you also get a rough overview of it and how the mapper went about mapping it.

It is important to respect the mappers idea of the beatmap. You are a modder, you are there to “polish” it and point out problems, not to “re-map” the beatmap. Always keep that in mind! If you do solely disagree with a beatmap, you are free to map the song yourself.

Have you noticed something weird while playing the difficulty? Great! Then jump to the part in the editor and check it. If you are unsure about where it was, you can test play single parts of the map by pressing F5 at a certain timestamp and see if you can find it.

Next you should analyze what exactly makes the pattern weird to play. Are they just uncomfortably placed? Do they have a hand bias? Are there any jacks where they do not belong? Anchors? There are many possibilities why a pattern plays weird. Try to find out what exactly makes it weird. You can do so by maybe moving some pattern around to remove “problems”, as well as potentially adding/deleting notes. It is important that you always test play your own suggestion. You should never suggest something without knowing how it plays.

Once you are happy with it, you write your suggestion in the modding discussion. For that you first have to copy/paste the timestamp. There are two ways to do this. If you have no notes selected, copying the timestamp by pressing Ctrl-C and then Ctrl-V on the beatmap discussion page will post the time location only. If you have notes selected, copying the timestamp will post to the time location of the first note and show the mapper the highlighted notes.

After you have posted the timing, write down your suggestion. First of all you should point out what is wrong. Do it short in one sentence. Next you should write your suggestion in full. The best way is to write down every step you did to change it to the current one. Do not fear to post several extra timestamps if you have moved or deleted notes! Make it as clear as possible for the mapper what you did and describe what problem it solves. The more you do that, the better the mapper can see what you did and what were your thoughts on doing so. Let me give you a little example:

`00:52:299 - These pattern feels pretty weird while playing as there is a bias on the left hand, as well as a long anchor. You can solve that problem by moving 00:52:459 (52459|0) - this note to 3, 00:52:618 (52618|3) - this one to 2 and maybe remove 00:52:858 (52858|1) - because it causes a jack with the next hand pattern.`

As you can see. I first posted the timestamp and then i described the problem and posted a suggestion on how to fix it. It’s okay to use several timestamps. Everything that helps to fix the problem and make the pattern more comfortable to play.

Continue doing that for the entire map. As mentioned earlier, if you find something which is clearly unrankable, post it as problem instead of a suggestion so that the mapper sees he has to fix it. If you are suggesting pattern changes for several parts as shown above, do it as a suggestion.

If you plan to give a problem/suggestion for a larger section of the beatmap, use two timestamps, then you describe the problem in this section and finally you post a suggestion/problem how to solve it. An example would be:

`00:53:416 - to 00:58:682 - The usage of the 1st column here causes too many anchors which is really awkward to play alongside notes in the 2nd column. I'd suggest moving every other note (00:53:691 - , 00:53:966 - , 00:54:241 - , etc.) to a different column to alleviate the left hand bias in the map.`

There are many ways how you can mod a beatmap. The more you will mod in the future, the more you will find out about how it works and you will find your own modding style!

### 2.7 Hitsound Modding
Another important part of every beatmap are the hitsounds. If the beatmap you are modding has no hitsounds and the mapper still plans to add them, all you can do is give a friendly hint that they are required for ranking a beatmap.

If the beatmap does have hitsounds, you can of course mod them! The first thing you do is get an overview of the mappers idea on how the beatmap should be hitsounded. In mania we have an advantage over other game modes as you can display the used hitsounds on the notes! To do so you go on “View” on the top left corner and then you choose “Show Sample Name”. Now you can see all used samples shown on the notes! Pretty neat, isn’t it? Always use this to mod the hitsounds!

So what to do now? **Check if the hitsounds are audible enough**. Every beatmap must have audible hitsounds. Ideally you will have the same volume set to Music as you do Effect in the general volume settings. Then you listen through the difficulty on normal playback rate and see if you can hear the hitsounds. If not, make a problem post in the “General (This difficulty)” section and tell the mapper. Additionally you can check how much the mapper has to increase the volume by simply testing it by yourself! The easiest way to do this is by going to Timing and Pressing the Timing Setup Panel (or Pressing F6), and selecting the timestamp which is the first one behind the current timing point (e.g. selecting 00:43:392 - , if the sound is quiet at 00:43:495 - ,). From here, go to Audio, and adjust the volume until the hitsounds are audible enough, and suggest the new value to the mapper.

Next you can go through the map and **seek out hitsound inconsistencies**. See if there is any pattern which has a wrong or missing hitsound. If this is the case, post it as suggestion! You can’t be sure if the mapper maybe left it out intentionally, that’s why you don’t post that as a problem. Little hitsound errors are also not unrankable. Copy the timestamp with the note and tell the mapper what is wrong, just like pattern modding. First you post the timestamp, then you point out the problem and a suggestion how to solve it. It might sound redundant for hitsounds, but it's better to be on the safe side! It also looks more professional.

If you see that the difficulty has really a lot of hitsound problems, **do not point them all out**! Make one bigger, general post as a problem in the same section and tell the mapper to look once again through their hitsounds. Preferably point out 2-3 timestamps to show where and tell that the same problem appears again later on.

You are not there to hitsound the beatmap for the Mapper. The Mapper has to ensure they are correct, you can just help him by pointing it out!

## 3. Advanced/Handy Tips
- **Do not exclusively make “Move/Add or Delete” suggestions!**
    - These suggestions are nothing bad. They also can help to improve a mapset. But they should never Make up the majority in ones modding. Try to find a good mix of “Move/Add or Delete” suggestions and other. Doing only “Move to X” “Add here” “Delete” suggestions lets the modding seem very unprofessional. This is especially important when aiming for becoming a Beatmap Nominator.
- **Mod different key modes!**
    - Try not to focus on only one key mode. Many modders begin with 4K because it is the most played key mode and most beatmaps are for 4K, but there are also mappers for 5K, 6K, 7K, 8K and 9K, and they often have trouble finding modders. It may also give an advantage in becoming a Beatmap Nominator in future! Modders for higher key modes are very much in demand!
- **Check how other people mod!**
    - There’s nothing bad about looking at how other people do it. Go into the discussion from some recently ranked beatmaps and check them out. Especially mods from Beatmap Nominators are worth taking a look at! They are usually very experienced in modding and can help  in getting a better understanding of formatting / style.
- **Editor usage (functions not everyone might know)**
    - **Open for Reference**: Opens a second difficulty to compare with the current one. This function can be accessed by clicking on "File -> Open Difficulty -> For Reference" and then click on the difficulty to compare.
    - **Show Sample Name**: Shows the hitsound names on the notes. This function can be accessed by clicking on “View -> Show Sample Name”. This does show the default W/F/C samples and custom sample names. Works also with the reference difficulty.

## 4. Useful Links
- **[General Ranking Criteria](https://osu.ppy.sh/help/wiki/Ranking_Criteria)**
- **[osu!mania Ranking Criteria](https://osu.ppy.sh/help/wiki/Ranking_Criteria/osu!mania)**
- **[Naxess' Mapset Verifier (Modding Tool)](https://github.com/Naxesss/MapsetVerifier)**
- **[Evening's SV Crash Course](https://github.com/Eve-ning/SV-Crash-Course-LaTeX/blob/master/builds/11082018.pdf)**
