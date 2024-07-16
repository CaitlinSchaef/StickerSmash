## Expo tutorial:
https://docs.expo.dev/tutorial/introduction/

## Installed Expo Go on your phone

## Installed these dependencies:
Run:
npx expo install react-dom react-native-web @expo/metro-runtime

## To run it
Run:
npx expo start

## Control C to exit the terminal

## Styling Note:
In React Native, styling (such as the yellow border) is done using JavaScript as compared to the web, where CSS is used. Most of the React Native core components accept a style prop that accepts a JavaScript object as its value. 

## Pressable: 
React Native provides various components to handle touch events on native platforms. For this tutorial, we'll use the <Pressable> component. It is a core component wrapper that can detect various stages of interactions, from basic single-tap events to advanced events such as a long press.

## We added an icon library:
Run:
npx expo install @expo/vector-icons

## Establish an Expo SDK library so that they can choose images from their device
expo-image-picker provides the launchImageLibraryAsync() method that displays the system UI for choosing an image or a video from the device's media library.
Run: 
npx expo install expo-image-picker

## Modals
React Native provides a <Modal> component that presents content above the rest of your app. In general, modals are used to draw a user's attention toward critical information or guide them to take action. For example, in the second chapter, we used alert() to display a placeholder when a button is pressed. That's how a modal component displays an overlay.
We successfully created the emoji picker modal and implemented the logic to select an emoji and display it over the image.

## Gestures
Gestures are a great way to provide an intuitive user experience in an app. The React Native Gesture Handler library provides built-in native components that can handle gestures. It uses the platform's native touch handling system to recognize pan, tap, rotation, and other gestures.
Add two different gestures using the React Native Gesture Handler library:
-Double tap to scale the size of the emoji sticker.
-Pan to move the emoji sticker around the screen so that the user can place the sticker anywhere on the image.

## Install Gestures
The React Native Gesture Handler library provides a way to interact with the native platform's gesture response system. To animate between gesture states, we will use the Reanimated library.
Run: 
npx expo install react-native-gesture-handler react-native-reanimated

-To get gesture interactions to work in the app, we'll render <GestureHandlerRootView> from react-native-gesture-handler to wrap the top-level component of our app (also known as the "root component").