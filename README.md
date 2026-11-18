# ScanToBin
### An AI-Powered Campus Waste Classification App
**IE209 Mini-Project · University of Hyderabad**

---

## 1. The Problem
Most students cannot tell the difference between PET, PP, or multilayer packaging. Because of this confusion, recyclable waste frequently ends up in mixed bins, contaminating the recycling stream. Furthermore, campus green teams have no data on what items are being thrown away or where the confusion is highest.

## 2. Users
*   **Primary Users:** University students living in hostels (Hostels J, K, I, and L) and attending classes.
*   **Secondary Users:** The campus Green Club and estate administrators who need data to plan targeted awareness drives and optimize bin placement.

## 3. Key Features
*   **AI Image Scanning:** Snap a photo of an empty bottle or packet. The app uses AI vision to identify the material and tell the user exactly which bin (Dry, Wet, Reject, E-Waste) it belongs in.
*   **Manual Resin-Code Picker:** If the AI is not confident, users can manually pick the recycling number (1-7) or material type.
*   **Confidence-Based Verification:** If the AI's confidence is below 80%, the app automatically pauses and asks the user to verify the answer manually to prevent errors.
*   **Gamification:** Students earn points and build daily streaks for correct disposal.
*   **Hostel Leaderboard:** Fosters friendly competition between hostels to see who recycles the most.
*   **Interactive Bin Map:** Shows the nearest campus bins using GPS coordinates.
*   **Data Insights:** A live Flourish dashboard embedded in our Google Site that shows the Green Club which items are misclassified the most.

## 4. Tools Used
*   **App Frontend:** MIT App Inventor (Android APK)
*   **Backend & Database:** Google Sheets + Google Apps Script (API)
*   **AI Vision:** Gemini 2.5 Flash (via Apps Script)
*   **Data Visualization:** Flourish Studio
*   **Website & Embedding:** Google Sites

## 5. Screenshots

### 1. Home Screen & Scanning Flow
<!-- DRAG AND DROP YOUR IMAGE HERE, OR PASTE LINK BELOW -->
![Home Screen](PASTE_IMAGE_LINK_HERE)
*Student dashboard showing points, streaks, and the main scan button.*

### 2. Result Screen & Manual Picker
<!-- DRAG AND DROP YOUR IMAGE HERE, OR PASTE LINK BELOW -->
![Result Screen](PASTE_IMAGE_LINK_HERE)
*Result screen showing the correct bin colour, reasoning, and the manual fallback.*

### 3. Data Insights Dashboard
<!-- DRAG AND DROP YOUR IMAGE HERE, OR PASTE LINK BELOW -->
![Data Insights](PASTE_IMAGE_LINK_HERE)
*Flourish story embedded on the Google Site showing scan accuracy.*

## 6. Team Roles
*   **Saksham Kulshrestha (25ETIM44):** Team Lead & Product Owner (Interviews, rules, pitch)
*   **Harshavardh K Iyer (25MCCE40):** UI/UX Designer (Figma, colours, app icon)
*   **Arjun Jadav (25ETIM13):** App Developer (App Inventor blocks, AI flow)
*   **Harshith Suram (25MCCE53):** Backend & Data Engineer (Google Sheet, Apps Script, Dashboard)
*   **Deepak Avinash P (24MCCE38):** QA, Integration & Outreach (Testing, Google Site, demo video)

## 7. Important Links
*   **Download the App (APK):** [Insert your Google Drive APK Link Here]
*   **Live Google Site:** [https://sites.google.com/view/scantobin/home](https://sites.google.com/view/scantobin/home)
*   **Live Flourish Data Story:** [https://app.flourish.studio/story/3856534/](https://app.flourish.studio/story/3856534/)
*   **Project Dataset (Google Sheet):** [https://docs.google.com/spreadsheets/d/1qnO0NLsIXOdvJ0C61cQe4NrJ_8dSnn3T8Bvhtqj-KtE/edit?usp=sharing](https://docs.google.com/spreadsheets/d/1qnO0NLsIXOdvJ0C61cQe4NrJ_8dSnn3T8Bvhtqj-KtE/edit?usp=sharing)
