# IOS-cooking-App
Creating an application with recipes for cooking delicious dishes

Technical review about work tasks

- Splash-screen with an image when the application starts.
- Implement local registration / login, save data using UserDefaults. The flow is as follows: The user logs in, tries to log in, if the login does not find the value in UserDefaults, he pops up Alert: "User not found", registration - saving the dictionary [String: Int] - nickname and password. If a user is found by nick, but the passwords do not match Alert: "Wrong password". Make the password TextField's keyboard only for numbers.

- TabBar has 2 tabs:
- List of recipes, includes a feed of recipes, also implement a screen segment control that switches between breakfast / popular or something like that, that is, by clicking on each item: a different list should be!
- If the tape is empty, then show the appropriate placeholder!
- By tapping on a cell, a transition to a detailed view with detailed information is carried out! On the detailed view screen, implement a pinch zoom! Also inside implement an icon, by clicking on which the recipe is saved to favorite recipes ( 2nd screen )
- Implement a search by any criteria, choose convenient for yourself.
- Implement a filter for the list, a few items will be enough.
- Favorite recipes:
- Display a list of recipes that have been added to favorites.
- By swiping or by long pressing on an item from the list - implement removing it from your favorites!
- By clicking on an element, you can go to a detailed view of the recipe.

- Detail screen:
- Detailed recipe information
- Implement ingredients using UICollectionView, literally photo + name, that's enough.

Requirements:
- Use MVP + Router + Assembly
- Use layout only from the code! (SnapKit)
- Transitions between screens strictly through Routers
- Pictures using KingFisher to load.
- Activate indicators on all pictures.
- Use only UIKit, i.e. without the help of SwiftUI
- Transfer the network layer separately, to the service.
- Minimum version of iOS 13.
- To work with the network, use either URLSession or Alamofire, it's already how and what you like.
- Design at your discretion, the main thing is that the collections should be on the detailed one, and the table on the main one!
