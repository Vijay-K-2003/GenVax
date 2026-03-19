# GenVax - Your Personal Vaccine Tracker

**GenVax** is a comprehensive Android application designed to help individuals and caregivers manage and track immunization schedules efficiently. From newborn infants to growing children, GenVax ensures you never miss a vital vaccine dose.

---

## 🚀 Features

-   **Comprehensive Vaccine Directory**: Access a detailed list of essential vaccines, including BCG, Hepatitis B, OPV, IPV, Rotavirus, Measles, DPT, and more.
-   **Detailed Immunization Info**: For each vaccine, the app provides:
    -   Number of required doses.
    -   The specific age or period during which the vaccine should be administered.
-   **Smart Reminder System**:
    -   Create personalized vaccine reminders based on your child's schedule.
    -   Store all reminders securely in a local SQLite database.
-   **Timely Notifications**: Receive alarm notifications to stay informed about upcoming vaccination dates.
-   **Quick Access to Health Resources**:
    -   Direct dial buttons for helpline numbers (International and National).
    -   Integrated links to the COVID-19 tracker and the World Health Organization (WHO) website for the latest health updates.
-   **User Authentication**: Secure your information with a built-in Login and Sign-up system.

## 🛠️ Tech Stack

-   **Platform**: Android
-   **Language**: Java
-   **Database**: SQLite (for local storage of reminders)
-   **UI Components**: Material Design, RecyclerView, Floating Action Buttons.
-   **Background Tasks**: AlarmManager for scheduling notifications.

## 📂 Project Structure

The project follows the standard Android Gradle structure:

-   `app/src/main/java`: Contains the Java source code (Activities, Adapters, Database Handlers, and Models).
-   `app/src/main/res`: Contains UI layouts, drawables, and string resources.
-   `app/src/main/AndroidManifest.xml`: Defines app components, permissions, and entry points.

## 🏁 Getting Started

### Prerequisites

-   [Android Studio](https://developer.android.com/studio) (Bumblebee or newer recommended).
-   JDK 8 or higher.

### Installation

1.  **Clone the Repository**:
    ```bash
    git clone https://github.com/Vijay-K-2003/GenVax.git
    cd GenVax
    ```
2.  **Open in Android Studio**:
    -   File > Open > Select the `GenVax` folder.
3.  **Build the Project**:
    -   Let Gradle sync the project dependencies.
4.  **Run the App**:
    -   Connect an Android device via USB or start an emulator and click the "Run" button in Android Studio.

## 🛡️ Permissions

-   `INTERNET`: To access external health resources and trackers.
-   `WAKE_LOCK` & `SCHEDULE_EXACT_ALARM`: For precise vaccine reminder notifications.

---

*Stay Healthy, Stay Protected with GenVax.*
