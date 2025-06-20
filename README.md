# structure

# 🎬 CinemaHub - Movie Booking System

## 📁 Project Structure

```bash
CinemaHub/
├── .idea/                 # JetBrains Rider configuration
│   └── .idea.CinemaHub/
│       └── .idea/         # IDE-specific files
│
├── CinemaServer/          # Backend (ASP.NET Core)
│   ├── Controllers/       # API controllers
│   ├── Services/          # Business logic
│   ├── Models/            # Database models
│   └── DTOs/              # Data Transfer Objects
│
├── CinemaWPF/             # WPF Client
│   ├── Assets/            # Images and resources
│   ├── Views/             # UI Screens
│   │   ├── Auth/          # Authentication views
│   │   └── Films/         # Movie browsing
│   ├── ViewModels/        # MVVM ViewModels
│   └── Controls/          # Custom UI controls
│
├── Core/                  # Shared core
│   ├── Models/            # Domain models
│   └── Contracts/         # Interfaces
│
└── Services/              # Service layer
    ├── Interfaces/        # Service contracts
    └── Implementations/   # Service implementations
```

## 🛠️ Technologies Used
- **Frontend**: WPF (MaterialDesign)
- **Backend**: ASP.NET Core
- **Database**: Supabase (PostgreSQL)
- **Auth**: JWT

## 🚀 How to Run
1. Clone repository
2. Restore NuGet packages
3. Start both projects:
   ```bash
   cd CinemaServer && dotnet run
   cd ../CinemaWPF && dotnet run
   ```

> 💡 Tip: Use Rider/Visual Studio for best development experience
