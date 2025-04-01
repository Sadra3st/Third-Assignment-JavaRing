# Project Title: Java-Ring RPG

## Description
I made this game to practice advanced programming lessons.
Java-Ring RPG is a text-based role-playing game (RPG) inspired by Souls-like games. The game features turn-based combat where players can choose from different character classes (Knight, Wizard, Assassin) and battle against various monsters (Goblin, Skeleton, Dragon). The game emphasizes Object-Oriented Programming (OOP) principles. Players can engage in combat, use unique abilities, and progress through different locations.

## Getting Started

### Dependencies

- **Java Development Kit (JDK)**
- **Gradle**: Build tool for managing dependencies and compiling the project.
- **Operating System**: Compatible with Windows, macOS, and Linux.

### Installing

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Sadra3st/Third-Assignment-JavaRing.git
   cd java-ring
   ```

2. **Build the Project**:
   ```bash
   ./gradlew build
   ```

3. **Run the Game**:
   ```bash
   ./gradlew run
   ```
- You can use intelliJ(
  recommended).
### Executing Program

1. **Choose a Character**:
  - At the start of the game, you will be prompted to choose a character:
    - **Knight**: High health, strong melee attacks.
    - **Wizard**: Can cast spells to heal and damage enemies.
    - **Assassin**: Can become invisible to avoid damage and deal increased damage.

2. **Enter the Starting Location**:
  - After choosing a character, you will enter the starting location where a random monster will appear.

3. **Choose an Action**:
  - You can choose to:
    - **Fight the Monster**: Engage in turn-based combat.
    - **Move to Another Location**: Encounter a new random monster.

4. **Combat**:
  - During combat, you can:
    - **Attack**: Deal damage to the monster.
    - **Defend**: Reduce incoming damage.
    - **Use Special Ability**: Use your character's unique ability.
    - **Heal**: Restore your health.

5. **Defeat Monsters**:
  - If you defeat a monster, you will be rewarded and can proceed to the next location.
  - If your health reaches zero, the game ends.

6. **Game Over**:
  - The game ends when your character is defeated.

## Help

If you encounter any issues while running the game, ensure that:
- You have the correct version of JDK installed.
- Gradle is properly configured on your system.
- All dependencies are correctly installed.


## Authors

- **Name** - [Sadra3st](https://github.com/Sadra3st)
- **Email**: sadra3st@gmail.com

## Version History

- **0.1**
  - Initial release of Java-Ring RPG.
  - Basic turn-based combat system.
  - Three character classes and three monster types.

