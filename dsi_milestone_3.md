#Design Framework
##Plan and execution
As we were all in different places for this phase, we had to take a highly distributed approach to this milestone’s work. Furthermore, due to poor connection, most of the time videochat wasn’t even an option, so we had to work asynchronously as well.

##Form factor, posture and input methods
Since our app makes heavy use of Augmented Reality (AR), we decided that the form factor should cover the entire viewport, with high-resolution overlay elements that appear directly in the line of sight of the user. However, as will be detailed later, one of the users’ concerns was that the app would require too much attention and would gen in the way of their date. Therefore, we must strive to make the notifications and controls subtle.

Outside of a date, just before it starts, the app could have a **sovereign posture**, since the users wanted to know details about their dates beforehand, such as biography, goals and aspirations. Thus, it would be useful to display this dense information before the date starts, since it’s the time when the user will have the most urgent need for it. On the other hand, once in the date, the app should sit in the background and only notify the user when there is critical information, such as a dangerous topic approaching or a topic suggestion when the conversations runs out. Therefore, during the date, the app should adopt a **daemonic posture**.

Since the user will not be able to exercise much control over the application while in a date, the input methods will have to be indirect, such as hand gestures, head movements and voice commands. However, while in a date, the app has mainly a responsive functionality, which means that it will not require much input from the user.

##Catalog of data elements 
These elements have been extracted directly from the requriements.

1. Map
 * Track to follow.
 * Places to select.
 * Distance between your location and the target place.
2. Emotion
 * Colour (for each emotion). 
3. Social network widget
 * Profile picture.
 * Pages followed.
 * Interests.
 * Friends in common.
 * Former partners.
4. Online encyclopedia
 * Search bar.
 * Title of the information.
 * Well-organized information.
 * Index.
 * Related somehow with the social network widgets, because we shall be interested in searching the interests that we don’t understand about the other person.
5. Intermittent notifications box
 * Low intrusive appearance.
 * Easy to read.
 * Intermittent (it appears and disappears).

##Functional elements
###Josh:
- Connect (Action) with wikipedia to show biographies or historical facts (objects) that are interesting to know for the user (context).

  1. From our “main view” we can identify an wikipedia search bar showing the title in every moment of the subject that is relevant in that moment form the application point of view.
  2. Josh can see the information about the subject the application decides in any moment.
  3. When seeing the information Josh can select rapidly where to go in an index.
