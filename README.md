# ScrollingText

A simple Android app that shows a long article in a scrollable two-column layout: a narrow left column for the subtitle and a wider right column for the article text.

Made as homework for the *Razvoj mobilnih aplikacij* (Mobile App Development) course, based on Android Developer Fundamentals – Homework 1.3.

## Features

- Scrollable article text using `ScrollView`
- Two-column layout built with a horizontal `LinearLayout`
  - Left: subtitle (fixed width of `100dp`)
  - Right: article text (fills the remaining width)
- "Add Comment" button at the bottom that shows a `Toast` message: *Comment submitted!*
- All texts stored in `strings.xml` (no hardcoded strings)

## Built with

- Java
- Android Studio
- XML layouts (`ScrollView`, `LinearLayout`, `TextView`, `Button`).

## Getting started

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/ScrollingText.git
   ```
2. Open the project in Android Studio (**File → Open**).
3. Wait for Gradle to sync.
4. Run the app on an emulator or a physical device.

## Project structure

<img width="271" height="484" alt="asd adbadjabsdbahsdjb" src="https://github.com/user-attachments/assets/e5020971-4ca8-445a-a062-0e60c0c2f48b" />
