## Overview
BLAH BLAH BLAH

## Commands
- `/todo`
  - **summary:**
    - Adds a todo item to the todo list.
  - **params:**
    - **(*) Activity Name** - The name of the activity.
    - **(*) Note** - Any additional specifications. E.x. "All solar run 🔥".
    - **(*) Reward** - What is everyone getting from this? E.x. "Title", "Midnight Coup", "ROTN Weapons", etc.
    - **#OfGoblins** - Defaults to 3. This is how many players should join the activity. This tells the bot when the lobby is full so it can create a channel.
- `/todo-list`
  - **summary:**
    - Shows all todo items that aren't done. As well as pertinent activities from the Destiny APIs.
- `/todone`
  - **summary:**
    - Marks a todo item as done, which removes it from the todo list.
    - Deletes associated voice channel if it exists.
  - **params:**
    - **Item Id** - The id of the todo item that will be marked as done.
- `/register`
  - **summary:**
    - Registers you to participate in a specified todo item.
    - When a lobby is full, creates a voice channel for the activity.
    - Generates a fireteam invite link: /join itsG0b1in#3492 that you can copy into chat in-game to join your group.
  - **params:**
    - **Item Id** - The id of the todo item you're registering for.
- `/inspire`
  - **summary:**
    - Presents you with a subset of activities from the Destiny APIs. Use case for this is when the todo list is empty or there isn't anything you want to do on it. When you select an activity this will prompy you to create a todo item, and register you for the activity.
