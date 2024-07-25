# Sorting Algorithm Visualization

This project is a visualization tool for understanding sorting algorithms. It uses the Pygame library to create a graphical representation of sorting algorithms in action, making it easier to understand how these algorithms work step by step.

## Features

- Visualization of Bubble Sort and Insertion Sort algorithms.
- Real-time display of sorting processes.
- Ability to reset and re-sort with new random lists.
- Option to sort in ascending or descending order.
- Intuitive controls for easy interaction.

## Requirements

- Python 3.x
- Pygame library

## Installation

1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/sorting_visualization.git
   cd sorting_visualization
   ```

2. **Install Pygame**:
   ```sh
   pip install pygame
   ```

## Usage

1. **Run the script**:
   ```sh
   python sorting_visualization.py
   ```

2. **Controls**:
   - `R`: Reset the list to a new random set of numbers.
   - `SPACE`: Start sorting the current list.
   - `A`: Set sorting order to ascending.
   - `D`: Set sorting order to descending.
   - `I`: Select Insertion Sort algorithm.
   - `B`: Select Bubble Sort algorithm.

## Description

This Python script leverages the Pygame library to create a window where sorting algorithms can be visualized in real-time. The window displays the current state of the list being sorted, with each element represented as a vertical bar whose height corresponds to its value. 

The program starts with a randomly generated list of numbers, which can be reset at any time using the `R` key. Users can choose to sort the list in ascending or descending order and can select between Bubble Sort and Insertion Sort algorithms using the `I` and `B` keys, respectively. The sorting process can be initiated by pressing the `SPACE` key, which will animate the sorting algorithm step by step.

## Credits

- Inspired by the tutorial from Tech With Tim: [Sorting Algorithm Visualizer](https://www.youtube.com/watch?v=twRidO-_vqQ&ab_channel=TechWithTim)

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

---

Feel free to customize this README to better fit your project and add any additional information you find relevant.
