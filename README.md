# 🏡 Zillow Real Estate Finder – iOS App (Swift + Core Data)

An iOS mobile application that enables users to search real estate listings, view property details and manage favorites using the Zillow API. Developed using UIKit and Core Data for the **MAP523 – iOS App Development** course at Seneca Polytechnic.

> 🔐 Features full user authentication, 10+ search filters, API integration and Core Data for persistence.

---

## 📲 Features

- 🔍 Search properties with filters like price, rooms, bathrooms, address and more
- 🏷️ View detailed property information using Zillow API
- ❤️ Add/remove favorite listings
- 🔄 Sort favorites by number of rooms or price
- 🔐 Core Data-based login and session persistence
- 📱 iPhone-friendly layout using UIKit and Storyboard

---

## 🛠️ Technologies

| Layer       | Tech Used                         |
|-------------|-----------------------------------|
| Frontend    | UIKit, Storyboard                 |
| Backend     | Zillow API (via RapidAPI)         |
| Storage     | Core Data                         |
| Auth        | Local authentication + persistence|
| Language    | Swift                             |

---

## 📸 Screenshots

### 🔎 City Search and Results  
![City View](./media/zillow_city_view.png)

### 📊 Forecast/Details View  
![Forecast View](./media/zillow_forecast_view.png)

---

## 📂 Folder Structure

```
ZillowFinderApp/
├── Controllers/
│   ├── SearchZillowViewController.swift
│   ├── PropertyViewController.swift
├── Models/
│   ├── ZillowProperty.swift
│   ├── ZillowSearchResponse.swift
├── Views/
│   ├── PropertyTableViewCell.swift
├── Services/
│   ├── PropertyManager.swift
├── CoreData/
│   ├── UserProfile.xcdatamodeld
│   ├── FavoriteListing.xcdatamodeld
├── Assets.xcassets/
├── Main.storyboard
├── Info.plist
├── README.md
```

---

## ⚙️ How To Set Up

1. Clone this repository:
```bash
git clone https://github.com/yourusername/zillow-ios-app.git
```

2. Open the `.xcodeproj` or `.xcworkspace` file in Xcode.

3. Add a `ZillowAPI.plist` file in the root folder with your RapidAPI key:
```xml
<dict>
    <key>API_KEY</key>
    <string>your_rapidapi_key_here</string>
</dict>
```

4. Run the app on an iOS Simulator or physical device (iOS 15+).

---
