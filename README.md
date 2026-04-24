# Fish Fillets NG - Java Implementation 🐠🚀

This project is a classic arcade-style puzzle game inspired by **Fish Fillets NG**, developed as the final project for the **Object-Oriented Programming (OOP)** course at **ISCTE-IUL** (2025/2026).

## 🎮 Project Overview
The game features two main characters—a **Big Fish** and a **Small Fish**—that must cooperate to navigate aquatic environments. Players interact with various objects (movable and fixed) to reach the exit of each level.

### Key Rules:
**Small Fish:** Can support and push one light movable object.
**Big Fish:** Can support multiple light objects or one heavy object. It can push multiple light or heavy objects horizontally.
**Gravity:** Movable objects (like trophies or stones) sink if they have no support.
**Game Over:** If an object falls on a fish or if the Big Fish supports too much weight, the level restarts.

## 🛠️ Technical Implementation
This project strictly follows OOP principles as required by the course:
**Inheritance & Abstraction:** A robust class hierarchy starting from a base `GameObject` abstract class.
**Interfaces:** Implementation of `ImageTile` for GUI rendering and custom interfaces for object behaviors (e.g., `Movable`, `Interactable`).
**Design Patterns:** Use of the **Observer/Observed** pattern for GUI updates and the **Singleton** pattern for the `GameEngine`.
**Persistence:** High scores and game progress are stored in the filesystem.

## 📂 Project Structure
- `src/`: Java source files organized by packages.
- `images/`: Game assets (tiles and sprites).
- `rooms/`: Level configuration files (`room0.txt`, `room1.txt`, etc.).

## 🚀 How to Play
1. Import the project into **Eclipse**.
2. Run the `Main` class.
3. **Controls:**
   - **Arrow Keys:** Move the active fish.
   - **Spacebar:** Switch between the Big and Small fish.
   - **'R' Key:** Restart the current level.

---
*Developed by: Tiago Pinto & Madalena Branco*
