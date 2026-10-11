OmniSearch Hub 🔎

OmniSearch Hub is a modern, responsive, multi-engine search dashboard that allows users to search across multiple platforms from one convenient interface.

✨ Features

- Multi-Engine Search: Search using Google, Bing, Yahoo, DuckDuckGo, YouTube, and Microsoft Copilot.
- Single Search: Enter a query and choose your preferred search engine.
- Engine Dashboard: Access multiple search providers from one interface.
- Split Comparison: Compare search results across different engines.
- Search History: Save previous searches locally and rerun or remove them.
- Saved Search Suggestions: Quickly access previous queries.
- Quick Engine Filters: Select your preferred search providers.
- Keyboard Shortcuts: Press "/" to focus the search field and "Escape" to dismiss or close supported interface elements.
- Responsive Design: Works on desktops, tablets, and mobile devices.
- Modern UI: Features a dark theme, glassmorphism effects, and a clean interface.
- Privacy-Friendly Storage: Search history is stored locally in your browser using "localStorage".

🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Tailwind CSS
- Font Awesome 6
- Google Fonts — Inter
- Browser Local Storage

📂 Project Structure

OmniSearch-Hub/
├── omnisearch-hub.html
└── README.md

The project uses a single HTML file for the main application, with external libraries loaded through CDNs.

🚀 Getting Started

Option 1: Open Directly

1. Download or clone the project.
2. Locate "omnisearch-hub.html".
3. Open the file in a modern web browser.
4. Start searching.

An active internet connection is required for external fonts, libraries, and search providers.

Option 2: Run Using a Local Server

If you have Python installed, open a terminal in the project directory and run:

python -m http.server 8000

Then open the following address in your browser:

http://localhost:8000

📖 How to Use

1. Search the Web

- Enter a keyword, question, or topic in the search field.
- Select a search engine.
- Submit your query to open the relevant provider.

2. Compare Search Engines

- Open the split-comparison feature.
- Enter your search query.
- Choose the available engines you want to compare.
- Review the results where the providers permit embedded viewing.

Note: Some search providers block iframe embedding. If a provider cannot display inside the dashboard, open its results in a separate browser tab.

3. Manage Search History

- Previous searches may be saved automatically in your browser.
- Select a saved query to search again.
- Remove individual entries or clear the history using the available controls.

Search history is stored in the current browser and device. It is not automatically synchronized across devices.

4. Use Keyboard Shortcuts

Shortcut| Action
"/"| Focus the search field
"Escape"| Dismiss or close supported interface elements

⚙️ Customization

You can customize the dashboard by editing "omnisearch-hub.html".

Change the Theme

Modify the CSS styles or Tailwind configuration to update the colors, backgrounds, spacing, and visual effects.

Add or Modify Search Engines

Update the JavaScript engine configuration to change provider names, search URLs, icons, or other supported settings.

Adjust Search History

Modify the JavaScript history settings to change the maximum number of saved searches or how history is managed.

🔒 Privacy and Security

- Search history is stored in browser local storage.
- Search queries submitted to external providers are subject to those providers' privacy policies.
- The application does not require a backend server for its core functionality.
- Avoid entering passwords, financial details, or other sensitive information into search queries.

⚠️ Known Limitations

- Some search engines prevent their pages from being displayed inside embedded frames.
- Search results are provided by external search engines; OmniSearch Hub does not independently index or merge the web.
- External provider URLs and functionality may change over time.
- Browser pop-up restrictions may affect features that open new tabs.
- The dashboard requires an internet connection for external services and resources.

🧰 Troubleshooting

The page does not load correctly

- Check your internet connection.
- Use an updated browser.
- Confirm that external CDN resources are accessible.

A search engine does not display inside the dashboard

- The provider may block embedded content.
- Open the search directly in a new tab instead.

Search history disappears

- Check whether browser storage is enabled.
- Private browsing, cleared browser data, or browser settings may remove saved history.

A new tab does not open

- Check your browser's pop-up blocker and allow the action if appropriate.

🌐 Browser Compatibility

Designed for modern browsers, including:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

Compatibility may vary depending on browser settings and external provider restrictions.

📄 License

No specific license has been assigned to this project. Add a license file if you intend to distribute the source code publicly.

👨‍💻 Project

Project Name: OmniSearch Hub
Type: Multi-Engine Search Dashboard
Platform: Web
Core Technologies: HTML, CSS, and JavaScript

---

OmniSearch Hub — One interface. Multiple ways to explore the web.
