# Cadify Technologies Flutter UI

## What Was Built
This project is a pixel-perfect Flutter UI implementation based on the provided CAD/3D design screens. The app includes a clean, scalable architecture with reusable components, centralized theme management, and production-ready structure suitable for further backend integration.

---

## Screens Included

- **Home Screen**  
  Landing page with hero section, services preview, and CTA buttons.

- **Services Screen**  
  Displays all CAD/3D services with detailed cards and descriptions.

- **Contact Screen**  
  Includes contact info and a fully designed inquiry form.

---

## Tech Stack

- Flutter SDK: 3.4+
- Dart SDK: 3.4+
- Packages:
  - google_fonts: ^6.2.1
  - flutter_launcher_icons: ^0.14.3

---

## How to Run

1. Unzip the project
2. Open terminal in project folder
3. Run:
   flutter pub get
4. Generate app icon:
   dart run flutter_launcher_icons
5. Run the app:
   flutter run

---

## Asset Placeholders to Replace

Replace these with actual production assets:

- `assets/images/home_hero.jpg`
  → Main hero CAD render (homepage top section)

- `assets/images/service_preview_1.jpg`
  → CAD Web Visuals preview image

- `assets/images/service_preview_2.jpg`
  → Interactive product media preview

- `assets/images/service_1.jpg`
  → 3D CAD rendering example

- `assets/images/service_2.jpg`
  → Mechanical part visualization

- `assets/images/service_3.jpg`
  → Exploded view graphic

- `assets/images/service_4.jpg`
  → Website-ready asset preview

- `assets/icon/app_icon.png`
  → App launcher icon (1024x1024 recommended)

---

## Notes

- The UI is fully responsive and uses best Flutter practices
- All styling is centralized (colors, typography, spacing)
- Navigation uses named routes (scalable for large apps)
- Replace placeholder assets for final production use
- Backend/API integration can be added easily on top of this structure