# OnboardingView-Swift

A simple onboarding screen for SwiftUI that mimicks the iOS onboarding screen

![Screenshot of OnboardView example](https://adamlyttleapps.com/git/onboardingview-hero-600.jpg)

**Usage:**

```
OnboardingView(appName: "Real Estate Calculator", features: [
    Feature(title: "Mortgage Repayments", description: "Easily calculate weekly, monthly and yearly repayments ", icon: "house"),
    Feature(title: "Amortization", description: "Quickly view amortization for the life of the loan", icon: "chart.line.downtrend.xyaxis"),
    Feature(title: "Deposit Calculator", description: "Calculate deposit based on purchase price and savings", icon: "percent"),
    Feature(title: "Ad-Free Experience", description: "Thank you for downloading my app, I hope you enjoy it :-)", icon: "party.popper"),
], color: Color.blue)
```

**Customize:**

* appName: The name of your app to be displayed at the top of the onboarding screen
* features: The list of features to be displayed
  * title: Title of the feature
  * description: Details about the feature
  * icon: Any SF Symbol name
* color: The color scheme to be used

**About Adam Lyttle:**

Follow me on Twitter: [twitter.com/adamlyttleapps](https://twitter.com/adamlyttleapps)

Visit my website: [adamlyttleapps.com](https://adamlyttleapps.com)
