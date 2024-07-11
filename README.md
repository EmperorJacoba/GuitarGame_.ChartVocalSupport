# Notes about this fork (currently planned to be .vchart, "Vocal Chart")
To whoever finds this fork (please be no one, I am extremely unconfident about this right now),
I believe we have entered a new era of Guitar Hero/Rock Band/Clone Hero charting.

With the recent release of rhythmverse and the release of YARG, vocal support has become more common in our community. Rhythmverse supports vocal charts in their files outside of RB3 packages, and YARG has native vocal support.

But Moonscraper & the .chart format have not updated to match. If a charter wants to add vocal support to their charts, they have to use Reaper or EditorOnFire, which are both abysmal and extremely outdated for charting. 
Moonscraper is the Rock God's gift to man, but it lacks support for the fourth core gamemode in Rock Band that is now starting to become more prevalent in the PC Guitar Hero clone space. And the superior (in my opinion) .chart file has no support for vocals at this moment. 

I want to change both these things, and add vocals support in .chart files for the new era of PC clones of GH/RB. I have rough drafts for how I think this could work. 

On the backend (the .chart format itself), I think it would be rather easy to add vocal support with the current infrastructure .chart files have combined with .mid documentation and current vocal standards. 
In moonscraper, however, a completely new UI would have to be built to edit the vocals in the .chart file. I have two goals: expand the .chart file to support vocals, and expand Moonscraper to support charting vocals on .chart files (I am not even thinking about converting between .chart and .mid files right now, that is an issue for later)

I do not currently know how to code in C#, nor use Unity. I am in the process of learning them, so it will be a while before I actually start creating this concept, if ever. I am currently reading up on the nitty-gritty of the existing infrastructure in .chart and .mid files additionally, and I will look over Moonscraper's code when I get through some C# courses.

While I prep myself to start working on this, I will attempt to sketch out my proposals in this fork. I will refine them later on.

I doubt anyone will stumble upon this, and I sincerely hope not, as I know I look *real* stupid right now. This is a passion project that I personally want to add to the CH (mainly YARG, to be honest) community, and I will worry about getting support in games implemented later, after I actually implement this new vocal track in .chart files. 
Also I did not know forks were forced public when I forked this, which is the whole reason I wrote this disclaimer. Already made it, so might as well live with it. Womp. 
