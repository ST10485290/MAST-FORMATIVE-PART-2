# MAST-FORMATIVE-PART-2


## README.md

#  FoodApp — React Native Menu Management App

##  Overview

**FoodApp** is a simple mobile application built using **React Native** (with Expo) that allows users to manage, filter, and view menu items for a restaurant.  
The app demonstrates user interaction, component-based design, and dynamic UI updates — ideal for a small business or restaurant concept.


## Objectives

The main objectives of this project are:
1. To design and develop a **simple food menu app** that can:
   - Display menu items (name, description, course, and price).
   - Add new items dynamically.
   - Filter items by course type (Starters, Mains, Dessert).
   - Display total prices and an order summary.
2. To demonstrate **React Native component-based development**.
3. To apply basic **state management** using React hooks (`useState`, `useMemo`).
4. To create a functional and **visually appealing** user interface using simple styles.


## How the App Works

### 1️ Menu Screen

* Displays all menu items.
* Shows total cost of visible items.
* Has buttons to:

  * `Filter` → go to filter options.
  * `Manage` → go to add new items.
  * `Orders` → view summary of all dishes.

### 2️ Manage Menu Screen

* Allows adding a new dish with:

  * Name
  * Description
  * Course (e.g. Starters, Mains, Dessert)
  * Price in Rands
* After adding, it returns to the Menu screen automatically.

### 3️ Filter Screen

* Lets the user choose a menu category.
* Applies a filter to show only that category’s dishes.

### 4️ Orders Screen

* Shows all dishes with their prices.
* Displays total amount at the bottom.


##  Future Improvements

These features can be added in the next phase:

* Persistent storage using **AsyncStorage**.
* Navigation using **React Navigation**.
* Search bar for filtering dishes by name.
* Image upload for menu items.
* Dark mode UI.

