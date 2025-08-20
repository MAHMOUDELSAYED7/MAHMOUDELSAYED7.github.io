Effective Date: July 19, 2025

Introduction
Qubic AI (“Qubic AI,” “we,” “our,” or “us”) respects your privacy. This Privacy Policy explains how the Qubic AI mobile application (the “App”) handles information. The App is developed by Mahmoud El Sayed and is available on Android, with iOS planned.

What We Do Not Collect
- We do not require you to create an account.
- We do not collect your name, email, phone number, location, contacts, or payment details.
- We do not use analytics or advertising SDKs.

Data You Provide And How It’s Used
- Chat content you type: When you use the chatbot, the text you type is sent to Google Generative AI (Gemini via Google AI Studio) to generate a response.
- Text recognized from images (OCR): If you choose to use the Camera or select an Image, the App can extract text on-device using Google ML Kit Text Recognition. Only the recognized text (not the image) may be sent to Google Generative AI as part of your chat prompt if you proceed to send it.
- We do not send your images to our servers or to Google Generative AI. Images remain on your device unless you share them yourself.

Third-Party Processing (Google Generative AI)
- The App uses the google_generative_ai SDK to send your chat text and any OCR-extracted text to Google for processing and to return responses to you.
- No personal identifiers are included by the App unless you include them in your message.
- Google’s handling of your input is governed by Google’s Privacy Policy and terms:
  - https://policies.google.com/privacy
  - https://policies.google.com/terms

On-Device OCR (Google ML Kit)
- The App uses Google ML Kit Text Recognition on-device to extract text from images you select or capture. By design, this processing occurs locally on your device; the App does not send images to any server for OCR.

Local Storage And Retention
- Local storage: Your chats (text and timestamps) and settings are stored locally on your device using Hive (app-private storage).
- Security at rest: Your data is protected by the operating system’s app sandbox. The App does not currently apply its own encryption to the local database.
  - Tip for users: Enable device-level encryption and screen lock for additional protection.
- Retention: Your data remains on your device until you delete it within the App or uninstall the App.
- Backups: Depending on your OS settings, system backups (e.g., Android backups) may include App data.

Notifications And Background Processing
- The App can schedule local reminder notifications approximately every 8 hours using WorkManager.
- You can disable notifications in the App’s settings at any time.
- To support reliable delivery, the App may request:
  - POST_NOTIFICATIONS (to show notifications).
  - SCHEDULE_EXACT_ALARM/USE_EXACT_ALARM (for precise alarms on supported Android versions).
  - RECEIVE_BOOT_COMPLETED (to restore scheduled tasks after device reboot).
  - WAKE_LOCK and VIBRATE (to deliver notifications reliably).
- No personal information is collected for notifications.

Network And Links
- The App needs INTERNET and ACCESS_NETWORK_STATE to check connectivity and communicate with Google Generative AI.
- The App may open external links (e.g., support email or web pages) using your device’s email client or browser when you tap them. No data is sent automatically without you tapping a link.
- The App configuration allows cleartext (HTTP) connections, but the App is intended to use HTTPS endpoints for security.

Children’s Privacy (All Ages)
- The App is designed for a general audience and can be used by all ages, including children under 13.
- We do not knowingly collect personal information from children.
- Important: Because the chatbot sends user-provided text to Google Generative AI, children should not include personal information (e.g., real names, addresses, phone numbers) in messages. We encourage parents and guardians to supervise use and discuss safe online behavior.
- If you believe a child has provided personal information in chat text, you can delete the local chat in the App. We do not control Google’s systems; please review Google’s Privacy Policy for questions regarding data processed by Google.

Your Choices And Controls
- Delete data: You can delete individual chats or all chats within the App.
- Notifications: You can disable reminder notifications in the App’s settings.
- Connectivity: If there is no internet connection, the App will not be able to request responses from Google Generative AI.

Data Sharing
- We do not sell or share your personal information with third parties for marketing.
- We transmit your chat text and optionally OCR-extracted text to Google solely to obtain AI responses. We do not have access to or control over Google’s use of that data beyond what is described in Google’s policies.

Security
- We take reasonable steps to protect your information, including using the OS app sandbox and HTTPS for network requests where applicable.
- Note: The App’s local database is not currently encrypted by the App itself. Consider enabling device encryption and screen lock. We continuously review opportunities to enhance data protection.

International Processing
- Google may process your chat inputs on servers located in different countries. See Google’s Privacy Policy for details.

Changes To This Privacy Policy
- We may update this Privacy Policy. Updates will be made available within the App and on our website with a revised effective date.

Contact Us
For questions or concerns about this Privacy Policy:
- Mahmoud El Sayed
- Email: mahmoudelsayed.dev@gmail.com


Appendix: Android Permissions And Why We Ask
- INTERNET, ACCESS_NETWORK_STATE: To check connectivity and send your chat text to Google Generative AI.
- POST_NOTIFICATIONS: To display local reminder notifications.
- SCHEDULE_EXACT_ALARM, USE_EXACT_ALARM: To schedule precise reminders on supported Android versions.
- RECEIVE_BOOT_COMPLETED: To restore scheduled reminders after device reboot.
- WAKE_LOCK, VIBRATE: To ensure notifications are delivered reliably.
- Foreground service: May be requested by the system for reliable background work on some devices.
- Camera/Photos: Using the system Camera or Photo Picker when you choose to add an image. The App does not read your media library without your action, and images are not sent to Google Generative AI; only OCR-extracted text is optionally included in your chat if you submit it.

Third-Party SDKs Used
- google_generative_ai: Sends your chat text to Google for AI responses.
- google_mlkit_text_recognition: On-device OCR (no images sent to servers).
- workmanager: Schedules periodic local reminders.
- flutter_local_notifications: Displays local notifications.
- connectivity_plus: Checks network connectivity.
- url_launcher: Opens email client or browser when you tap a link.

No Analytics Or Ads
- The App does not include analytics or advertising SDKs.
