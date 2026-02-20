# DoorDash Clone

A DoorDash UI clone built with Flutter. This is a frontend-only project created for portfolio and demonstration purposes.

## Screenshots

The app replicates the DoorDash home screen, including:

- Address bar with search functionality
- Food category browsing (American, Chinese, Italian, Mexican, Pizza, Sushi, etc.)
- "New on DoorDash" restaurant carousel
- Favorites section
- All stores listing
- Bottom navigation sheet

## Tech Stack

- **Framework:** Flutter (Dart SDK >=2.19.5)
- **Icons:** Cupertino Icons, Material Icons
- **SVG Support:** flutter_svg
- **Haptic Feedback:** flutter_vibrate
- **Font:** Roboto (bundled)

## Getting Started

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install) (>=2.19.5)

### Installation

```bash
git clone https://github.com/kylebessemer/doordash_clone.git
cd doordash_clone
flutter pub get
flutter run
```

## Project Structure

```
lib/
  main.dart                      # App entry point
  home/
    view/home.dart               # Home screen layout
    controller/
      appbar.dart                # Custom app bar
      categories.dart            # Food category row
      favorites.dart             # Favorites section
      new.dart                   # New restaurants carousel
      allstores.dart             # All stores listing
      bottomsheet.dart           # Bottom navigation sheet
```

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
