# 🎉 Holiday Calendar Project
## 📜 Table of Contents
- [📖 Overview](#overview)
- [✨ Features](#features)
- [🔧 Installation](#installation)
- [🚀 Usage](#usage)
- [💻 Technologies](#technologies)
- [📂 Data Source](#data-source)
- [📸 Screenshots](#screenshots)
- [🐞 Known Issues](#known-issues)
- [✅ Testing](#testing)
- [📞 Support](#support)
- [📬 Contact](#contact)

## 📖 Overview

The **Holiday Calendar** is a web-based project designed to manage and display holidays and other notable dates in a user-friendly calendar format. Users can create custom time blocks, add notes, and view holidays for each day throughout the year.

## ✨ Features

- **📅 Responsive Calendar Display**: Displays a full year's calendar with options to view additional years.
- **🌟 Holiday Highlights**: Automatically highlights holidays based on provided CSV data.
- **🧱 Custom Blocks**: Allows users to create and place custom time blocks on any day of the calendar.
- **📝 Editable Notes**: Users can add and edit notes directly on the calendar days.
- **💾 Data Persistence**: Holiday and note data are saved locally to allow for persistence across sessions.
- **↩️ Undo Functionality**: Supports undo operations to revert changes in the calendar data.

## 🔧 Installation

### 🛠️ Prerequisites

- A modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, etc.)
- Internet connection (if fetching external data)

### 📥 Steps

1. **Download the Project Files**
   - Clone the repository:
     ```bash
     git clone https://github.com/your-username/holiday-calendar.git
     ```
   - Or download the ZIP archive and extract it.

2. **Ensure Data File Availability**
   - Make sure the `msar-public-holidays-zh.csv` file is located in the appropriate directory as referenced in the project.

3. **Open the Application**
   - Navigate to the project directory.
   - Open `index.html` in your preferred web browser.

## 🚀 Usage

- **➕ Adding a Block**: Type the desired time block text in the input field and click `創建塊` or use predefined templates.
- **✏️ Editing Notes**: Click on any calendar day to add or edit notes directly.
- **🔍 Viewing Holidays**: Holidays are automatically highlighted and can be viewed by mousing over the relevant days.
- **🗑️ Removing Blocks or Notes**: Right-click on a block or editable area to remove content.
- **↩️ Undo Changes**: Use `Ctrl + Z` or `Cmd + Z` to undo recent changes.

## 💻 Technologies

- **📄 HTML5**: Structure of the project.
- **🎨 CSS3**: Styling of the calendar and interactive components.
- **🖥️ JavaScript**: Functionality for interactive elements, local data storage management, and calendar generation.

## 📂 Data Source

The project utilizes a CSV file named `msar-public-holidays-zh.csv` for holiday data. **By default, the holidays are based on the Macau Special Administrative Region's (MSAR) 2024 to 2025 holidays**.

## 📸 Screenshots

![Calendar View](https://hackmd.io/_uploads/SJulOHPlkx.png)

*📅 The main calendar displaying holidays and custom blocks.*

![image](https://hackmd.io/_uploads/Hy1cdBwx1e.png)
*📝 Adding notes to a specific date.*


## 🐞 Known Issues

- **🌍 Localization:** Currently supports only Chinese for holiday data; future updates may include additional languages.


## ✅ Testing

1. **🔓 Open the Application:**
   - Open `index.html` in a web browser.

2. **🔍 Verify Features:**
   - **📅 Calendar Display:** Ensure the calendar correctly displays the current year.
   - **🌟 Holiday Highlights:** Check that holidays from the CSV are highlighted.
   - **📝 Add/Edit Notes:** Add a note to a date and verify it's saved and editable.
   - **↩️ Undo Functionality:** Make changes and use `Ctrl + Z` or `Cmd + Z` to undo them.

3. **🌐 Cross-Browser Testing:**
   - Test the application in different browsers to ensure compatibility.

4. **📱 Responsive Design:**
   - Resize the browser window or use developer tools to verify the calendar is responsive on various screen sizes.


## 📞 Support

For issues, suggestions, or contributions, please contact the project maintainer at [iamkenny@protonmail.ch](mailto:iamkenny@protonmail.ch).

## 📬 Contact

- **👤 Project Maintainer:** Your Name
- **✉️ Email:** [iamkenny@protonmail.ch](mailto:iamkenny@protonmail.ch)
- **🐱 GitHub:** [Coizvixxy](https://github.com/coizvixxy)

## 📄 License

This project is open source and available under the [MIT License](LICENSE.md).