---
title: "Small Mess System v1.0"
subtitle: "Practical organization for digital creators"
date: 2024-02-27T07:59:56-06:00
draft: false
comments: true
tags:
  - Artmaking
---

The Small Mess system (SMS) works on the idea that a small mess is inevitable when working on a creative project, be it an unorganized stack of notes, pencils scattered on a desk or a mood-board with lots of images. These small messes are not a problem when we're working, but at some point, they start to blend into each other and turn into a huge mess, which is now intrusive to our creative process and needs to be cleaned up.
The system helps you organize small messes into distinct sections so they don't blend into each other, with the added benefit of archiving past projects and quick access to important files.

This system will not tell you how you should organize your project, if you feel comfortable with having 500 files in one folder with no additional structure that's up to you.
It will only help in preventing that from spilling over and affecting other projects.

## Folders

These are four basic folders that every SMS vault must have:

- **Active**
- **Archive**
- **Fridge**
- **Admin**

Let's go into more detail on each one.

### Active

This folder is your digital desk. Where everything you are currently working on is, no more dumping files in the desktop along with your shortcuts. If you're working on it, it goes here.

"Won't it turn into a mess if I have everything there?"
Yes, that's what this whole system is about, there's no problem with having what you need handy and ready to be used, even if its messy, as long as its a small mess that is easy to work with and simple to clean.

### Archive

Here goes everything that's done, its a hard rule that if its here, you can't work on it.
Once you publish that article, turn in that commission or give up on that song, it gets boxed up in a folder and frozen in time with a unique, understandable and best of all, searchable special name.

Within this folder you'll have folders for each year, and within that, a folder for each month. This is immensely helpful for scheduling cleanups, but also to keep track of when you did what.

### Fridge

The fridge is for all those resources you commonly use in projects, such as design guidelines, file templates, reference images, those hand stretch exercises, or whatever you know you'll want to have handy in more than one project.

### Admin

The boring stuff that you need to keep around.

Unfortunately, filing taxes is a recurring event, this folder is made to keep the "business side" of whatever you do contained but also accessible. This might include your pricing information, receipts, client contact information, etc.
Bottom line is that files here are necessary but not directly related to your craft unlike those in the fridge.

## Folder Structure

```
ROOT/
+-- [active]
+-- [archive]
    +-- year
        +-- month
            +-- project-a
            +-- project-b
+-- [fridge]
    +-- Notes
    +-- References
    +-- Tools
    +-- Brushes
    +-- Characters
+-- [admin]
    +-- Brand
    +-- Taxes
    +-- Commission Info
```

## Filename Convention

### Path

```
+-- [archive]
    +-- year
        +-- month
            +-- (project folder)
```

### Filename

    Prefix[Arguments]-Descriptor

#### Prefix

- **il**: Illustration
- **ani**: Animation
- **ps**: Photo session
- **vg**: Video-game
- **3dm**: 3D Model
- **logo**: Logo design
- **album**: Contains several song projects
- **super**: Super project, contains related sub-projects

##### Arguments

Arguments are separated by '-' dashes, with the identifier number always going first.

- **_number_** unique numeric identifier for the project (can use ascending, hashed, timestamp, etc), MUST GO FIRST
- **com{_client_}** commission identifier, include client name
- **unf** unfinished marker, used for incomplete projects that have a lot of files, only used to maintain monthly folder cleanliness

#### Descriptor

This is the personalized text you'll add to the project, probably the most important when it comes to understanding what the project is about, try to be as precise as possible, and think of keywords you might want to search for later (portrait, fantasy, charcoal, etc.).

### Rules

- NO spaces in file or folder names, ever.
- Avoid capital letters, never have two or more files with the same name ("File.txt" and "file.txt").
- Short, yet descriptive names, "cat" is not a good descriptor if you draw a lot of cats.
- No number identifiers in the descriptor (eg. "cat-15"), that's what the unique identifier number in the prefix is for.
- Never add any additional characters before the prefix.
- You can make new prefixes, but be consistent with them.
- Avoid using parentheses () and reserved words like "NOT", "OR", "LIKE" etc. as it will interfere with your searches.

### Example

I have an illustration of a white cat, which was commissioned by Tom. I finished the project in February 2024.

- Folder placement: ROOT/[archive]/2024/01/(here)
- Project Folder name: il[1-com{Tom}]-white-cat/

I'll place all the files related with that project inside that folder from my [active] folder.
If there needs to be any additional structure within that project folder, I'll make additional folders or information files within that folder, there is no set structure within project folders.

## Getting Started

This system is very minimal and does not require you to download a piece of software or any other external tool to function.
If you're starting from scratch, make a folder that will serve as the root of your SMS vault.
You can name this whatever you like, but keep it in an accessible location and with a distinct name, such as "art-vault", "articles-sms" or simply "projects".

Create the basic folders inside the root you just made. You can pick any names you want for the folders, but I recommend adding a special decorator so you know which folders you don't want to be moving ("[Archive]", "archive-sms", "!archive")

If you were using a different system or had a particular structure to your projects before, a few lines of code and you might be able to reorganize everything into the system.
In any other case, you'll want to organize as much as you can into the [fridge] and [admin] folders since you'll be making use of these constantly as you work.
For previous projects, if there's no salvaging the structure or don't care, make a folder in your [archive] named with the earliest year a file was worked on up to the latest with an identifier such as "2017-2021 unorganized" and start from there.

You can create a vault in anything that has a functional file-system with folders, be it your personal computer, a Google drive or Dropbox, an external drive, or you could even make it into a git repository if your really wanted to.

## Usage

Whenever you start a new thing, be it project, sketch, idea or whatever it might be, place files in the [active] folder.
If you are adding a large amount of files, you can make a sub-folder to store that sketch's files temporarily.
Keep working no your thing until you consider it complete, meaning you are going to either publish it, and don't feel like there will be any more significant changes done.
Create a project folder and name it according to the [Filename Convention], place all related files within that folder. Move the folder to the appropriate year and monthly folder at the date of completion/publication.
Finally, you can clean up the [active] folder by moving finished or dropped ideas to the same monthly folder.

### Monthly Cleanup

Once the month ends, go to your [active] folder and move anything no longer being worked on to the appropriate monthly folder.

This will mean that your monthly folder will be a combination of finished projects with the SMS nomenclature and unfinished ideas and sketches.
This is fine, as long as you can distinguish between them there's really no need to further organize them unless it bothers you.
I can personally say its a great feeling to wrap up a month by browsing what you did and moving on to the next thing.

### Examples

1. Lets say you signed up for a new website or social media and want to make a post for every illustration you've done so far.

First, you'll want to go to your [archive] and search for "il[".
This will get you every illustration you've done, but if you want to be more specific, you can add more arguments to your search.
To get all illustrations but exclude commissions, search "il[ NOT com{"

2. Your long time commissioners Anne lost all her files and asked you if you could re-send them.

Once again, go to your [archive] folder and search for "com{Anne}".
If you want all their commissions in a specific year, start your search from within that year's folder.

## Pitfalls and weaknesses

The system ain't perfect in any way, and with some types of projects can be more bothersome than helpful.
It works best with projects that can be sealed away and left alone.
Meaning that for example, software that is getting constantly updated or live-service related projects are a bad match for this system.
There may be ways of adapting it, but I fear that the solution would end up being to mostly ignore the core ideas of this project.

## Extending the system

Having a SMS vault by no means will let you forget about organizing ever again, its meant to be the 20% you do that gets you 80% of the results.
One could easily implement an app or interface to automate most tasks. However creative programs are very finicky with file paths so your mileage may vary.

Possible extensions of the system could look like an AutoHotKey script, a terminal interface or a full website with a remote implementation. These are left as an assignment to the reader.

# Credits

Something like the Small Mess System has been on my mind for about a year.
I felt that a tag based approach to file management would be a much better solution than what we use now, but the technical aspects compete with existing technology and would honestly be a headache to work with thanks to art programs freaking out over a non-conventional file structure.
I really nailed this system down when I found out about [the PARA Method](https://fortelabs.com/blog/para/). There are evidently a lot of similarities, especially with the base folder structure and concepts, the system would not have come to be without knowing about it.
