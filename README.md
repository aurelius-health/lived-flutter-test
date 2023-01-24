# Lived Chat

In this Flutter case study you will be creating some UI for a basic chat feature. You will be starting with an empty/fresh Flutter project and implementing the requirements listed.

## Basic Requirements
- A chat page with the following:
    - Textfield at the bottom of the screen for inputting and sending a new message.
    - A list of previously sent messages sorted by newest at the bottom of the screen.  
    - Show a timestamp for each message but in a timeago format (eg: 2 mins ago).
    - A button to scroll back to the latest message which shows when scrolling through messages.
- Create a Message model for sending and retrieving messages.
- The saving and fetching of messages should happen through some kind of service implemented with a state management of your choice (though Riverpod is preferred).
- The standard Flutter ThemeData should be utilised for styling of textstyles, colors, etc.
- Implement using the folder structure stated below.

## Bonus Requirements
- Use the Freezed package to create the Message model
- In this example there will be no backend implementation, but bonus points if you can abstract away the methods for fetching/creating chat messages, so that a backend implementation could be added in addition to the test implementation.


## Folder Structure

Files should be grouped by feature, meaning that all files related to a certain feature (in this case: 'Chat') live in a that folder. We then group files by type, eg: Models, state, widgets.

An example folder structure could be:

- features
    - chat
        - state
            - chat_providers.dart
        - models
            - chat_model.dart
        - widgets
            - message_bubble.dart
        - chat_screen.dart

