---
layout: single
comments: true
title: "New Manager Bounce : Analysis of Mid-Season Manager Hirings in the English Premier League"
date: 2016-05-30
---
<sub>Starred post on Reddit's /r/soccer</sub>

The term 'New Manager Bounce' has become part of football jargon over the past few years. Given the new TV deal and the plethora of opportunities to make money by staying in the Premier League, there is an ever increasing pressure on managers to deliver results fast. A few wins on the trot could be the difference between survival and relegation. Clubs turn to new managers hoping for quick results and a change in fortune.

The end of season report by the **League Managers Association** makes for grim reading. The total manager sackings rose to an all-time high of 58 at the end of the 2015/16 season in the **top 4 tiers** of English Football, in comparison to 47 at the end of 2014/15 season. 

<div style="text-align:center;"><img src="/images/sackbyseason.png" align = "center" height="600" width="600"></div>

There is no doubt football culture has changed over the past couple of decades. Premier League Clubs are run more and more like businesses. Impatient owners, panicking board members, angry fans, endless criticism from the media, one has to feel for the modern day manager. With new managers chasing this mythical "bounce", let us see if the stats back it up.


### Some caveats
The datasets used for the analysis are: 

- End of season table  

- Results for every single matchday 

- All manager hirings and sackings 

The data starts from 1992, the inception of the Premier League, and goes till the end of 2015/16 season. This season's data can be used to validate any assumptions we make along the way.

The goals, objectives and the budgets of the clubs vary wildly from tier to tier of English Football. For the sake of simplicity, I am restricting the analysis only to the English Premier League. Managers with tenure less than 30 days were ignored. Same as managers brought in during the months of April(too short a time to make a change) to August(not mid-season hirings).

With 24 years worth of data scraped, cleaned and organized, I went digging. The results make for an interesting read.

## How many achieve the bounce?
For each new manager, I compute the average points per game for 5 games leading up to the date taken charge and the average points per game for 5 games from the date taken charge. Typically, the new manager bounce lasts for **5** match days before a dip in form. This will help us examine any short term effects. **If the average points per game is better after the date taken charge, we can conclude that the new manager bounce is well and truly in effect**.

Season|      Club       |Before Pt Avg|After Pt Avg| New Manager  |Position Season Before|Position at end of Season
-----:|-----------------|------------:|-----------:|--------------|---------------------:|------------------------:
  2005|Newcastle United |          0.2|         2.6|Glenn Roeder  |                    14|                        7
  2008|Blackburn Rovers |          0.0|         1.8|Sam Allardyce |                     7|                       15
  2008|Tottenham Hotspur|          0.2|         2.0|Harry Redknapp|                    11|                        8
  1997|Aston Villa      |          0.6|         2.4|John Gregory  |                     5|                        7
  2007|Wigan Athletic   |          0.0|         1.6|Steve Bruce   |                    17|                       14
  
*Above table shows top 5 results for the highest bounce achieved. Season 1997 denotes 1997/98, 2005 denotes 2005/06 and so on.*

Let us look at the entire history. Among **107** mid-season manager hires, **80** of them were able to bring in a bounce in form (~74%). Let us take a look at this season's mid-season hires.

- Sam Allardyce -- Surprisingly, no new manager bounce. But Big Sam turned it around with 4 consecutive wins and saving Crystal Palace from relegation. 

- Marco Silva -- 4 wins in his first 4 home games. Definite Bounce.

- Craig Shakespeare -- 5 wins from 5 games in charge. Definite Bounce.

- Bob Bradley -- Negligible. But going by numbers, Bradley did well in his first 5 games in charge compared to the 5 before (2 draws in 5 games vs 1 draw in 5 games prior). It should be noted that the sacked manager Guidolin had the more difficult fixtures leading up to his sacking.

- Paul Clement -- Definite Bounce. Evidenced by the Manager of the Month award in January.

- Steve Agnew -- No improvement. 




### Worst performing new managers

<img src="/images/villa15.png" width="325"/>   <img src="/images/sunderland02.png" width="325"/> 

**Eric Black** (Aston Villa, 2015/16) and **Mick McCarthy** (Sunderland, 2002/03) are the only mid-season hires to start their terms with 5 consecutive losses. Surprisingly, the 5 games leading up to their start were also losses. Ultimately, the new managers couldn't save their clubs from relegation. 


## When is the bounce most prevalent?
Let us examine the number of manager hirings by month and the ones who achieved the bounce.

<div style="text-align:center;"><img src="/images/bymonthbar.png" align = "center" width="425"></div>


**November is the highest**, with 14 out of 16 managers achieving the bounce (~ 88%). If you look at the following plot closely, it is easy to observe that managers tend to do well from October to December and start dropping off from January onwards. 


<div style="text-align:center;"><img src="/images/bymonthpercent.png" align = "center" width="425"></div>


This indicates that the best time to bring on a manager would be towards the end of the first half of the season. There are many factors that contribute to this. Unless the situation was hopeless and an immediate change was needed, teams do not sack managers during the early parts of the season. This makes it relatively easy for new managers to bounce back, since there is no way to go but up. Also, managers can make use of the winter transfer window to bring the right players they need. Then again, you have [Moyesy](http://www.telegraph.co.uk/football/2017/01/20/david-moyes-paints-bleak-picture-sunderland-transfer-hopes/). 

## Big Picture
Now that we have sufficiently established the presence of the "new manager bounce", let us take a step back and look at the long term impact of bringing in a new manager. Does the club finish higher up the table than the season before?

Out of the **107** mid season hires, only **30** managers could help their club finish higher(~ 28%). Among the 30 who did well, 23 were brought on by January(~ 77%). This is expected as managers hired from February onwards are usually brought in with the objective of stopping the freefall and steadying the club. One important takeaway is that the **new manager bounce is no evidence for long term success**.

### Acrimonious Departures
--> *What if there is no "new manager bounce", but the team still ends up finishing higher in the table?* 

Lets take a step back and think about this. A new manager has been brought in and there was no "new manager bounce". The season ends and the team finishes higher in the table compared to the previous season. This means the new manager did not improve the performance and the replaced manager must have done  a great job. There is no incentive for the manager to leave or get sacked when things are going so well, unless something controversial had happened. Let us take a closer look at these cases.

- Ruud Gullit (Chelsea 1997/98) 

  Player-manager, allegedly sacked for a disagreement with the club's board over compensation.

  > "I didn't like his arrogance – in fact I never liked him." - Ken Bates, Chelsea Chairman after the sacking.
 
- Glenn Hoddle (Southampton 2000/01)  

  Left Southampton mid way through the season to manage Tottenham. Embroiled in [controversy](http://www.telegraph.co.uk/sport/football/teams/tottenham-hotspur/3001934/Hoddle-quits-Southampton-for-Spurs.html).
  
  
## Specialists in...
Are there any managers who have made a reputation by achieving this bounce and turning fortunes around? Familiar names pop up.

If we just look at the numbers, Harry Redknapp leads the list where he has achieved the bounce 3 times. But this metric is misleading in identifying specialists. If a manager has had a lot of stints, he is bound to get it right some of the time.  

A better metric to look at would be the **number of times bounce was achieved relative to the number of times in charge during mid-season**. We look for managers who have been hired *more than once* during the mid-season.

**Alan Pardew, Avram Grant, Guus Hiddink, John Gregory, Kenny Dalglish, Ron Atkinson, Sam Allardyce and Tim Sherwood** have a 100% record of achieving a bounce, while Harry Redknapp drops down the list with a 75% record (3 out of 4 stints). 


## Asinine Strategy
The new manager bounce lasts for a few matchdays, before the eventual regression to the mean. So how do clubs strategize managerial changes, in order to capitalize on this new manager bounce? 

Going just by the numbers, it would make sense to have a manager for 9 games. This will result in 4 managers per season. The bounce in form sustains for 5 matchdays before the slump. Just at the end of the slump, you bring in a new manager who repeats this cycle. Repeat this process until you get a manager who does not bring in a huge slump after the bounce period.

Wait, what if there is no bounce in the first 5 games? Wait 4 more games to see if there is an improvement in form. If so, then stick with the manager for the next 9 games. Let us look at Sam Allardyce this season at Crystal Palace, there was no new manager bounce but he managed to turn it around. There are plenty of signs that point to the fact this type of improvement is more sustainable. If there is no improvement in form even after 9 games from hiring, it is time to look for a new manager.  

## Conclusion
> “Whatever the reason for hitting a low, things will almost inevitably improve afterwards.” 

> “The new manager rarely causes the pendulum to swing. He’s just the beneficiary of the swing.” -- Simon Kuper and Stefan Szymanski’s book, Soccernomics.
 
While that is true, one cannot argue the fact that with new managers one gets a change. If you are the owner of a club in free fall, you cannot just wait and expect things to get better. With a new manager, you get a fresh set of ideas and tactics. Players tend to perform better to impress their new manager. A new manager is a much needed catalyst for a change. As the stats point out, you can expect an improvement in form most of the time. It is a risk many clubs are willing to take.

## TL;DR
- Out of 107 mid-season(September to March) hires, 80 of them got a bounce (~ 74%). A bounce is when the average points per game for 5 games after the date of hiring a new manager, is greater than the 5 games before.
- Eric Black (Aston Villa, 2015/16) and Mick McCarthy (Sunderland, 2002/03) are the only mid-season managers to start their terms with 5 consecutive losses. The 5 games before their start were also losses.
- Bounce is highest in November, with 88% of the managers getting the bounce.  
- Best time to bring in a manager is towards the end of the first half of the season.
- Out of the 107 mid season hires, only 30 managers could help their club finish higher in the table compared to the previous season(~ 28%). New manager bounce is no evidence for long term success.
- If the team finishes up higher in the table but there is no bounce, then the replaced manager left in controversy. eg. Ruud Gullit and Glenn Hoddle.
- Specialists : Guus Hiddink, Sam Allardyce etc. Got a bounce in all of their stints.
