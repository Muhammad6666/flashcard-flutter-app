# 📚 Flashcard Flutter App

A modern microlearning app built with Flutter that helps users learn efficiently using flashcards and quizzes. Perfect for students, self-learners, and professionals looking to boost memory retention and track learning progress.

---

## 🚀 Features

### 🧑‍💻 User Authentication
- **Sign Up**: Create a new account.
- **Sign In**: Log in securely using email and password.

### 🏠 Home Page
- Overview of user-created decks.
- Quick access to recent or favorite decks.
- Search decks by title.

### 📦 Deck Management
- **Create Decks**: Add new topic-based decks.
- **Edit Decks**: Update title, description, and content.
- **Delete Decks**: Remove unwanted decks.
- **Deck Details**: View all flashcards inside a deck.

### 📝 Flashcard Functionality
- Add individual flashcards to decks.
- Edit and delete flashcards.
- Flip animations for front/back review.

### 🔍 Explore Page
- Browse predefined/public decks curated for learning.
- Import and study ready-made decks.

### 📊 Progress & Stats
- Track how many flashcards you've studied.
- Monitor right/wrong answers and view:
  - Total flashcards studied
  - Correct vs. incorrect count
  - **Accuracy %**

### 🧠 Quiz Mode
- Test yourself on a deck with quiz-style flashcards.
- Instant feedback on your answers.

---

## 🛠 Tech Stack

- **Flutter** (frontend)
- **Firebase** (authentication, database)

---

## 📸 Screenshots

| Step | Screen | Preview |
|------|--------|---------|
| 1️⃣ | **Landing Page** – Welcome screen introducing the app | ![Landing Page](https://github.com/user-attachments/assets/6e9d24e9-ec3d-4f86-8b17-790c6068a725) |
| 2️⃣ | **Sign Up Page** – New users can create an account | ![Sign Up Page](https://github.com/user-attachments/assets/89f786fd-f656-4e69-8de3-0d97ad002670) |
| 3️⃣ | **Sign In Page** – Returning users can log in | ![Sign In Page](https://github.com/user-attachments/assets/0cb18354-edb1-4a84-884c-dde1c2a79821) |
| 4️⃣ | **My Decks** – Home view showing your created decks | ![My Decks](https://github.com/user-attachments/assets/a89606df-5d21-4fd7-8aeb-ca4c96c07ea3) |
| 5️⃣ | **Deck Details** – View and manage flashcards within a deck | ![Deck Details](https://github.com/user-attachments/assets/78c53de8-a5fa-47b9-8423-abaf34b04148) |
| 6️⃣ | **Quiz Screen** – Test your knowledge using a quiz format | ![Quiz Screen](https://github.com/user-attachments/assets/ac12762a-9129-49f7-b515-a9f2306ddcb0) |
| 7️⃣ | **Explore Decks** – Discover and study public decks | ![Explore Decks](https://github.com/user-attachments/assets/5a84ab04-89cb-43ed-b1b6-a8e1cf604117) |
| 8️⃣ | **Progress/Stats** – Visual insights into your study performance | ![Progress/Stats](https://github.com/user-attachments/assets/81f51c81-aeb6-44e4-9549-71b4e0b71323) |

---

### 🔐 Authentication Testing
Tests the core functionality of user login and signup.

- ✅ Valid signup creates a new user
- ✅ Valid login navigates to the home screen
- ❌ Invalid credentials show error messages
  
<img width="1094" alt="authentication testing" src="https://github.com/user-attachments/assets/5af7c24e-7c12-4a7a-b945-72e1f56fd0a5" />

---

### 📦 Deck CRUD Testing
Covers creation, update, and deletion of decks and flashcards.

- ✅ Create a new deck and verify in My Decks
- ✅ Edit an existing deck title
- ✅ Add and delete flashcards
- ❌ Duplicate deck names should be handled gracefully

  <img width="703" alt="deck crud testing" src="https://github.com/user-attachments/assets/8d00b80f-21d8-4f1a-b8c7-ad5800ce4e93" />
