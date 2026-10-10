# CSCW Meta Design Thoughts

These are ideas for the actual app itself, not the meta-app

- Live conference chat:
  - When opening it asks "Which talk are you currently at?"
    - Options display paper title + room description
    - Also an ongoing "Hallway track" option
  - Choosing an option opens up an ongoing chat for that particular room.
    - As sessions start and as paper talks begin, markers in the chat appear
- Message other conference attendees
  - Direct messages
  - Group messages
    - Use case: messaging a paper's authors, see below
    - Use case: introducing someone (start a chat with 1-1 then leave?)
- Find room feature?
  - Should this be somehow integrated with the conference chat feature? That seems relevant.
  - There is a map of the conference venue on the website
- CSCW Meta
  - Meta Facebook group-like discussion platform, not live chat
  - People create new threads
  - Other people can reply to those threads.
- Paper browsing discussion:
  - Browse papers in the program (various sorts of search?)
  - Comment on paper
  - Authors can self-claim papers (this is my paper)
  - People can message the authors (e.g. "Hi I loved your paper want to chat?")
  - Bookmark a paper / add it to your schedule
  - Recommend a paper to someone else
    - "You should read this"
    - They get a notification, and perhaps it goes to their schedule optionally
    - This is similar to the Confer tool ("Confer: A Conference Recommendation and Meetup Tool" https://people.csail.mit.edu/axz/papers/demo_confer.pdf)
- Dinner plans?
  - Help people find other people interested in getting dinner.
- People create profiles, where they can describe themselves and make a photo.

## Assorted notes from past emails:

CSCW metarecommend paperscomment on papers in social taggingconfer: you should meet so and so I spoke to amy about the hypothetical cscw bbs.   she said she likes 
facebook, the only problem is that some of our community aren't on it.  
  so from that perspective, you basically want a facebook clone (ie 
namebook).    You could even stick to the same metaphor of facebook 
"groups".  so cscw would be one facebook group, but anyone who wanted to 
could create another and then users would see posts from both groups in 
their feed (I assume you'll offer chronological only with no recommender 
algorithm). at the same time, you could keep it all invisible by having 
the cscw "page" let people single-click join the cscw group without 
going into details of how there can be other groups.
The cscw steering committee is discussing setting up a cscw discord. This got me thinking about one nice way to leverage the powers of graffiti. Create multiple cscw meta apps that replicate the look and feel of different social tools. One that looks like discord, one that looks like slack, one that looks like Facebook, one that looks like WordPress, one that looks like Reddit, etc. That way everyone can use their favorite. The challenge/question is figuring out a common schema for the conversations that all these different apps could properly present and manage
CHI (which I'm not at) has me thinking about revisiting some Confer ideas for UIST and CSCW in october/november that I think could advance both your research agendas.   I'm envisioning a "social conference app": shows the conference program (already accessible by an api)lets you mark papers you want to attendlets you *recommend* papers to specific other people---recs show up in their view of the program as well as a "show my recs" pane.   allow for recommendation of other not-in-conference papers (eg from acm dlib) e.g. to let speakers know about something they should look atwithin each paper's listing in the program, a discussion channel for talking about that papermeronymous identities for people nervous about participating in those discussionslets you recommend meetings between people (eg your students and people in their area)lets you see people who are interested in the same papers as youlets you schedule meetings with people (especially recommended ones) (include map data specific to the conference to make it easier)DMs so you can update plans around those meetingsschedule/calendar view showing papers you want to attend and meetings you want to have.  ideally with an ical representation that can be imported to user's customary calendar app https://www.dropbox.com/t/uNhTid6cJvvA mUg

This is in an email from the current chair of cscw.    It would be cool 
if we could seize this opportunity.

> One of the things I would like to discuss is how to generate community 
> discussion. None of the current mailing lists have many members, only 
> a small fraction of the community and seems to contain mostly the same 
> messages as in CHI Announce. The Facebook group seems to reach more 
> people than these mailing lists, but it definitely has downsides. We 
> might consider requesting an ACM mailing list (which apparently we 
> used to have) or shifting to another platform.
