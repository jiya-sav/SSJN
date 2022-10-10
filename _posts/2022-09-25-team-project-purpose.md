---
toc: true
layout: post
description: SSJN's Group Project Purpose Description.
categories: [markdown]
title: SSJN Project Purpose
---

# SSJN Group Project

## How it will Work

1. Users enter their current emotion into a text entry box
2. User is then prompted to fill out an optional survey to further personalize song list.
3. The program outputs a list of songs that match their current emotion, with spotify links embedded, so the users can explore new music!

## Spotify x SSJN!

![]({{ site.baseurl }}/images/SSjn.png)

> xxx

![]({{ site.baseurl }}/images/spotify.png)

## Roles

- Scrum Master: Shreya Sapkal
- Frontend Developer: Noor Grewal
- Backend Developers: Sanika Shahapurkar & Jiya Savlani

## Implementation: 6 Principles of College Board

1. Program Purpose and Function

> To help users discover new types of music, artists, and songs. To help users diversify their music listening experience.
> To match users with a list of songs to listen to depending on their current emotion.
Input: Emotion/Mood (out of options provided)
Output: Song that matches mood (selected out of info provided from API, additional information like lyrics or link to listen may be provided)

2. Data Abstraction

> Output will be displayed using a list, to provide multiple song options to diversify users listening experience.
> Planned name of varibale representing list: 
Melancholy = ["I Bet On Losing Dogs", "See You Again", "Burning Hill"]
> Data in this list represents music type

3. Managing Complexity

> By using lists to display song output, it is not necessary to write continuous lines of if/else statements, though they may still be useful for further personalization. 
> In case that list is not used to provide songs, multiple functions may have to be written and printed seperately
ex: 
if Emotion=Melancholy
  print("I Bet On Losing Dogs""
  print("See You Again")
  print("Burning Hill")
  
4. Procedural Abstraction

> Use procedural abstraction to account for user error input, to ensure selected Emotion is existent in program
ex:
def emotion_input
  if Emotion = melancholy
    print("Melancholy")
  elif Emotion = joy
    print("Joy")
else
  print("Please input emotion")
    
5. Algorithm Implementation
- sequencing
Use of strings and lists to output song information, as well as error information (shown above)
- selection
Use of if/else/elif statements (as shown above)
- iteration
Use of for loops (*still planning how this may be implemented productively into program given function)
ex: 
emotion = ["melancholy", "joy", "rage"]
for x in emotion:
  if x == "joy":
    break
  print(x)

6. Testing

Test each cell, which will be organized by purpose. Each line will have notes to ensure we manage complexity, as well as best enabling ourselves to explain in video.


  
