# Unit2.Manual-Test-Suite

-------------------------  Test Case 1: Main Page Testing ------------------------------------------------
1. Open the Puppy Bowl application.
2. Check if the main page displays a well-formatted list of all players.
/ --> The program Loops through the array of player objects and differentiates between the bench and field players.
3. Confirm that the player cards are divided into two categories (players on the bench and field other players on the field)
4. Verify that all teammates (players assigned to the same team) are displayed.
5. Confirm that each player is shown with a "See details" button and a "Remove" button.

------------------------- Test Case 2: Player Details Testing ----------------------------------------------
1. Click on the "See details" button for a player.
2. Confirm that all the player's details are displayed as they are saved on the original API.
3. Verify that a larger version of the player's picture is shown.
4. Click the cancel button to return to the main list.

------------------------- Test Case 3: Remove Player Testing -----------------------------------------
1. Click on the "Remove" button for a player.
2. Confirm that the player is removed from the API and from the roster as well without a page refresh.

------------------------- Test Case 4: Adding Player(s) Testing -----------------------------------------
1. Locate the form for adding a new player.
2. Enter a player name, breed, team ID, and a valid image URL.
3. Select a status option (bench or field)
4. Click the submit button.
5. Confirm that a player is added to the API and to the main list without a page refresh.

------------------------- Test Case 5: Input validation Testing -----------------------------------------
1. Locate the form for adding a new player.
2. submit an empty form.
3. Verify that an appropriate error message is displayed for invalid player name input.
4. Relocate the form 
5. Enter a player name and leave the other input fields blank.
6. Click the submit button.
7. Confirm that an error message is displayed for the missing breed.
8. Relocate the form 
9. Enter a player name and breed, and leave the other input fields blank.
10. Click the submit button.
11. Confirm that an error message is displayed for invalid image URL input.
12. Relocate the form 
13. Enter a player name, breed, and image Url, and leave the other input fields blank.
14. Click the submit button.
15. Verify that an error message is displayed for invalid status selection.
16. Relocate the form 
17. Enter a player name, breed, and image URL, and select a valid status option, but leave the team Id input field blank.
18. Confirm that a new player is added to the unassigned team (team Id input is optional).