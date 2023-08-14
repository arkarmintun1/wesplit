# wesplit

The application we can use to split the amount among friends and family at the diner. I created this application as part of learning iOS development with SwiftUI.

https://github.com/arkarmintun1/wesplit/assets/33666829/df968314-8d5c-4847-aa1f-afa6255878f0

## Tech Stack

- SwiftUI
- Swift

## How it's built?

- The application uses `@State` for local state management for the total amount, number of people, and tip percentage. Since those values are two-way binding, the changes to the values are immediately reflected in the total amount per person calculation.
- For keyboard dismissal, a toolbar modifier adds a `Done` button above the keyboard.

