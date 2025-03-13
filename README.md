# Sorta - A Web App for Ranking Items

## Overview
Sorta is a simple, interactive web app that allows users to rank items using one of two sorting methods. Users enter a list of items, choose a sorting method, and then make pairwise comparisons to determine the ranking.

## Features
- **Smart Sorting (Efficient Ranking)**: Uses a **merge-sort-based** approach to minimize the number of comparisons, making it the fastest option.
- **Thorough Sorting (Compare Every Item with Every Other)**: Compares every possible pair of items for a **more detailed ranking** but takes longer.
- **Shuffle Option**: Allows users to randomize the order before sorting starts.
- **Undo Functionality**: Users can go back to previous steps if they make a mistake.
- **Save and Load**: Users can save their progress and load rankings from a file.

## How to Use
1. **Enter Items**: Type a list of items, one per line.
2. **Select a Sorting Method**:
   - **Smart Sorting** (default): Faster, uses a structured merge-sort approach.
   - **Thorough Sorting**: Slower, but compares every item with every other.
3. **Start Sorting**: Click the "Start" button.
4. **Make Comparisons**: Choose between two items in each comparison until the ranking is determined.
5. **Undo Mistakes**: Click "Undo" to go back to the previous step.
6. **View Results**: The sorted list is displayed when all comparisons are complete.
7. **Save/Load Data**: Save your ranking to a file or load a previous ranking.

## Sorting Methods Explained

### **Smart Sorting (Efficient Ranking)**
- Uses a **merge-sort-inspired** approach.
- Breaks the list into smaller groups and merges them **step by step**.
- Requires only **O(n log n)** comparisons, making it **very efficient** for long lists.
- Best when speed is the priority.

### **Thorough Sorting (Compare Every Item with Every Other)**
- Compares **every item against every other item**.
- Items are ranked based on their total "wins" in these comparisons.
- Requires **O(n²)** comparisons, making it much **slower** for large lists.
- Best when a **fully exhaustive** ranking is needed.

## System Requirements
- A modern web browser (Chrome, Firefox, Edge, Safari).
- JavaScript must be enabled.

## Notes
- **Cannot select both sorting methods at once**.
- The shuffle feature randomizes item order before sorting starts.
- The undo feature allows for full history-based reversal of actions.

## License
This project is free to use and modify. No license restrictions apply.

## Contact
For any questions or improvements, feel free to contribute!

