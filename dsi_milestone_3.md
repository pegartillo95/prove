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

- Connect (Action) to every social network to extract the personal information of the hobbies of the target girl (object) before the date (context).

  1. When Josh starts walking to the date location, a notification will automatically shown in order to open the girl’s profile.
  2. We can open her profile whenever the notification is activated.
  3. When showing the profile Josh can select what to read and when to close it.

- Connect (Action) to Google Maps (object) when requested by the user (context).

  1. A map with your location will be shown in every moment in the “main view”.
  2. In every moment Josh is able to ask for going to different places. At the same time the application is suggesting locations whenever is important from the application point of view.
  3. When the places are found he can select one of them.
  4. A track will be shown whenever Josh selects a target place. Alternative paths can be taken by Josh.

###Aaron:
- Show (Action) the information (Object) in a way that is not very intrusive because the one using it (Context) has to be able to follow the app info at the same time that is having a date with someone.

  1. The “main window” is generally empty in the center and part of the sides.
  2. Notifications will only be shown when it is extremely advisable from the application’s point of view.
  3. Aaron can close any notification as soon he is uncomfortable with it.

###Helene:
- Display (action) a box (object) to see all the previous relationships of the guy and see the comments of their ex-girlfriends beforehand (context). It should search (action) for common hobbies(object) and propose new topics (action) to Helene in the screen when the conversation stalls(context).
 The same as the second functional element of Josh. It can also notify when to talk about some particular topic. (Notice that there are two functional elements in one)

- She wants to know if the guy is trustworthy, so the app has to notify(action) this information and the reasons(object) in advance(context), so Helene does not waste time. The app should notify (Action) if the guy (object) is looking for a long term relationship during the date (context).
 A notification will be shown just the same way as with Aaron. (Notice that there are two functional elements in one)

- The app has to analyze (action) the user gestures and face (object) and find out if the guy is starting to fall in love (action) during the date (context).

  1. We can see the emotional state of the other person permanently in the “main view”.
