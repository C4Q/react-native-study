# React Native

## Project Goal
Create a subway tracker app that automatically tells me if the subways I use for my morning commute have delays.

Sprints:
- Get dead simple app up and running, that simply renders 'hello world' to the page
- Create a page that either says 'Subways on Time' or 'Subways Delayed' (using hardcoded data)
- Add a ListView page that lists at least two subway statuses (using hardcoded data)
- Use real data from MTA API

## Resources
- [React Native Docs](https://facebook.github.io/react-native/docs/getting-started.html)
- [React Native Code Examples](https://github.com/facebook/react-native/tree/master/Examples)
- [React Native Todo List Code Example](https://github.com/joemaddalone/react-native-todo)
- [React Native Training Book](https://unbug.gitbooks.io/react-native-training/content/chapter1.html)
- [Exponent IDE](https://docs.getexponent.com/versions/v14.0.0/guides/up-and-running.html#open-the-app-on-your-phone-or-simulator)

## Overview
React Native is a framework that lets you build native mobile apps in JavaScript. Basically, it lets you write one mobile code base and then compiles that code into native iOS (Swift) and Android (Java) code.

React Native is built on top of React (and is pretty similar) except it uses special native components instead of web components. For example, instead of using a `p` tag (like you would in web) React Native uses a `Text` tag. Similarly, instead of `div`, React Native uses `View`.

## Components

### TextInput
- [Handling Text Input](https://facebook.github.io/react-native/docs/handling-text-input.html)

### ScrollView
- [Using a ScrollView](https://facebook.github.io/react-native/docs/using-a-scrollview.html)

ScrollViews allow you to scroll through your app.

### ListView
- [Using a ListView](https://facebook.github.io/react-native/docs/using-a-listview.html)

ListViews are used for generating lists of data (instead of a `ul` or `li` tag)

### Navigators
- [Using Navigators](https://facebook.github.io/react-native/docs/using-navigators.html)

Navigators are used to navigate between pages (similar to an `a` or `Link` tag)

### Styling
- [React Native Styling](https://facebook.github.io/react-native/docs/style.html)

React Native uses inline styles
