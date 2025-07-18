# AI-BASED-CORPORATE-SAFETY-DETECTION-SYSTEM
This project is a real-time threat detection system designed to enhance corporate security by detecting fire and weapon presence using AI-based object detection models (YOLOv8). It features a GUI built with Tkinter and supports webcam monitoring as well as manual image uploads. On detecting a threat, it instantly sends alerts via email, SMS, and plays an alarm sound, while also saving an image snapshot of the event.

📌 Features

🔥 Real-time Fire Detection

🔫 Real-time Weapon Detection

🖼️ Manual Image Upload for Testing

📷 Webcam Integration for Live Monitoring

📩 Email Alerts via Gmail SMTP

📲 SMS Alerts via Twilio API

🔊 Audio Alert on Detection

💾 Automatic Image Snapshot Saving

✅ Simple and user-friendly Tkinter GUI

🚀 How It Works
Custom YOLOv8 Models are trained on fire and weapon image datasets.

The application loads trained .pt models for real-time inference.

When a threat is detected:

   An alarm is played,

   A snapshot is saved locally,

   Email and SMS notifications are sent to the registered security team.

🧠 Tech Stack
Component	Tech Used
AI Model	YOLOv8 (Ultralytics)
GUI	Tkinter (Python)
Alerts	Gmail SMTP (Email), Twilio (SMS)
Media	OpenCV for image/video handling
Others	Pillow, Numpy, OS, Threading


🔐 APIs Used

📧 Email – Gmail SMTP

📲 SMS – Twilio API

📈 Future Enhancements
🔐 Admin dashboard to review threats and logs

☁️ Cloud-based alert system

📊 Threat detection analytics

🎥 CCTV stream integration

