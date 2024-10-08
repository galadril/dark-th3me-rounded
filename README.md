# dark-th3me-rounded

This is a rounded adaptation of the original Domoticz dark th3me. 

For more details, check the original thread:
[Domoticz Dark Th3me](http://www.domoticz.com/forum/viewtopic.php?f=8&t=15546)

## Cloning the Theme into the Domoticz `styles` Folder

To download and install the `dark-th3me-rounded` theme directly to your Domoticz `styles` folder, follow these steps:

1. **Connect to Your Domoticz Server**  
   Open a terminal and connect to your Domoticz server via SSH (if you are working on a remote server).

2. **Navigate to the Domoticz Styles Directory**  
   Run the following command to navigate to the directory where Domoticz themes are stored:
   ```bash
   cd /path/to/your/domoticz/www/styles/
   ```
   Replace `/path/to/your/domoticz/` with the actual path to your Domoticz installation.

3. **Clone the Repository**  
   Once you are in the correct directory, use `git` to clone the `dark-th3me-rounded` repository:
   ```bash
   git clone https://github.com/your-repo/dark-th3me-rounded.git
   ```

4. **Verify the Installation**  
   Ensure that the folder `dark-th3me-rounded` is now present in the `styles` directory.

5. **Apply the Theme**  
   - Go to your Domoticz web interface.
   - Navigate to `Setup` > `Settings` > `Website Theme`.
   - Select `dark-th3me-rounded` from the dropdown menu.

That's it! The new theme should now be applied.

---

## Features
- **Rounded Elements:** The theme now includes more rounded corners for a modern look.
- **Device Information:**
  - White: Normal devices
  - Blue: Protected devices
  - Red: Devices not updated for a while
  - Yellow: Battery almost empty

---

## Screenshots
TODO
