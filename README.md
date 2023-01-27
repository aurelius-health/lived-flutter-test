# Lived Chat

In this Flutter case study you will be creating a basic chat feature where you can send messages to yourself 😅. You will be starting with an empty/fresh Flutter project and implementing the requirements listed.

## Submitting project for review

Please ZIP up the flutter project, attach it to an email, and send it to brandon@lived.app and kane@lived.app

## Basic Requirements
- A chat page with the following:
    - Textfield at the bottom of the screen for inputting and sending a new message.
    - A list of previously sent messages sorted by newest at the bottom of the screen.  
    - Show a timestamp for each message but in a timeago format (eg: 2 mins ago).
    - A button to scroll back to the latest message which shows when scrolling through messages.
- Create a Message model for sending and retrieving messages.
- The saving and fetching of messages should happen through some kind of service implemented with a state management of your choice (though Riverpod is preferred).
- The standard Flutter ThemeData should be utilised for styling of textstyles, colors, etc.

## Bonus Requirements
- Use the Freezed package to create the Message model
- In this example there will be no backend implementation, but bonus points if you can abstract away the methods for fetching/creating chat messages, so that a backend implementation could be added in addition to the test implementation.
- Tests are not required, but if you would like to add some, feel free.

## Time Constraints

This test is designed to take between 1-4 hours

## Design example

Use this image as a guide when developing the UI. Pay special attention to the border of the message bubbles..

![UIExample](https://github.com/aurelius-health/lived-flutter-test/blob/master/assets/UIExample.png?raw=true)
