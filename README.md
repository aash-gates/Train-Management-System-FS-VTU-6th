# Train Search Program

This program is designed to make the search for trains easier for the user. It is implemented in the C programming language and incorporates file handling and the linked list data structure for searching and sorting train and route data. The program also includes a basic GUI to facilitate user interaction.

## Features

- Train and route data management: The program allows you to store and manage train and route information, including train numbers, source, destination, and timing.

- Sorting: You can sort the train data based on various criteria such as timing.

- Searching: The program enables you to search for trains based on source, destination, and timing.

- Graphical User Interface (GUI): The GUI provides a user-friendly interface where users can input their desired source, destination, and timing, and view the search results.

## Prerequisites

To run this program, you need to have the following installed on your system:

- C compiler (e.g., GCC)
- GTK+ library (for the GUI)

## Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/aash-gates/Train-Management-System-FS-VTU-6th.git
   ```

2. Navigate to the project directory:

   ```bash
   cd train-search-program
   ```

3. Compile the program using the C compiler:

   ```bash
   gcc -o train_search train_search.c `pkg-config --cflags --libs gtk+-3.0`
   ```

4. Run the program:

   ```bash
   ./train_search
   ```

## Usage

1. Launch the program, and the GUI window will appear.

2. Input the desired source, destination, and timing in the corresponding fields.

3. Click the "Search" button to initiate the search.

4. The search results will be displayed in the GUI window.

## Contributing

Contributions to this project are welcome. Feel free to open issues and submit pull requests to suggest improvements or fix any bugs.


You can modify this template according to your project's specific details, requirements, and license. Include any additional information, screenshots, or instructions that you think would be helpful for users who want to understand and use your train search program.
