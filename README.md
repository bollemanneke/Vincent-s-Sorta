Vincent's Sorta

Vincent's Sorta is a web-based tool designed for interactive ranking and sorting of items using a round-robin, bottom-up merge sort approach. It allows users to compare items in pairs, progressively determining their preferred order while offering options such as undo, removal, optional shuffling, and saving/loading sorting sessions.

1.	Inspiration

This app was inspired by, and therefore very closely modelled on, Sorta, available at Sorta.app. Although highly effective, it did not allow more than 50 items to be sorted, imposed a character limit and also made users publish everything on Mastodon before sorting was possible, which the author of this app did not find convenient.

2.	Features

-	Interactive Sorting: Users compare two items at a time and choose their preference.
-	Round-Robin Merge Sorting: Items are ranked progressively using a structured merge sort process.
-	Undo Functionality: Reverse the last decision at any point.
-	Item Removal: Remove items from sorting without affecting the order of others.
-	Shuffle Option: Randomize the initial order before sorting starts.
-	Save & Load Sessions: Export and import sorting sessions to resume later.
-	Automatic Ranking: Once sorting is complete, the final ranked list is displayed.

3.	How to Use

Enter Items:

-	Type or paste items into the text box (one per line).
-	Choose whether to shuffle them before sorting. This might help to avoid initial bias.
-	Click Start.

Sorting Process:

-	The app will present two items at a time.
-	Click on the item you prefer.
-	Alternatively, click Remove to exclude an item. Removing an item does not reset the sorting.

Undo & Save:

-	Use Undo to revert the last choice.
-	Click Save to File to store progress.

View Final Results:

-	Once all comparisons are made, a sorted list will be displayed.

Loading a Previous Session:

-	Click Load from File and select a previously saved JSON file.

4.	Technologies Used

-	Chat GPT 4O and O1, without which this app would not have been possible.
-	HTML, CSS, JavaScript (Frontend)
-	Blob-based File Saving & Loading for session management
-	Merge Sort Algorithm adapted for interactive ranking

5.	Installation & Setup

No installation is required—simply open the provided HTML file in any modern web browser. Or use this link:
https://bollemanneke.github.io/Vincent-s-Sorta/


6.	Notes

-	The app requires JavaScript to be enabled.
-	Large lists may take longer to sort due to manual comparisons.
-	Although the app uses a merge sort algorithm, users will not be asked to sort individual groups at first. This keeps the sorting process as varied as possible.
