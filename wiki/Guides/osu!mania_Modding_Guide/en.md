# osu!mania Modding Guide

Greetings! If you found this it must mean that you are either interested in starting to mod in osu!mania or wanting to improve your modding! Congratulations!
In this little guide/tutorial, I will show you how to mod a beatmap in osu!mania. Modding is not hard and everyone can do it.
And if you are good enough, you might even become a Beatmap Nominator!
So let's start!

## Part 1. Where to start?

*Should you have already made your first steps in modding and know which button does what you can skip this part and move on to Part 2.*

It doesn’t require much to start your modding career! Just pick a beatmap from the [pending beatmap listing](https://osu.ppy.sh/beatmapsets?m=3&s=pending) and start! If you have some osu!mania mappers as friends, then you can also ask them if they have any beatmap they plan to rank which you could mod.
Once you choose a beatmap, click on the “Discussion” button on the beatmap page and you will be sent to the discussion page, the place where you can mod a beatmap.

Once you are on the discussion page you will see a lot of buttons but don’t be scared, i will explain everything!

First, we will start with the following row of buttons:
![](https://i.imgur.com/qDpJG62.png)
- **[xK] (Difficulty Name)** - Here you can choose which difficulty you want to mod. The x represents the amount of columns the map has.
- **Mine** - Only your posts will be displayed.
- **Notes** - Only notes the mapper left on the discussion page will be displayed.
- **Resolved** - Only resolved issues will be displayed.
- **Pending** - Only pending issues will be displayed.
- **Praises** - Only praises will be displayed.
- **All** - Everything will be displayed.
- **Filter by user** - Here you can setup to let only posts by a specific user be displayed.

Furthermore you have 3 “Big” buttons on the page:
![](https://i.imgur.com/UJY2hrN.png)
- **Hype Beatmap** - If you like the beatmap you have modded, hype it! Hypes are required to move a beatmap into qualified. Before a Beatmap Nominator can nominate a beatmap, it must reach at least 5 Hype. You can only hype a beatmap once, and you get 1 hype every X days, up to a maximum of 10 hype.
- **Watch/Unwatch** - Here you can follow the beatmap discussion. Once you watch a beatmap, you will get notifications whenever something happens in the beatmap discussion. Should you already follow a beatmap discussion, you can also unfollow it by clicking on the button again.
- **Beatmap Page** - Takes you back to the beatmap information and scores page.

Should you become a Beatmap Nominator or Moderator, you will see more buttons, but these are currently not important for this tutorial so i will not explain them.

Before you make a post, you first have to choose where you want to post it. You can choose from 3 options:
- **General (All difficulties)** - Things you post here will be displayed for all difficulties, regardless of which one you chose in the drop down menu. This is usually reserved for mentioning things which affect the complete mapset, such as timing point suggestions or metadata. You can also hype the beatmap here!
- **General (This difficulty)** - Things you post here will be only visible on the difficulty which you have chosen above from the drop down menu. Posts here reflect the complete difficulty instead of just singular points, such as feedback on the complete difficulty or maybe spread problems with previous/following difficulties.
- **Timeline** - This is where the bulk of modding occurs. All problems/suggestions for sections or notes in the difficulty you have chosen from the drop-down menu above belong here. You are required to copy/paste the timestamp from the difficulty here before making a post, so the mapper can see where to look.

When you write something into the text field on the modding discussion page, you will be shown three more general buttons, along with two situational buttons depending on what section you're in. These are important for how important an issue is. Here is a quick explaination of each before I go into them in more detail:

#### General
- **Praise** - Here you can praise the beatmap as a whole or several parts of the beatmap by using the timestamp.
- **Suggestion** - With this your post will be marked as normal suggestion.
- **Problem** - With this your post will be marked as problem.

#### Situational
- **Hype** - This shows up when on the General (All difficulties) section of the modding discussion page. Pressing this will cost 1 hype and increase the hype of the map by 1. A map needs 5 hype before it can be checked by Beatmap Nominators.
- **Note** - This shows up when on your own beatmap. This will leave public notes for people to see, mainly used to point out anything that seems odd, or any future plans with the set.

When you mark your post as a **suggestion** you are suggesting something. Use this for changes which are not unrankable. Pattern changes, subjective changes, everything which would improve the beatmap in your eyes. Do not fear on making subjective suggestions. When you played through the beatmap and find some pattern uncomfortable, post it as suggestion!

When you mark your post as a **problem** you indicate that a change is required for the rankability of the beatmap and the change must be done. Do not post subjective changes as a problem, only when something clearly violates the Ranking Criteria or is extremely unfitting, such as SV’s on a section where nothing happens which could justify them, or unsnapped notes.

You can visit the [Beatmap Discussion](https://osu.ppy.sh/help/wiki/Beatmap_Discussion) page for more details about it!

## Part 2. Let's start modding!
Alright, after doing a lot of theory and explaining which buttons do what we can finally start with what you are here for. Modding a beatmap! For that you have to open the difficulty of a beatmap you want to mod in the editor. Then you also choose **the same** difficulty from the drop-down menu on the beatmap discussion page, to be sure you make your posts on the right difficulty!

**Before we start**: You do not have to mod all of the following points. If you are unsure with something, such as metadata or timing, leave it out. By making it worse you do not really help anyone. However, it is good to “train” your skills in all of these points. If you are aiming to become a Beatmap Nominator you should not leave out any of these points. Even if you do mistakes, you learn from them! It’s like everything in life: **Learning by doing!**

### 2.1 The AiMod
So what to do first? You can actually do whatever you want now! My suggestion when entering a beatmap difficulty for the first time is **checking the AiMod**.

This can be done by going on “File” on the top-left corner of the screen and choose “Open AiMod”. If you are a fan of hotkeys, such as I am, simply do CTRL+Shift+A, which also opens the AiMod!
The AiMod will tell you when something is wrong in the beatmap.

It displays issues in two categories. **Warning** and **Error**. A warning will be displayed if something can get fixed. But a lot of warnings can be ignored because they are actually not against the Ranking Criteria.
One of them, for example, is “Kiai Time is toggled on for less than 15 seconds.” You will find this one on many beatmaps because sometimes mapper like to use “Kiai flashes” for a special effect, means they make a little cut in the kiai time.

But it also displays unsnapped objects as a **warning** while it is clearly against the Ranking Criteria.
You should always make a general post for the difficulty if you see something in the AiMod which needs to get fixed.

### 2.2 The Timing
After checking the AiMod you can **check the timing** of a beatmap. A correct timing is mandatory for a beatmap to get ranked, even for the playability for the beatmap although the beatmap might not get ranked.

But how do i check if it’s correctly timed? First you check if the BPM is correct. Mostly this should be the case, but everyone makes mistakes. Check if the “Beats” of the map land on a white beat line. The best way to do so is increasing the hitsound volume and setting the playback rate of the map slower. Then just listen carefully if the hitsounds plays correctly with the beat! Simple, right?

Next you check the offset. Most timing problems occur when setting the offset. An offset which is wrong for more than 5ms is unrankable, which is why It should always get checked! You can basically do it the same way you are checking the BPM.

The offset is the timing points position. It should **always**  start on the very first beat of the map! If this is not the case, point it out as problem on the beatmap discussion. However, there are special cases where it does not start at the very first beat, for example it can start in the minus, if it is required for the storyboard.

### 2.3 The Meta Data
Now you can move on. The next point is also important for beatmap rankability, however because of its difficulty it often gets skipped. It’s **checking the Metadata of the beatmap**. The “Metadata” is basically the first window you can see, when you open the “Song Setup”. Everything in the “General” part belongs to the Metadata. The Artist, Title etc.

It often gets skipped because it requires effort on researching several sources on the internet, preferably **official sources**, for a proof of the Metadata. A lot of people also have problems with it when the artist and title are written in a different language, such as Japanese, Korean or Russian.

It’s not required to understand other languages for it, you should just make sure the Metadata is exactly the same as in the official source on the internet.

No one will be mad at you if you skip this part, but you can be a huge help for the mapper and BNs if you check the Metadata and make a post about it. Even when the Metadata is already correct, posting good sources for it is also helping!

### 2.4 The Song Setup
While we are in the **Song Setup**, why not stay here and check the other pages of it too?

On the “**Difficulty**” page you can check the OD/HP for the beatmap. You can check if the OD/HP for the difficulty follow the **official guidelines** from the Ranking Criteria. Keep in mind that Guidelines have to be followed or the mapper needs to explain why he does something different. Point that out as a problem should you see that it does not follow the Ranking Criteria!

Beside that, you should also check if the HP/OD used in the beatmap are appropriate for it’s difficulty. If the beatmap uses for example a lot of long notes, the OD rate should be kept rather low and vice versa.

The **Audio** and **Colors** pages are not that important for you as a modder.

Moving on to Design. This is only important if the beatmap has a storyboard. Should the map have one, make sure that **Widescreen Support** is ticked. If the storyboard has a lot of flashing lights, it also requires to tick “**Display Epilepsy Warning**”. So whenever the map gets played by a user, he first sees the warning.

The last page is the **Advanced Section**. This one is also not important for you as a modder!

### 2.5 Spread Modding
The next important thing which should always be checked is the overall spread of the beatmap.

But first things first: **Do never ever take the Star Rating as a spread measure**. Do not take that into account. The Star Rating is pretty broken in osu!mania. It takes mostly the note density as measure. Means: More Notes = More Star Rating. Especially on higher BPM it can happen really fast that the difficulties skip from 3* to almost 5* because of the note density, while it’s still perfectly fine according to the Ranking Criteria.

So remember: **Do not use Star Rating as a measure for spread**.

Alright. After that is clarified, how exactly do you check the spread now?

The best way is to go into the editor of one difficulty of the beatmap you are checking right now. Next you go to “File” in the top-left corner, to “Open Difficulty…” and then select “For Reference”. Then you select the next difficulty in the spread. If you are checking an Easy, open the Normal. If Normal, open the Hard and so on. Now you have the next difficulty shown in the editor right next to the one you are checking right now.

All you have to do now is compare the pattern difficulty between these two beatmaps. Let’s look at an example:

You are checking an **Easy difficulty** of a beatmap of 180 BPM. The Easy difficulty consists mostly of 1/1 pattern with occasional 1/2 patterns and rare jump usage.

In the **Normal difficulty** you can spot several 1/4 patterns with a length of 5 Notes. You spot them especially in parts which were mapped in simple 1/1 pattern in the Easy Difficulty.

You can imagine that the jump from 1/1 to 1/4 is pretty high in several places. Which is not alright. The difficulty is increasing way too quickly because you can’t expect from a beginner which just learned the game to play different types of 1/4 patterns.

This you have to point out as a problem in the “General (This difficulty)” tab in the beatmap discussion. First of all you have to state the problem, then you give the mapper several examples in the beatmap by posting the timestamps, explaining that the spread is not alright. Finally you give the mapper a solution. Either by “Nerf” or “Buff” one of the difficulties.

You basically do this with every difficulty in the beatmap set, taking also the ranking criteria into account.

**Note**: Should the beatmap have a length of over 5 minutes and still have several difficulties mapped, it does not have to follow any spread rules. This is also stated in the general Ranking Criteria.

### 2.6 Pattern Modding
Now we are getting to the real deal! The most important part of modding is modding the pattern of a beatmap. The pattern is the heart of every beatmap. Without them, no map.

If you are already experienced in playing osu!mania, you will have a clear advantage. You should also be able to play the difficulty you are planning to mod, however **this is not required**! If you know how a pattern “feels”, you can often mod it without being able to play it.

Before you start modding the pattern you should play the difficulty at least once to see if it feels uncomfortable, odd or has some errors somewhere. By playing the difficulty you also get a rough overview of it and how the mapper thought about mapping it.

It is important to respect the mappers idea of the beatmap. You are a modder, you are there to “polish” it and point out problems, not to “re-map” the beatmap. Always keep that in mind!

Have you noticed something weird while playing the difficulty? Great! Then jump to the part in the editor and check it. If you are unsure about where it was, you can test play single parts of the map and see if you can find it.

Next you should analyze what exactly makes the pattern weird to play. Are they just uncomfortably placed? Do they have a hand bias? Are there any jacks where they do not belong? Anchors? There are many possibilities why a pattern plays weird. Try to find out what exactly makes it weird. You can do so by maybe moving some pattern around to remove “problems”. You can also add/delete notes, important is that you always test play your own suggestion. You should never suggest something without knowing how it even plays.

Once you are happy with it, you write it down in the modding discussion. For that you first have to copy/paste the timestamp. Just CTRL+C in the editor and then CTRL+V in the modding discussion. Be Careful: If you have any notes marked somewhere else in the beatmap, it will **always** copy their timing. Make sure you post the right one!

After you have posted the timing write down your suggestion. First of all you should point out what is wrong. Do it short in one sentence. Next you should write your suggestion. The best way is to write down every step you did to change it to the current one. Do not fear to post several extra timestamps if you have moved or deleted notes! Make it as clear as possible for the mapper what you did and describe what problem it solves. The more you do that, the better the mapper can see what you did and what were your thoughts on doing so. Let me give you a little example:

`00:52:299 - These pattern feel pretty weird while playing, there is a bias on the left hand, additionally there is a long anchor. You could solve that problem by moving 00:52:459 (52459|0) - this note to 3, 00:52:618 (52618|3) - this one to 2 and maybe remove 00:52:858 (52858|1) - because it causes a jack with the next hand pattern.`

As you can see. I first posted the timestamp and then i described the problem and posted a suggestion on how to fix it. It’s okay to use several timestamps. Everything that helps to fix the problem and make the pattern more comfortable to play.

You do that basically for the entire map. As mentioned earlier, if you find something which is clearly unrankable, post it as problem so that the mapper sees he has to fix it. If you are suggesting pattern changes for several parts as above, do it as a suggestion

If you plan to give a suggestion for a larger section of the beatmap, use two timestamps. Such as “00:53:416 - to 00:58:682 - “. Then you do the same as before!

You first post the timestamps, then you describe the problem in this section and finally you post a suggestion/problem how to solve it.

There are many ways how you can mod a beatmap. The more you will mod in the future, the more you will find out about how it works and you will find your own ways of modding!

### 2.7 Hitsound Modding
Another important part of every beatmap are the hitsounds. If the beatmap you are modding has no hitsounds and the mapper still plans to add them, all you can do is give a friendly hint that they are required for ranking a beatmap.

If the beatmap does have hitsounds, you can of course mod them! The first thing you do is get an overview of the mappers idea how the beatmap should be hitsounded. In mania we have a really cool advantage above the other game modes. You can display the used hitsounds on the notes! To do so you go on “View” on the top left corner and then you choose “Show Sample Name”. Now you get all used samples shown on the notes! Pretty neat, isn’t it? Always use this to mod the hitsounds!

So what to do now? **Check if the hitsounds are audible enough**. Every beatmap must have audible hitsounds. Ideally you use “**50/50/50**” volume settings. Means master, music and effect volume on the same level. Then you listen through the difficulty on normal playback rate and see if you can hear the hitsounds. If not, make a problem post in the “General (This difficulty)” section and tell the mapper. Additionally you can check how much the mapper has to increase the volume by simply testing it by yourself!

Next you can go through the map and **seek out hitsound inconsistencies**. See if there is any pattern which has a wrong or missing hitsound. If this is the case, post it as suggestion! You can’t be sure if the mapper maybe left it out intentionally, that’s why you don’t post that as a problem. Little hitsound errors are also not unrankable. Copy the timestamp with the note and tell the mapper what is wrong. Just like the pattern modding. First you post the timestamp, then you point out the problem and a suggestion how to solve it. It might sound redundant for hitsounds, but better be on the safe side! It also looks more professional.

If you see that the difficulty has really a lot of hitsound problems, **do not point them all out**! Make one bigger post as problem in the same section and tell the mapper to look once again through their hitsounds. Preferably point out 2-3 timestamps to show where and tell that the same problem appears again later on.

You are not there to hitsound the beatmap for the Mapper. The Mapper has to ensure they are correct, you can just help him by pointing it out!

## 3. Advanced/Handy Tips
- **Do not just make “Move/Add or Delete” suggestions!**
    - These suggestions are nothing bad. They also can help to improve a mapset. But they should never Make up the majority in your modding. Try to find a good mix of “Move/Add or Delete” suggestions and other. Doing only “Move to X” “Add here” “Delete” suggestions makes your modding seem very unprofessional. This is especially important if you aim to become a Beatmap Nominator.
- **Mod different key modes!**
    - Try not to focus on only one key mode! Many modders begin with 4K because it is the most played key mode and most beatmaps are for 4K. But there are also mappers for 5K, 6K, 7K, 8K and 9K, they are just rare. And they often have trouble finding modders. It may also give you an advantage in becoming a Beatmap Nominator in future! Modders for higher key modes are very much in demand!
- **Check how other people mod!**
    - Yes, for real. There’s nothing bad about looking at how other people do it. Go into the discussion from some recently ranked beatmaps and check them out! Especially mods from Beatmap Nominators are worth taking a look at!. They are usually very experienced in modding.
- **Editor usage (functions not everyone might know)**
    - **Open for Reference**: Opens a second difficulty to compare with the current one. You can access this function by “File -> Open Difficulty -> For Reference”. Then just click on the difficulty you want to open.
    - **Show Sample Name**: Shows you the hitsound names on the notes. You can access it by “View -> Show Sample Name”. This does show you the default W/F/C samples and custom sample names. Works also with the reference difficulty.

## 4. Useful Links
- **[General Ranking Criteria](https://osu.ppy.sh/help/wiki/Ranking_Criteria)**
- **[osu!mania Ranking Criteria](https://osu.ppy.sh/help/wiki/Ranking_Criteria/osu!mania)**
- **[Naxess' Mapset Verifier (Modding Tool)](https://github.com/Naxesss/MapsetVerifier)**
