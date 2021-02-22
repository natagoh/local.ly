Thanks for checking out our medium-fi prototype! 

Operating Instructions:
Our medium-fi prototype was developed in Figma for the Google Pixel 2 XL. Figma will highlight rectangular regions that can be clicked on the screens to simulate transitions and perform various actions. 

Figma Link: 
https://www.figma.com/proto/ptoDW2Drn3HL8zzb8Kz8aG/Local.ly-Medium-fi-Prototype?node-id=133%3A129663&scaling=scale-down

Important Note: 
Figma allows you to use your keyboard left and right arrows to navigate screens. 
If you use these arrows to transition, you may not progress through the screens in a logical manner because the keyboard arrows do not follow our branching logic. 

Features:
- Search for and navigate to local stores that fit selected value and distance filters
- Save store cards to your card wallet
- Share cards with friends looking for recommendations
- Ask your friends for shop recommendations
- Receive cards from & chat with friends
- Scan purchase receipts to progress your card ranks and unlock rewards

Wizard-of-Oz and Hardcoded Features:
Most of our features currently are hard-coded due to the inability to ask users to input information, connect to a database, and leverage APIs in Figma. 
- Log in and sign up information is hard-coded
- User profile and friends information is hard-coded
- Users can currently only search for jackets, and we've limited the value filters that users can apply
- Store results & all store details that appear on cards (i.e. rating, number of friends who trust, store hours) are hard-coded 
- The store recommendation the user can ask for, and the recommendation card the user receives is hard-coded
- All chat information is hard-coded
- We simulated the passage of time between when a user asks for a recommendation and receives one through a different screen that shows their post is now 15 minutes old 
- We also simulated the user receiving a notification showing their friend has asked for a recommendation by having a separate home screen that the user encounters later in the flow 
- Card rank progress and receipt-scanning is hard-coded to facilitate demonstrating the functionality 
- When the user clicks text boxes or the keyboard in certain instances, we auto-fill the text box with a hard-coded message since we can't actually process user input in Figma.  

Limitations:
- We have intentionally limited the clickable regions to maintain continuity in our task flows. 
- To focus on our 4 main task flows, we have left out some features and screens, like a sign out button, and the screens that would correspond to the options on the profile (edit profile, add friends, account settings). 
- We left out opening Maps (which should open Google Maps or whatever default map app the user has set) since we are the Figma environment.
- The "call" button on store cards is not functional currently but should open up the user's phone app with the store's associated phone number. 
- We simulated the passage of time through different screens with notification bubbles and different timestamps since we did not want users of our medium-fi prototype to spend a long amount of time waiting until they could progress on certain tasks.
- We could not simulate swipes using Figma so we stuck with clickable buttons.