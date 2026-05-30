Privacy Policy

AI EmergencyAct — Privacy Policy

Last updated: May 2026

Overview
AI EmergencyAct is designed with privacy as a core principle. The app does not collect, store, transmit, or share any personal data with the developer or any third party.

Data Collection
We collect no data. The app does not have a backend server, analytics, advertising SDK, or any form of telemetry.

Permissions Used and Why

| Permission | Why It's Needed | Data Leaves Device? |
|---|---|---|
| Camera | Video recording for evidence capture | No — saved locally only |
| Microphone | Audio recording for evidence capture | No — saved locally only |
| Location | Detect country to resolve correct emergency number; find nearby police stations; share location via iOS share sheet | No — processed on-device via Apple's frameworks |
| Photo Library | Save recorded video to the user's Photos | No — written to user's own library only |

Location Data  
Location is obtained via Apple's Core Location framework and processed entirely on-device. It is used only to:  
• Determine the correct local emergency number (e.g. 911, 000, 999)  
• Find nearby police stations via Apple Maps  
• Allow the user to share their coordinates via the iOS system share sheet (the user controls where and to whom)  

The developer never receives, stores, or has access to location data.  

Recordings  
Audio and video recordings are stored locally on the device in the app's Documents folder and optionally in the user's own iCloud Photos library. The developer has no access to these files.  

Third-Party Services  
The app uses only Apple's own first-party frameworks:  
• Core Location — on-device GPS  
• MapKit — police station search via Apple Maps  
• AVFoundation — recording  
• Photos — saving to photo library  

No third-party SDKs, analytics tools, or advertising networks are used.  

Children's Privacy  
The app does not knowingly collect data from anyone, including children under 13.  

Changes  
Any future changes to this policy will be reflected in an updated version posted with the app.  

Contact  
For questions about this privacy policy, contact: [your contact email]  
 
⸻

Feature List  

Emergency Calling  
• Automatically detects the user's country via GPS and resolves the correct local emergency number (911, 000, 999, 112, etc.)  
• Covers 50+ countries with a 112 international fallback  
• One-tap emergency call via the device's native dialler  
• Supports iPad with iPhone Continuity Calling  
• User-configurable custom emergency number override  

Video Recording  
• One-tap background video recording with front/rear camera toggle  
• Seamless mid-recording camera switching — all segments merged into a single file  
• Correct orientation handling for portrait and landscape  
• Saved to device Documents folder and Photos library  
• Recording overlay with elapsed timer and camera position indicator  

Audio Recording  
• One-tap audio recording in AAC format  
• Saved to device Documents folder  
• Accessible via iOS Files app  

Flashlight  
• Instant torch on/off toggle  
• SOS distress signal mode — flashes torch in international Morse SOS pattern (··· — — — ···)  

Location Sharing  
• Resolves current GPS coordinates to a formatted address via Apple's geocoder  
• Shares location (address + Apple Maps link) via iOS system share sheet — user chooses the recipient (Messages, WhatsApp, email, etc.)  

Nearby Police Finder  
• Searches for police stations near the user's current location using Apple MapKit  
• Displays name, distance, address, and phone number for each result  
• Tappable phone number to call directly
• One-tap directions via Apple Maps  

Recordings Library  
• Lists all saved audio and video recordings sorted by date  
• In-app playback for both video and audio  
• Processing indicator while multi-segment video is being merged  
• Share recordings via iOS share sheet  
• Swipe to delete  

Siri Integration  
• Voice shortcuts for key actions:  
   • "Start emergency video in EmergencyAct"  
   • "Start emergency audio in EmergencyAct"  
   • "Call emergency with EmergencyAct"  
   • "Share my location with EmergencyAct"  
   • "Stop recording in EmergencyAct"  
   • "Toggle flashlight in EmergencyAct"  
