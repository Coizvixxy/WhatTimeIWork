# 🎉 Holiday Calendar Project
## 📜 Table of Contents
<!-- TOC start (generated with https://github.com/derlin/bitdowntoc) -->

- [📖 Overview](#-overview)
- [✨ Features](#-features)
- [🔧 Installation](#-installation)
   * [🛠️ Prerequisites](#-prerequisites)
   * [📥 Steps](#-steps)
- [🚀 Usage](#-usage)
- [💻 Technologies](#-technologies)
- [📂 Data Source](#-data-source)
- [📸 Screenshots](#-screenshots)
- [🐞 Known Issues](#-known-issues)
- [✅ Testing](#-testing)
- [📞 Support](#-support)
- [📬 Contact](#-contact)
- [📄 License](#-license)

<!-- TOC end -->


<!-- TOC --><a name="-overview"></a>
## 📖 Overview

The **Holiday Calendar** is a web-based project designed to manage and display holidays and other notable dates in a user-friendly calendar format. Users can create custom time blocks, add notes, and view holidays for each day throughout the year.

<!-- TOC --><a name="-features"></a>
## ✨ Features

- **📅 Responsive Calendar Display**: Displays a full year's calendar with options to view additional years.
- **🌟 Holiday Highlights**: Automatically highlights holidays based on provided CSV data.
- **🧱 Custom Blocks**: Allows users to create and place custom time blocks on any day of the calendar.
- **📝 Editable Notes**: Users can add and edit notes directly on the calendar days.
- **💾 Data Persistence**: Holiday and note data are saved locally to allow for persistence across sessions.
- **↩️ Undo Functionality**: Supports undo operations to revert changes in the calendar data.

<!-- TOC --><a name="-installation"></a>
## 🔧 Installation

<!-- TOC --><a name="-prerequisites"></a>
### 🛠️ Prerequisites

- A modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, etc.)
- Internet connection (if fetching external data)

<!-- TOC --><a name="-steps"></a>
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

<!-- TOC --><a name="-usage"></a>
## 🚀 Usage

- **➕ Adding a Block**: Type the desired time block text in the input field and click `創建塊` or use predefined templates.
- **✏️ Editing Notes**: Click on any calendar day to add or edit notes directly.
- **🔍 Viewing Holidays**: Holidays are automatically highlighted and can be viewed by mousing over the relevant days.
- **🗑️ Removing Blocks or Notes**: Right-click on a block or editable area to remove content.
- **↩️ Undo Changes**: Use `Ctrl + Z` or `Cmd + Z` to undo recent changes.

<!-- TOC --><a name="-technologies"></a>
## 💻 Technologies

- **📄 HTML5**: Structure of the project.
- **🎨 CSS3**: Styling of the calendar and interactive components.
- **🖥️ JavaScript**: Functionality for interactive elements, local data storage management, and calendar generation.

<!-- TOC --><a name="-data-source"></a>
## 📂 Data Source

The project utilizes a CSV file named `msar-public-holidays-zh.csv` for holiday data. **By default, the holidays are based on the Macau Special Administrative Region's (MSAR) 2024 to 2025 holidays**.

<!-- TOC --><a name="-screenshots"></a>
## 📸 Screenshots

![image](https://cdn.discordapp.com/attachments/1297886322807148655/1298891848751910952/s1.png?ex=671b36cc&is=6719e54c&hm=21d3f10e5eed2e6b890d44405e4cf0cabd740241b3d120e974eaa50cee4f872a&)


*📅 The main calendar displaying holidays and custom blocks.*

![image](https://cdn.discordapp.com/attachments/1297886322807148655/1298891849230192720/s2.png?ex=671b36cd&is=6719e54d&hm=305604a82fb47b7f5e56d51e72c3c5e94bd1a2327492a377be824c29df979e4f&)

 
*📝 Adding notes to a specific date.*


<!-- TOC --><a name="-known-issues"></a>
## 🐞 Known Issues

- **🌍 Localization:** Currently supports only Chinese for holiday data; future updates may include additional languages.


<!-- TOC --><a name="-testing"></a>
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


<!-- TOC --><a name="-support"></a>
## 📞 Support

For issues, suggestions, or contributions, please contact the project maintainer at [iamkenny@protonmail.ch](mailto:iamkenny@protonmail.ch).

<!-- TOC --><a name="-contact"></a>
## 📬 Contact

- **👤 Project Maintainer:** Your Name
- **✉️ Email:** [iamkenny@protonmail.ch](mailto:iamkenny@protonmail.ch)
- **🐱 GitHub:** [Coizvixxy](https://github.com/coizvixxy)

<!-- TOC --><a name="-license"></a>
## 📄 License

This project is open source and available under the [MIT License](LICENSE.md).
