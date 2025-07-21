# CardDeckProject

This is a simple Java-based card game project that demonstrates object-oriented programming concepts such as classes, enums, interfaces, and comparators. The project simulates basic card operations like creating a deck, shuffling, comparing cards, and running a card game.

## 📁 Project Structure

```
.
├── Card.java            # Represents a playing card with Suit and Rank
├── Deck.java            # Manages the deck (creation, shuffling, dealing)
├── Rank.java            # Enum for card ranks (TWO to ACE)
├── Suit.java            # Enum for card suits (CLUBS to SPADES)
├── CardComparator.java  # Custom logic for comparing cards
├── CardGame.java        # Main class to execute the game
├── AppTest.java         # Contains unit tests (JUnit-based)
```

## 🚀 Features

- Card creation using enums (`Suit`, `Rank`)
- Full deck generation (52 cards)
- Shuffle functionality
- Card comparison logic via `CardComparator`
- Unit testing with `AppTest`

## 🛠️ How to Compile and Run

### 1. Compile the Source Code

```bash
javac *.java
```

### 2. Run the Card Game

```bash
java CardGame
```

### 3. Run Tests (Optional)

Make sure you have JUnit in your classpath:

```bash
java -cp .:junit-4.13.2.jar:hamcrest-core-1.3.jar org.junit.runner.JUnitCore AppTest
```

> 🔁 For Windows, replace `:` with `;` in classpath.

## ✅ Requirements

- Java Development Kit (JDK) 8 or higher
- JUnit 4 (for running tests)

## 📌 Class Descriptions

- **Card.java** – A data structure holding a card’s suit and rank.
- **Deck.java** – Contains logic to initialize, shuffle, and draw cards from a standard deck.
- **Rank.java** – Enum with ranks from `TWO` to `ACE`, including their values.
- **Suit.java** – Enum with four suits: `CLUBS`, `DIAMONDS`, `HEARTS`, `SPADES`.
- **CardComparator.java** – Comparator for comparing two cards based on their ranks.
- **CardGame.java** – Contains the `main()` method and game logic.
- **AppTest.java** – Simple test cases using JUnit.

## 📄 License

This project is provided for educational purposes and has no official license. You are free to use, modify, and share it as needed.

---

👨‍💻 Built with 💙 in Java
