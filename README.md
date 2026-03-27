Spark MIDI Bridge
A lightweight, one-click utility to connect any MIDI controller to Positive Grid Spark amps using your PC as the "brain".



Versions
Version	Features	Status	Recommended for
v1.0.2. (Latest)	Universal MIDI Support	Stable	Everyone (Best choice)
v1.0.0.	Initial release (M-VAVE only)	Legacy	Only for M-VAVE Chocolate
Getting Started
1. Download Files
Click the green <> Code button at the top of this page. or dowload file from Release Page (Latest version)
Select Download ZIP.
Extract the archive to a convenient folder.
📖 Quick Start
Important

For M-VAVE Users: You MUST pair your pedal via Windows Bluetooth settings (FootCtrlPlus device) even if you are using a USB connection. If you don't pair it, the pedal will constantly enter "searching mode" (blinking light), which can cause connection instability and lag. Pairing it once ensures the pedal stays "locked" and stable.

Prepare your Amp: Turn on your Spark. Ensure it's NOT connected to the Spark mobile app.
Connect MIDI: Plug your controller into the PC (USB is recommended for stability).
Run: Open SparkMidiBridge.exe.
Select the amp model from the drop-down list.
Done: Wait for SPARK: ONLINE and PEDAL: READY.
Ensure your pedal buttons send unique IDs (0, 1, 2, 3 or 1, 2, 3, 4) via CubeSuite. If the app sees the same "Button ID" for all presses, check your pedal's CC/PC settings

For macOS In work

🛠 Hardware Compatibility
I am actively looking for testers for other models!

Device	Status	Notes
Spark 40	✅ Working	Fully tested by developer
Spark 2	⏳ Testing	Should connect automatically. Need data!
Spark MINI	⏳ Testing	Need confirmation on Bluetooth ID.
Spark GO	⏳ Testing	Need confirmation on Bluetooth ID.
M-VAVE Chocolate	✅ Working	Best experience via USB or Bluetooth.
🧪 How to help
If you own a Spark 2, MINI, or GO, you can help even if you don't have a MIDI pedal:

Run the app with your amp turned on.
Change the amp model from the drop-down list
Wait and check if the log says SPARK: ONLINE.
If it doesn't, please Open an Issue and tell me your amp model and how it's named in your Windows Bluetooth settings.
📜 Credits & Acknowledgments
This project uses research and protocol documentation from the following open-source projects:

SparkMIDI — for the original Sysex command structures.
⚖️ Legal Disclaimer & Safety
USE THIS SOFTWARE AT YOUR OWN RISK. 1. Not Official: This project is an independent, community-driven tool and is NOT affiliated with, authorized, maintained, or endorsed by Positive Grid LLC. 2. Trademarks: "Spark", "Positive Grid", "Spark LIVE", and all related product names are trademarks or registered trademarks of Positive Grid LLC. They are used here solely for interoperability and identification purposes. 3. No Liability: The author is not responsible for any potential damage to your amplifier, MIDI hardware, computer, or for any loss of data. 4. Experimental: Support for newer models (Spark 2, Spark LIVE) is based on community research and is considered experimental. 5. Testing: Always test your setup thoroughly before using it in a live performance or critical environment.

This software is provided "as is" under the GPL-3.0 License, without warranty of any kind.
