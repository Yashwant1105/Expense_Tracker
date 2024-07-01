# **Expense Tracker**

Expense Tracker is a Flutter application that helps users track their daily expenses efficiently. The app provides features for adding new expenses, viewing a list of expenses, and visualizing expense data with charts.


### *Features*

**Add New Expenses:** Easily add new expense items with details such as title, amount, and date.

**View Expenses**: See a list of all expenses with the ability to delete them.

**Expense Charts:** Visualize expenses in a bar chart to get insights into spending patterns.



### *File Structure*

The project consists of the following Dart files:

[main.dart](https://github.com/Yashwant1105/Expense_Tracker/blob/main/lib/main.dart): The entry point of the application. It initializes the app and sets up the main widget tree and contains the theming part of the app.

[chart.dart](https://github.com/Yashwant1105/Expense_Tracker/blob/main/lib/widgets/expenses_list/chart/chart.dart): Contains the logic and UI for displaying expense data in a chart format.

[chart_bar.dart](https://github.com/Yashwant1105/Expense_Tracker/blob/main/lib/widgets/expenses_list/chart/chart_bar.dart): Defines the individual bars used in the expense chart.

[expense.dart](https://github.com/Yashwant1105/Expense_Tracker/blob/main/lib/model/expense.dart): Defines the data model for an expense item.

[expense_item.dart](https://github.com/Yashwant1105/Expense_Tracker/blob/main/lib/widgets/expenses_list/expense_item.dart): Represents a single expense item in the UI.

[expenses.dart](https://github.com/Yashwant1105/Expense_Tracker/blob/main/lib/widgets/expenses.dart): Manages the overall state and logic of expenses within the app.

[expenses_list.dart](https://github.com/Yashwant1105/Expense_Tracker/blob/main/lib/widgets/expenses_list/expenses_list.dart): Provides a list view of all expense items.

[new_expenses.dart](https://github.com/Yashwant1105/Expense_Tracker/blob/main/lib/new_expenses.dart): Contains the UI and logic for adding new expenses.



### *Flutter Concepts Used*

- **State Management**: Uses native Flutter implementation with StatefulWidget and setState.
- **Navigation**: Implements modal bottom sheets for input forms.
- **Custom Widgets**: Encapsulates UI components like expense items and charts.
- **Theming and Styling**: Uses ThemeData contexts, LinearGradient, and other styling techniques.
- **Asset Management**: Efficiently manages icons and other assets with careful attention to related Element Tree.
  

### *Setup and Installation*

#### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install) installed on your machine.
- An editor like [Android Studio](https://developer.android.com/studio) or [Visual Studio Code](https://code.visualstudio.com/).

#### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Yashwant1105/Expense_Tracker.git
   cd Expense_Tracker
   ```
    

2. **Install Dependencies**:
   ```bash
   flutter pub get
   ```
    

3. **Run the App**:
   ```bash
   flutter run
   ```


### *Usage*

1. Launch the app on your device or emulator.
2. Press the "+" button to add a new expense.
3. Fill in the expense details (title, amount, date, and category).
4. View the list of expenses and the corresponding chart.
5. Swipe left or right on an expense to delete it, with an option to undo.

### *Flutter Concepts Used:*

- **State Management:**
  - Uses native Flutter implementation with `StatefulWidget` and `setState` for managing dynamic UI changes.

- **Navigation:**
  - Implements modal bottom sheets for input forms to enhance user interaction and workflow.

- **Custom Widgets:**
  - Encapsulates UI components like expense items and charts into reusable custom widgets for modularity and maintainability.

- **Theming and Styling:**
  - Utilizes `ThemeData` contexts, `LinearGradient`, and other styling techniques for consistent visual aesthetics.

- **Asset Management:**
  - Efficiently manages icons and other assets with careful consideration of their impact on the Element Tree.
