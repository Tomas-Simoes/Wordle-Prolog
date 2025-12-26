# Wordle Prolog
This project is a logic-based implementation of the popular game **Wordle**, built entirely in **Prolog**. It features a fully interactive text-based UI, a game loop, and a solver to assist with optimal guesses.

## Project Structure

- **`main.pl`**: The entry point of the application.
- **`wordle_game.pl`**: Contains the core game logic and rules.
- **`wordle_solver.pl`**: A logic-based solver to suggest the best next guess.
- **`ui.pl`**: Handles the user interface (menus, input/output).
- **`words.pl`**: The database of valid 5-letter words.
- **`utils.pl`**: Helper predicates for list manipulation and string handling.

## Prerequisites

To run this project, you need a Prolog interpreter. **SWI-Prolog** is the recommended standard.

* **Windows/macOS/Linux:** [Download SWI-Prolog](https://www.swi-prolog.org/Download.html)

## Installation

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/Tomas-Simoes/Logic-Project.git](https://github.com/Tomas-Simoes/Logic-Project.git)
    cd Logic-Project
    ```

## Usage

1.  **Start SWI-Prolog**
    Run the main file in your terminal:
    ```bash
    swipl main.pl
    ```

2.  **Start the Application**
    Once inside the Prolog environment, launch the main menu by typing:
    ```prolog
    main.
    ```
3.  **Navigating the Menu**
    The `main_menu` will likely guide you through options such as:
    * **Play:** Start a new game.
    * **Solver:** access the helper tool.
    * **Exit:** Quit the application.

## Authors
* **Tomas Simoes** - [GitHub Profile](https://github.com/Tomas-Simoes)
