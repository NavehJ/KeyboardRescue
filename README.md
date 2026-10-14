# KeyboardRescue 

A lightweight, automated tool designed to detect, translate, and fix text typed in the wrong keyboard layout (specifically alternating between Hebrew and English layouts). No more deleting entire sentences just because you forgot to press `Alt+Shift`.

##  Features
- **Auto-Detection:** Automatically spots when text looks like accidental keyboard layout gibberish (e.g., typing "aca" instead of "ששש").
- **Instant Translation:** Seamlessly flips the characters back to the intended language layout.
- **Lightweight & Fast:** Runs efficiently in the background

##  Repository Structure
The project is built using **.NET / C#**:
- `/src`: Core application logic, keyboard hooks, and translation engines.
- `/tests`: Automated testing suite ensuring highly accurate layout conversion.
- `FIX_REPORT.md`: Comprehensive log tracking resolved issues, bugs, and patch notes.


### Prerequisites
- .NET 8.0 SDK or higher
- Visual Studio 2022 (supports the new `.slnx` solution format)

## Installation & Local Setup

### 1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/NavehJ/KeyboardRescue
   ```
 -  Open `KeyboardRescue.slnx` using Visual Studio.
 - Build the solution (`Ctrl + Shift + B`) and run the project.

   
### 2. Download it by the `KeyboardRescue.exe` file:
- Download `KeyboardRescue.exe` from the Assets section below.
- Double-click to run the application.
- Note for Windows users: Since this application is new and self-published, Windows SmartScreen may show a warning. Click "More info" and then "Run anyway" to launch it safely.
