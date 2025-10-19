# MyOffers — Android app (Jetpack Compose)

A smooth, fast Android app that shows offers around Sri Lanka across all sectors. Filter by sector, city, hot deals, and sort by ending soon or top discount. The search bar lives at the bottom for quick access.

## Features
- Home: Best offers first (hot + higher discount + ending sooner)
- Filters: sector, city, hot-only
- Sorting: Best, Ending Soon, Highest Discount
- Bottom search bar
- Offer details
- Simple, attractive colors with dark mode
- Smooth animations (list reordering, fades, badges)

## Tech
- Kotlin + Jetpack Compose + Material 3
- Navigation Compose
- Coil for images
- Fake repository with Sri Lanka sample data (swap with real API later)

## Run
1. Open in Android Studio (Giraffe+).
2. Sync Gradle.
3. Run on Android 8.0 (API 26) or newer.

## Customization
- Colors: `ui/theme/Color.kt`
- Data model: `data/Offer.kt`
- Filters/Sort: `domain/FilterState.kt`
- Replace `FakeOfferRepository` with your API:
  - Implement `OfferRepository`
  - Inject it into `MyOffersNav`

## Next steps (optional)
- Add pagination and a real backend
- Add map view for nearby offers
- Add push notifications for ending-soon/hot deals
- Add saved favorites

## License
MIT