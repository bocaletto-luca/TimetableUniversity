# Timetable University

**Timetable University** is a modern, responsive one-page webapp for students to schedule courses by drag-and-drop. No installation or registration needed—just HTML5, CSS3, and vanilla JavaScript. Import/export your timetable in JSON, add/edit/delete courses, detect conflicts, and print your schedule with one click.

---

## 📺 Live Demo

https://bocaletto-luca.github.io/TimetableUniversity/index.html

---

## 🚀 Features

- Responsive CSS Grid timetable (Monday–Friday, 8 AM–8 PM)  
- Drag & drop to assign courses into time slots  
- Add, edit & delete course entries on the fly  
- Import and export full state (courses & schedule) as JSON  
- Conflict detection when dropping into occupied slots  
- Double-click to remove scheduled entries  
- Print-ready layout via native `window.print()`  
- Fully offline after initial load (no external APIs)

---

## 📁 Repository

https://github.com/bocaletto-luca/TimetableUniversity

---

## 🛠️ Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari)

### Installation

1. Clone the repository  
   ```bash
   git clone https://github.com/bocaletto-luca/TimetableUniversity.git
   ```
2. Or download the ZIP and extract.

### Running Locally

1. Open `index.html` in your browser.  
2. Use the sidebar to add courses and drag them into the timetable grid.  
3. Import or export your data via the **Import JSON** / **Export JSON** buttons.  
4. Click **Print Timetable** to generate a printable version.

---

## 📝 Usage

1. **Add a Course**  
   - Enter the course name.  
   - Select the faculty.  
   - Click **Add**.  

2. **Schedule a Course**  
   - Drag a course item from the sidebar.  
   - Drop it into any empty time slot.  
   - Double-click a scheduled block to remove it.

3. **Import / Export JSON**  
   - **Import**: Load a previously saved `timetable.json`.  
   - **Export**: Download the current state as `timetable.json`.

4. **Print**  
   - Click **Print Timetable** for a clean, print-optimized view.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to:

1. Fork the repository  
2. Create a new branch (`git checkout -b feature/YourFeature`)  
3. Commit your changes (`git commit -m 'Add new feature'`)  
4. Push to the branch (`git push origin feature/YourFeature`)  
5. Open a Pull Request  

---

## 📄 License

This project is licensed under the [GPL License](LICENSE).

---

## 👤 Author

**Bocaletto Luca**  
- GitHub: [@bocaletto-luca](https://github.com/bocaletto-luca)  

---
