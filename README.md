# ReservationApp – StartingProject

A **starter project for an iOS restaurant reservation app** built with SwiftUI. This template lays the foundation for a multi-location restaurant booking experience showcasing modern iOS development practices.

## Features

- **Multi-location support**: Contains a list of restaurant locations for user selection
- **Simple reservation system**: Users can create reservations for their chosen location
- **MVVM architecture**: Utilizes SwiftUI with ObservableObject data flow
- **Modular components**: Clean separation for locations, reservations, and restaurant views

## Project Structure

```
StartingProject/
├── StartingProject.xcodeproj           # Xcode project file
├── StartingProject/                    # Main source folder
│   ├── Assets.xcassets                 # App image assets
│   ├── Preview Content/                # SwiftUI preview assets
│   ├── MainView.swift                  # Root view (TabView: Locations/Reservation)
│   ├── Model.swift                     # App-wide ObservableObject model
│   ├── LitttleLemonLogo.swift          # Custom logo view
│   ├── LocationsView.swift             # UI for listing locations
│   ├── RESTAURANT/                     
│   │   ├── RestaurantLocation.swift    # Restaurant location model
│   │   ├── RestaurantView.swift        # UI for displaying a single restaurant
│   ├── RESERVATION/
│   │   ├── Reservation.swift           # Reservation model
│   │   ├── ReservationForm.swift       # Form UI for creating reservation
│   │   ├── ReservationView.swift       # Reservation tab content
│   └── .DS_Store                       # macOS metadata (safe to ignore)
└── .DS_Store                           
```

## Getting Started

1. **Clone the repo:**
   ```
   git clone https://github.com/rishikanthkc/ReservationApp.git
   ```

2. **Open in Xcode:**
   Open `ReservationApp/StartingProject/StartingProject.xcodeproj`.

3. **Run the app:**
   Select a simulator and press ▶️ to build and run.

## Requirements

- **Xcode 15** or later (Swift 5.9+, SwiftUI)
- macOS with development tools

## Customization

- Add real restaurant data or expand input fields in `ReservationForm.swift`.
- Refactor and build out app state in `Model.swift` for more advanced flows.

## License

This project is open-source and intended for learning, testing, or extending into a real app.
