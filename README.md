# Storage Inspector

A powerful Chrome extension for security researchers to inspect and edit localStorage, sessionStorage, and Cookies.

## Features

- 🔍 **Inspect Storage**: View localStorage, sessionStorage, and Cookies for any website
- ✏️ **Edit Values**: Create, modify, and delete storage items with ease
- 🌙 **Dark/Light Mode**: Beautiful UI with theme toggle support
- 📤 **Export Data**: Export all storage data to JSON file
- 📥 **Import Data**: Import storage data from JSON file
- 🔎 **Search**: Quickly find items by key or value
- 🍪 **Full Cookie Support**: Edit all cookie attributes (domain, path, secure, httpOnly, sameSite, expiration)

## Installation

### Step 1: Generate Icons

1. Open `icons/generate-icons.html` in Chrome
2. Click each "Download" button to save the icon files
3. Save them to the `icons` folder as:
   - `icon16.png`
   - `icon32.png`
   - `icon48.png`
   - `icon128.png`

### Step 2: Load Extension in Chrome

1. Open Chrome and navigate to `chrome://extensions/`
2. Enable "Developer mode" (toggle in top right)
3. Click "Load unpacked"
4. Select the `storage-inspector` folder
5. The extension icon should appear in your toolbar

## Usage

1. Navigate to any website
2. Click the Storage Inspector icon in your toolbar
3. Browse localStorage, sessionStorage, or Cookies using the tabs
4. Use the search bar to filter items
5. Click on an item to expand and view its full value
6. Use the action buttons to copy, edit, or delete items
7. Use Export/Import to backup or restore storage data

## Permissions

- **activeTab**: Access the current tab to read/write storage
- **cookies**: Read and modify cookies
- **scripting**: Execute scripts to access localStorage/sessionStorage
- **storage**: Store extension preferences (theme)

## Security Note

This extension is designed for security research and development purposes. Be careful when importing data from untrusted sources.

## License

MIT License - Free for personal and commercial use.

