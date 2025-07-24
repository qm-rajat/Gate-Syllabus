# GATE Syllabus Planner

[**Visit the Live Website**](https://qm-rajat.github.io/Gate-Syllabus/)

An interactive, modern web app to help you plan, track, and enrich your GATE exam preparation. This tool combines a visual tree view and a detailed table for the syllabus, with advanced features for notes, resources, and progress tracking.

---

## Features

- **Interactive Tree View**: Visualize the syllabus by focus area and week, with animated expand/collapse, icons, and progress indicators.
- **Detailed Table View**: See all weeks/topics in a sortable, filterable table.
- **Search & Filter**: Instantly search and filter by week, topic, or focus area.
- **Progress Tracking**: Mark weeks as complete and see your progress as a percentage and bar.
- **Notes**: Add personal notes for each week/topic, and a global notes area for general study tips or formulas.
- **Resource Links**: Attach and view recommended books, videos, or web resources for each week.
- **Sample Questions**: Add and review sample GATE-style questions for each week.
- **Show/Hide Completed**: Optionally hide completed weeks in the tree view.
- **Expand/Collapse All**: Quickly open or close all nodes in the tree.
- **Export/Print Table**: Print the table or (future) export as CSV/PDF.
- **Keyboard Navigation**: Navigate the tree with arrow keys and expand/collapse with Enter/Space.
- **Responsive Design**: Works well on both desktop and mobile browsers.

---

## Usage

1. **Open `index.html` in your web browser.**
2. **Switch between Tree View and Table View** using the toggle buttons.
3. **Search or filter** using the bar and dropdown at the top.
4. **Mark weeks as done** with the checkbox in either view. Progress is tracked automatically.
5. **Add notes, resources, or questions** for any week by clicking the 📝, 🔗, or ❓ icons.
6. **Use the global notes area** at the bottom for your own formulas, reminders, or summaries.
7. **Show/hide completed weeks** in the tree with the toggle.
8. **Expand/collapse all** tree nodes with the provided buttons.
9. **Print the table** or (in future) export as CSV/PDF.

All your data is saved in your browser (localStorage). No server or account required.

---

## Customization

- **Add More Weeks/Topics**: Edit the `syllabusData` array in the HTML to add or modify weeks, topics, or focus areas.
- **Pre-fill Resources/Questions**: You can pre-populate the resources/questions for each week in the same array.
- **Change Colors/Style**: Adjust the CSS variables at the top of the `<style>` section for a different look.
- **Add More Features**: The code is modular and commented for easy extension (e.g., import/export, reminders, etc.).

---

## Browser Compatibility

- Works in all modern browsers (Chrome, Firefox, Edge, Safari, Opera).
- All features are client-side; no internet connection required after first load.
- Data is stored in localStorage—clearing browser data will erase your notes and progress.

---

## License

This project is for personal and educational use. You are free to modify and share it.

---

## Credits

Created with ❤️ by Rajat. 
