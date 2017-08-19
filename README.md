# Pokemon-Search-iOS
This app makes use of Apple maps and fetches the current location of the user. The user can spot pokemons around him and navigate to the pokemons he/she wants to catch.

Tool: XCode 8.3.3

Language: Swift 3

Instructions to configure Firebase:

Open terminal
Go to the downloaded project folder in the terminal.
Install cocoapods by typing "sudo $ gem install Cocoapods" in the terminal.
Type pod init and enter
Type pod install and enter.
Then, open the file with the extension ".xcworkspace"
Run

The Firebase database rules should be set as follows

{
  "rules": {
    ".read": true,
    ".write": true,
    ".indexOn": ["g"]
  }
}
