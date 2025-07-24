# ESM Equipment Tracker

A comprehensive web-based equipment loan tracking system designed for teams to manage equipment inventory, bookings, and detailed equipment information.

## Features

### 📅 Calendar-Based Tracking
- Full month calendar view with equipment loan visualization
- Color-coded equipment types for easy identification
- Click-to-book functionality for new loans
- Navigate between months to plan equipment usage

### 🔧 Equipment Management
- **Settings Panel**: Manage equipment types, quantities, and color codes
- **Add New Equipment**: Easily expand your inventory
- **Edit Equipment**: Update quantities as you acquire more equipment
- **Delete Equipment**: Remove obsolete equipment from tracking

### 📋 Detailed Equipment Database
- **Equipment Details**: Comprehensive database with serial numbers, calibration dates, and remarks
- **Smart Sorting**: Sort by name, type, serial number, calibration dates
- **Calibration Tracking**: Visual warnings for expired or expiring calibrations
- **Add/Delete Equipment**: Full CRUD operations for equipment details

### ✏️ Loan Management
- **Editable Loans**: Click on borrower names to edit loan details
- **Availability Tracking**: Automatic calculation of remaining equipment
- **Multi-borrower Support**: Multiple people can book equipment for the same date
- **Validation**: Prevents overbooking and ensures data integrity

## Equipment Types (Default)
- AT600 Flow Meter (1 unit)
- PT900 Flow Meter (2 units)
- Dent Logger (14 units)
- Thermistor (6 units)
- Agilent Data Logger (2 units)

## Getting Started

### Option 1: Simple Deployment
1. Download the `index.html` file
2. Open it directly in any modern web browser
3. No server setup required - runs entirely in the browser

### Option 2: GitHub Pages Deployment
1. Create a new GitHub repository
2. Upload the `index.html` file to the repository
3. Go to repository Settings → Pages
4. Select "Deploy from a branch" and choose your main branch
5. Your app will be available at `https://yourusername.github.io/repository-name`

### Option 3: Local Server (Optional)
If you prefer to run with a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## Usage Guide

### Making a Booking
1. Click on any calendar date
2. Fill in borrower name and site location
3. Select return date
4. Choose equipment quantities (only available amounts shown)
5. Click "Book Equipment"

### Editing a Loan
1. Click on the borrower's name (blue underlined text) in the calendar
2. Modify any details: name, site, return date, or equipment quantities
3. Click "Save Changes"

### Managing Equipment Settings
1. Click the "Settings" button in the top-right
2. Edit existing equipment: change names, quantities, or colors
3. Add new equipment types with custom colors
4. Delete equipment no longer in use
5. Click "Save Changes"

### Equipment Details Management
1. Click the "Equipment Details" folder icon
2. View comprehensive equipment database
3. Sort by any column (name, type, serial number, dates)
4. Add new equipment with full details
5. Track calibration expiry dates (red = expired, orange = expiring soon)

## Browser Compatibility
- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## Data Storage
- All data is stored locally in the browser session
- Data persists while the browser tab remains open
- For permanent storage, consider integrating with a backend database

## Customization
The application is highly customizable:
- Equipment types and quantities
- Color schemes for each equipment type
- Equipment details fields
- Calibration tracking periods

## Contributing
Feel free to fork this project and submit pull requests for improvements.

## License
This project is open source and available under the MIT License.

## Support
For issues or feature requests, please create an issue in the GitHub repository.

---

**ESM Equipment Tracker** - Streamlining equipment management for teams everywhere.