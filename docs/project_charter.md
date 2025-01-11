# Project Charter

## Project Overview
Mobile web app designed to allow families and roommates to manage a shared grocery list

**Project Name:**  
GoGrocery


## Objectives

1. Allow users access to a shared grocery list using a list key (think kahoot access keys) 
2. Users should be able to add items, remove items, mark items as 'added' and 'received'; these items will be stored in a new list 'Completed' based on the 'received' date.
3. Adding items will hold attributes: name, quantity, and notes.
4. 'added' items will be used similar to a checklist where they will be highlighted in green and there will be a received button at the bottom of the screen much like a submit button that can be pressed after checking out or receiving order.
5. When marking 'adding' items of multiple quanity you will have to add the quantity added and that will be check against the numeric quantity on the list and the remaining quanitity will be left on the list. 

## Scope

**In Scope:**  
- Allow users to create and share a grocery list with a unique access key (similar to Kahoot's access keys).
- Users can add, remove, and mark items as 'added' and 'received.'
- Items marked as 'received' will be moved to a "Completed" list with timestamps.
- Item attributes such as name, quantity, and notes will be tracked.
- Items in the 'added' state will be highlighted in green, and users will be able to mark them as 'received' once checked out or the order is complete.
- Users can update quantities for items and track remaining quantities.
- Design the app for a mobile web interface for ease of use on phones.

**Out of Scope:**  
- Integration with external platforms (e.g., grocery stores, delivery services) is not included in the initial version.
- User authentication and account management will not be implemented in the initial version.
- Any advanced analytics or reporting features are not part of this version.

## Risks and Issues

- **Data Loss or Corruption:** There is a risk of losing user data (e.g., grocery lists, quantities) due to technical issues, such as server downtime, database corruption, or improper handling of the data.
- **Security Vulnerabilities:** Since users will access a shared list using a key, there's a risk of unauthorized access or data breaches if the access key is not properly secured or if there's inadequate encryption of user data.
- **Poor User Adoption:** Users may not find the app intuitive or useful, leading to poor engagement and adoption. This could be due to a non-user-friendly interface or lack of features they expect.
- **Cross-device Compatibility Issues:** The app might face challenges with compatibility across different mobile browsers and screen sizes, leading to inconsistent user experiences.
- **Scalability Issues:** As the user base grows, the app may face performance issues, such as slow load times or lag in updating the grocery list in real time, particularly if the app doesn't handle a large number of users or items effectively.

## Success Criteria

- Users are able to access the list via a key [ ]
- Users can add items with a name, quantity, and notes [ ]
- Users can edit items (name, quantity, and notes) [ ]
- Users can delete items from the list [ ]
- Users can mark items as added and received [ ]
- Received items are stored in a new list for each date [ ]
- Received items can be checked against the listed quantity, and the remaining quantity will stay on the list [ ]

## Stretch Goals
- **Highlighting items:** Green if added & quantity matches the listed quantity [ ]
- **Highlighting items:** Yellow/orange if the added quantity does not equal the listed quantity [ ]
- **Auto Complete:** When typing in an item name, the app will suggest names based on previously added items [ ]
- **Database Cleanup:** The app will store 'Completed' lists for only six months [ ]


