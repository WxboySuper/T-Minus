# T-Minus Roadmap

This roadmap outlines the development of T-Minus, a free, no-nonsense Android countdown widget. The goal is to build a clean, resizable widget without subscriptions or bloat.

## Versioning Guide

Format: vX.Y.Z (e.g., v0.1.0, v0.2.0, v1.0.0)

Major (X): Fundamental changes.

Minor (Y): New customization options or features.

Patch (Z): Bug fixes.

Pre-1.0: Use v0.Y.0 for initial development.

Philosophy: Keep it simple. Ship it fast.

<details>
<summary>🗂️ <strong>Milestone Progress Task List</strong></summary>

[ ] Project Initialization (v0.1.0)

[ ] The Editor UI

[ ] Data Storage (Room/Preferences)

[ ] The Widget Layout

[ ] The Countdown Logic

[ ] Calendar Integration

[ ] Customization (Colors/Fonts)

[ ] v1.0.0: Release

</details>

## v0.1.0-alpha: The Hello World

Goal: Get a blank widget on the Android home screen.

[ ] Create new Android Project (Kotlin/Compose).

[ ] Implement GlanceAppWidget (Jetpack Glance).

[ ] Verify widget appears in the Android Widget Picker.

[ ] Place widget on home screen (even if it just says "Hello").

## v0.2.0-alpha: The Editor

Goal: An app interface to create countdowns.

[ ] Create Main Activity UI.

[ ] Add "Title" input field.

[ ] Add "Target Date" picker.

[ ] Implement Save button.

## v0.3.0-alpha: Data Persistence

Goal: Saving the events.

[ ] Set up local storage (DataStore or Room Database).

[ ] Save user input to storage.

[ ] Retrieve list of saved countdowns in the app.

## v0.4.0-alpha: The Engine

Goal: Connecting the App to the Widget.

[ ] Pass saved data from App to Widget Receiver.

[ ] Implement "Days Remaining" calculation logic.

[ ] Update Widget UI to show the calculated number.

## v0.5.0-alpha: The Widget UI

Goal: Making it look good.

[ ] Design a clean, readable layout (Big Number, Small Label).

[ ] Handle "Event Passed" state (e.g., "0 Days" or "Done").

[ ] Ensure text fits different widget sizes.

## v0.6.0-alpha: Calendar Integration 📅

Goal: Sync with existing calendar events.

[ ] Request READ_CALENDAR permission.

[ ] Query Android Calendar Provider for upcoming events.

[ ] Create an "Import from Calendar" screen.

[ ] Allow selecting a specific calendar event to use as the countdown target.

## v0.7.0-alpha: Customization

Goal: Personalization.

[ ] Add Color Picker for background/text.

[ ] Add Transparency toggle.

[ ] Allow resizing the widget (2x1, 4x1, 2x2).

## v1.0.0: Release 🚀

Goal: A permanently useful tool.

[ ] Create App Icon.

[ ] Build Signed APK.

[ ] Install on personal device for daily use.

## Post-v1.0: "Nice to Haves"

### v1.1.0: Multiple Events

[ ] Allow multiple widget instances with different events.

### v1.2.0: Recurring Events

[ ] Support for annual events (Birthdays, Anniversaries) automatically detected from calendar.
