# Ryan Jacobell - E-Portfolio

A modern dark-themed portfolio website for an Exercise Science student with a Pre-Physical Therapy emphasis.

## Running on Localhost

Choose one of the following methods to run the site locally:

### Option 1: Python (Recommended)

**Python 3:**
```bash
cd /Users/ryanjacobell/Desktop/port
python3 -m http.server 8000
```

**Python 2:**
```bash
cd /Users/ryanjacobell/Desktop/port
python -m SimpleHTTPServer 8000
```

Then open: http://localhost:8000

### Option 2: Node.js

Install a simple server globally:
```bash
npm install -g http-server
```

Run it:
```bash
cd /Users/ryanjacobell/Desktop/port
http-server -p 8000
```

Then open: http://localhost:8000

### Option 3: PHP

```bash
cd /Users/ryanjacobell/Desktop/port
php -S localhost:8000
```

Then open: http://localhost:8000

### Option 4: Live Server (VS Code)

1. Install the "Live Server" extension in VS Code
2. Open the `port` folder in VS Code
3. Right-click `index.html` and select "Open with Live Server"

## Project Structure

```
port/
├── index.html    # Main HTML file
├── styles.css    # Stylesheet (dark theme)
├── script.js     # JavaScript for interactivity
└── README.md     # This file
```

## Customization

Update the following in `index.html`:

- **Personal Info**: Name, university, GPA, graduation date
- **Contact**: Email, phone, location, LinkedIn URL
- **Experience**: Job titles, dates, descriptions
- **Mission Statement**: Your personal mission
- **Career Goals**: Your short/mid/long-term goals
- **Skills**: Add or remove skill tags

To change colors, edit the CSS variables at the top of `styles.css`:

```css
:root {
    --bg-primary: #0a0a0f;
    --accent-primary: #6366f1;
    --gradient-start: #6366f1;
    --gradient-end: #a855f7;
}
```
