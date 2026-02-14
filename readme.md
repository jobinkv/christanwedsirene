# Christian & Irene Wedding Website

A responsive, single-page wedding invitation website for Christian & Irene.

## 🚀 How to Run Locally

### Option 1: The Simple Way (Double Click)
Simply navigate to this folder and double-click `index.html`. It will open in your default web browser.

### Option 2: Using Python (Recommended)
If you have Python installed, you can run a local server to view the site. This is better for testing on mobile devices connected to the same WiFi.

1. Open your terminal/command prompt.
2. Navigate to this directory:
   ```bash
   cd /Users/jobin/christanwedsirene/christanwedsirene
   ```
3. Run the following command:
   ```bash
   python3 -m http.server
   ```
4. Open your browser and go to `http://localhost:8000`.

### Option 3: VS Code Live Server
If you are using VS Code:
1. Install the "Live Server" extension.
2. Right-click `index.html` and select "Open with Live Server".

## 📱 Features
- **Responsive Design**: Works on Desktop and Mobile.
- **Countdown Timer**: Counts down to April 15, 2026.
- **Events Map**: Direct links to Google Maps for the Church and Reception.
- **RSVP Form**: A mock RSVP form.

## 🛠️ Customization
- **Images**: Replace images in `assets/images/`.
- **Colors/Fonts**: Edit `css/style.css` (check the `:root` variables).
- **Text/Details**: Edit `index.html`.

## 🌐 Deployment (GitHub Pages)
1. Push this repository to GitHub.
2. Go to **Settings** > **Pages**.
3. Select the `main` branch as the source.
4. Your site will be live at `https://your-username.github.io/repo-name`.
