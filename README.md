# TimeCapsule
HOTH XII UCLA (TimeCapsule) -- Kindness Challenge

**Overview**

With nearly 322 million people being affected by depression worldwide [https://iris.who.int/bitstream/handle/10665/254610/WHO-MSD-MER-2017.2-eng.pdf] (2017), it is important to
recognise the need for empathy, bridging social divides, and combating loneliness.
This is why I am creating TimeCapsule:

When individuals practice self-compassion, they're often better equipped to extend empathy to
others. In other words, nurturing kindness toward oneself can eventually foster more meaningful
connections with people from diverse backgrounds.

**What it should do:**
TimeCapsule allows users to store personal memories such as pictures and texts for periodic
reflection.

Allowing users to share their TimeCapsules with others can promote understanding and
empathy by exposing individuals to diverse life experiences. {Also can share the timeCapsules anonymously}

Incorporating community features where users can connect over shared memories or themes
can help bridge social divides and combat loneliness.




**Features (Currently):**

Personal Memory Storage: Save pictures, text, and other data.

Interactive 3D Interface: Memories are visualized in a dynamic, immersive 3D space using Three.js.

Emotion-Based Memory Organization: Memories are categorized by emotions, affecting their visual representation.

Fading Memories System: Older memories gradually fade but can be revived.

Person Association: Link memories to specific people for organized recollection. 

Community Sharing: Optionally share memories anonymously to connect with others.

Import/Export Memories: Backup and restore memory data via JSON.



**Drawbacks:**

Currently cannot delete any data, or revisit it once an entry made.
Added everything in one file because was under a time crunch and separate files were not working :/
Cannot access memory in any way possible, I wanted to make it accessible by clicking on both the names of the people as well as the specific animations -- did not do either unfortunately.
(When you click on the names however, it does filter out the memories associated with person)


**What does the future for TimeCapsule look like?**
*"Common Ground" Connection Map:*

Users enter personal experiences or struggles they’ve faced (e.g.,
“Struggled with imposter syndrome” or “Moved to a new country”).
The app visually maps connections between people who have similar experiences but come from completely different backgrounds.
Example: A single mother in India might find she shares similar challenges to a college student in the US.

This would help people look past their differences and find unexpected connection, thus promoting inclusivity and kindness.

*"You matter" Notes Archive*

I got somewhere on this by allowing to post things anonymously but the main idea was: 
People can anonymously contribute encouraging notes to others who are struggling.


Also other potential options to improve: 
1. Allow users to change the background --> seasons, custom images to further personalize their experience 
2. The memories "fading away" could randomly appear as Memory portals (basically like a Spotify Wrapped?)

**Technologies Used**

Frontend: HTML, CSS, JavaScript
3D Graphics: Three.js for rendering memory objects
Animation: Tween.js for smooth transitions
Local Storage: Saves user data in the browser


**Proud of**
I used threejs for the first time today so it was pretty interesting and fun to figure that out, although I should probably look into git and file organization first


