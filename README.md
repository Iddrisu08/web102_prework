# WEB102 Prework - Sea Monster Crowdfunding App

Submitted by: Iddrisu Abdul Razak Iddrisu

Sea Monster Crowdfunding App is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: 10 hours spent in total

## Required Features

The following **required** functionality is completed:

✅ **Introduction Section**
- Displays company background
- Shows real-time count of unfunded games
- Calculates and formats total dollars raised

✅ **Stats Dashboard**
- Shows total contributions (backers)
- Displays total dollars raised ($858,268)
- Highlights top 2 most funded games:
  1. Zoo Tycoon: The Board Game ($442,602)
  2. How to Read Minds 2 Kit ($147,975)

✅ **Our Games Section**
- Initially displays all 11 games
- Functional filter buttons:
  - **Show Unfunded Only** (4 games)
  - **Show Funded Only** (7 games)
  - **Show All Games** (11 games)

* [ ] The introduction section explains the background of the company and how many games remain unfunded.
* [ ] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [ ] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [ ] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

 **Search Functionality**
- Live search filters games by name
- Case-insensitive matching

 **Enhanced Game Cards**
- Displays funding progress (pledged/goal)
- Visual progress bars
- Hover animations

## Video Walkthrough

Here's a walkthrough of implemented features:

[![App Walkthrough](https://www.loom.com/share/74e65ec2b24e4e6d833f7e4c6894a0f1)](https://www.loom.com/share/74e65ec2b24e4e6d833f7e4c6894a0f1)

GIF created with Loom (video)

## Notes

Describe any challenges encountered while building the app.
## Development Journey

### Challenges Faced
1. **Data Formatting**  
   Initially struggled with `toLocaleString()` for currency formatting, but mastered number formatting.

2. **Filter Logic**  
   Debugged edge cases in funded/unfunded calculations to ensure accurate filtering.

3. **Search Implementation**  
   Required tuning the input event listener for optimal performance.

   ### Lessons Learned
- Deepened understanding of array methods (`filter`, `reduce`, `sort`)
- Improved DOM manipulation skills
- Gained experience with template literals and ternary operators
- Learned to implement responsive design principles

## Technical Details

**Tech Stack:**
- HTML5
- CSS3 (Flexbox, animations)
- JavaScript (ES6)

**Key Functions:**
- `addGamesToPage()` - Renders game cards
- `filterFundedOnly()` - Filters by pledge goals
- `calculateStats()` - Handles all dashboard metrics

## License

    Copyright © 2023 [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

