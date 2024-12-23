# Prework - DeTECTify2 rough draft

Submitted by: Idiris Muumin

Detectify is a simple and powerful app that helps users make healthier choices by identifying product ingredients through a photo of the product’s cover. 
The app will recognizes the product and retrieves its ingredient list from trusted online sources. 
It then analyzes the ingredients, categorizing them as healthy or harmful, and gives the product a clear numerical score based on its safety. 
Users can see detailed explanations for each ingredient and even get suggestions for healthier alternatives. 
With Detectify, making informed decisions about the products you use has never been easier or more convenient.

Time spent: 1.5 hours spent in total

## Required Features

The following **required** functionality is completed:

- [X] Users are see a screen with three labels and a button
- [X] Tapping the button changes the screen color to a random color
 
## Video Walkthrough


<div>
    <a href="https://www.loom.com/share/3969ee02657943989e88c71975d29376">
    </a>
    <a href="https://www.loom.com/share/3969ee02657943989e88c71975d29376">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/3969ee02657943989e88c71975d29376-9553e0819ef80647-full-play.gif">
    </a>
  </div>

## App Brainstorming (Step 4)
Yuka - a mobile application that allows users to scan the barcodes of food and cosmetic products to assess their health impact

1. Ease of information : Upon scanning, Yuka provides a rating and detailed information about the product's nutritional quality, presence of additives, and, for cosmetics, the safety of ingredients
2. The interface is simple and intuitive, making it accessible for users of all ages.

CapybaraGo - an adventure based game that encourages users to gain points to level up

1. Each adventure is different, with randomized encounters that keep the game fresh and replayable
2. A captivating story motivates players to progress through the game, with branching narratives based on choices.

Notion - All in one productivity tool

1.  Notion combines features like note-taking, task management, project planning, databases, and wikis into a single platform.
2. Notion works on desktop, web browsers, and mobile devices, ensuring your workspace is always within reach.
## Notes

Describe any challenges encountered while building the app.

I had some trouble connecting the UI to the logic needed to make the button work. To make the button interactive, I connected its action to the logic in the ViewController.swift 
file by opening the Storyboard, enabling the Assistant editor, and using Control + Drag from the button to the ViewController class to create an IBAction. I named the action 
changeBackgroundColor and set its type to UIButton. Since it was my first time creating an application in Swift, I encountered issues but resolved them by creating a new version 
of the project and identifying the error.
## License

    Copyright 2024 Idiris Muumin

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
