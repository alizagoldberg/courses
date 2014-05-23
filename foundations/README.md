---
title: Foundations of Computing 
date: 5/28/14 - 7/14/14
time: M & W 10am - 1pm 
affiliation: Columbia University, Lede Program
instructors: Jonathan Soma, Dennis Tenen
location: 601b Pulitzer Hall*

---

\* We will be meeting in room 601b for the first week or so and then according to the [room schedule](https://drive.google.com/file/d/0B4OAOue0b3VMNXJ1Z1loaGg4bWc/edit?usp=sharing).  

> An introduction to the ways in which the computer and data technologies can be partners in creative practices. We will emphasize writing code over point-and-click interfaces, presenting the computer as a programmable object. Through a series of projects, students will move from exploratory sessions, to writing small programs, to sharing code with others in class. They will learn by making, and in the process master a "scripting language" like Python or Ruby. Projects will examine and extend existing technologies in the digital humanities, computational journalism, architecture, and design; and will likely deal in text and images, in human relationships as exhibited through social networks, in map-making, and in reporting.

## Week 1: Intro to Terminal

**Focus**: Get comfortable running Python at the command line and understand that seeking out help is 90% of coding

### Wednesday 5/28

- Programmer's mindset
- Course philosophy
- Computer architecture
- File cleanup/organization
- Introduction to pseudocode
- Terminal bash basics
- Python hello world
- Simple data types, variables, methods
- Getting help
    - Living with syntax errors
    - Docstrings
    - Googling
    - IRC backchannel

#### Wishlist

Conditionals & lists

## Week 2: Python Basics

**Focus**: Learn to read and write basic (clean, commented, beautiful) Python.

**Week Inspiration:** [Dogs of NYC](http://project.wnyc.org/dogs-of-nyc/)

**Resources:** [Sustainable Authorship in Plain Text](http://programminghistorian.org/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown)

### Monday 6/2

- More pseudocode
- Writing readable code 
- Dictionaries (csv.reader vs. csv.DictReader)
- for...in
- Functions
- Object-oriented basics
- Style w/ PEP 8
- Github workflow
- Markdown

### Wednesday 6/4

- Lab notebooks
- Algorithmic thinking with [Dogs of NYC data](https://www.google.com/fusiontables/data?docid=1pKcxc8kzJbBVzLu_kgzoAMzqYhZyUhtScXjB0BQ#rows:id=1)

## Week 3: Object Orienteering

**Focus:** Get more comfortable with coding, install some libraries, write your own class.

**Week Inspiration:** [Quakebot](http://www.slate.com/blogs/future_tense/2014/03/17/quakebot_los_angeles_times_robot_journalist_writes_article_on_la_earthquake.html)

**Resources**: [Idiomatic Python](http://web.archive.org/web/20140501190202/http://python.net/~goodger/projects/pycon/2007/idiomatic/handout.html)

### Monday: 6/9

- Reading other peoples' code
- Installing & using libraries ([gspread](https://github.com/burnash/gspread)?)
- Writing your own classes
- ~~Version control~~
- ~~Data types~~
- ~~Control structures~~
- ~~From text to data~~

### Wednesday 6/11

- Write a story generator
    - Class with methods, attributes
    - Outputs sentence based on input
    - Can be expanded/contracted based on skill level

~~***Lab:*** Github workflow. NLTK excercises.~~

## Week 4: Working with the Census and an introduction to APIs

**Focus:** Use another library, a simple key-based API, understand Census data

**Week Inspiration:** [Almost every story ever uses ACS data](http://articles.latimes.com/keyword/american-community-survey)

### Monday 6/16

- APIs
- The [census package](https://github.com/sunlightlabs/census) from Sunlight Labs
- Census terminology
    - FIPS codes
    - Blocks, tracts
    - MSAs
    - [etc](https://www.census.gov/geo/reference/)

### Wednesday 6/18

- .gitignore for API keys
- Project using with ACS data

## Week 5: AWS & Crypto

- AWS Server
- Cloud computing
- Internet infrastructure 
- Cron

**Week Inspiration:** ??? ~~[Twitter stories](http://radar.oreilly.com/2013/12/tweets-loud-and-quiet.html)~~

### Monday 6/23

- OAuth?
- Security and cryptography 

### Wednesday 6/25

- Send an encrypted email message

**Resources**: [How PGP Works](http://web.archive.org/web/20140501185547/http://www.pgpi.org/doc/pgpintro/), [Mailvelope](http://www.mailvelope.com/), [Keybase](https://keybase.io/)

## Week 6: Matplotlib

**Focus:** Make visuals of your data

**Week Inpiration:** [How FiveThirtyEight Got the Nigerian Kidnappings Analysis Wrong](http://web.archive.org/web/20140516152339/https://source.opennews.org/en-US/articles/gdelt-decontextualized-data/)  

**Resources:** [Statistics Done Wrong](http://www.statisticsdonewrong.com/), [Demystifying Networks](http://web.archive.org/web/20140501191102/http://www.scottbot.net/HIAL/?p=6279), [Introduction to social network methods](http://www.faculty.ucr.edu/~hanneman/nettext/)

### Monday 6/30

- Bad stats
- Tufte
- Working with data
- Data visualization
- Matplotlib

### Wednesday 7/2

- Matplotlib
- Bokeh
- Google TakeOut

## Week 7: Mapping

**Focus:** Making non-interactive and interactive maps (matplotlib and TileMill, respectively)

### Monday 7/7

- Shapefiles
- Joining data (Join with week 4 via FIPS?)
- Color schemes
    - diverging, sequential, qualitative
    - color blindness
    - RGB vs HSB
- Geocoding points

### Wednesday 7/9

- matplotlib
- [TileMill](https://www.mapbox.com/tilemill/)

## Week 8: Physical Computing

### Monday 7/14

- Physical computing
- Sensor tech
- Drone control

**Lab:** [Phidget](http://www.phidgets.com) music machine.

# Moved & etc

- Pandoc
- Protocols
- Debugging w/PDB in iPython 
- Exception handling
- Character encoding
- Scrape data from Twitter
- Twitter API with [tweepy](https://github.com/tweepy/tweepy)

***Lab:*** Traceroute. Amazon AWS. Sys admin basics. Package management, permissions, security, etc. Diagram a packet from home. Cron and Boto.  
***Resources***: [Take the Linux Filesystem Tour](http://web.archive.org/web/20140501190339/http://tuxradar.com/content/take-linux-filesystem-tour/)