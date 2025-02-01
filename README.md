# Text Analyzer Application

This is a simple text analyzer application built using F# and Windows Forms. The application allows users to load a text file, analyze the text, and view various statistics such as word count, sentence count, paragraph count, average sentence length, and the most frequent words.

## Features

- **Load Text File**: Users can load a text file (`*.txt`) into the application for analysis.
- **Analyze Text**: The application analyzes the loaded text and provides the following statistics:
  - **Word Count**: Total number of words in the text.
  - **Sentence Count**: Total number of sentences in the text.
  - **Paragraph Count**: Total number of paragraphs in the text.
  - **Average Sentence Length**: Average number of words per sentence.
  - **Most Frequent Words**: A list of the most frequently occurring words in the text.
- **Clear Input**: Users can clear the input text and reset all statistics.

## How to Use

1. **Load a Text File**:
   - Click the "Load File" button in the sidebar.
   - Select a text file (`*.txt`) from your file system.
   - The content of the file will be loaded into the input text box.

2. **Analyze the Text**:
   - Click the "Analyze" button in the sidebar.
   - The application will process the text and display the analysis results in the respective panels.

3. **Clear the Input**:
   - Click the "Clear" button in the sidebar to clear the input text and reset all statistics.

## UI Components

- **Header**: Displays the title "Text Analyzer".
- **Sidebar**: Contains buttons for loading a file, analyzing text, and clearing the input.
- **Content Area**:
  - **Input Text Box**: Displays the loaded text or allows manual text input.
  - **Output Panels**: Display the analysis results including word count, sentence count, paragraph count, average sentence length, and most frequent words.

## Code Structure

The application is structured as follows:

- **Form2**: The main form of the application, which inherits from `Form`.
  - **UI Components**: Various UI elements such as panels, labels, buttons, and text boxes are defined and initialized.
  - **Event Handlers**: Event handlers for button clicks are defined to handle loading files, analyzing text, and clearing input.
  - **Text Analysis Logic**: The `analyzeText` function processes the input text and calculates the required statistics.

## Requirements

- **.NET Framework**: The application is built using .NET and requires the .NET Framework to run.
- **F#**: The application is written in F#.

## Running the Application

1. Clone the repository or download the source code.
2. Open the solution in an IDE that supports F# (e.g., Visual Studio).
3. Build and run the application.

## Example

Here is an example of how the application might look when analyzing a text file:

- **Input Text**: "Hello world! This is a test. This is only a test."
- **Output**:
  - **Word Count**: 10
  - **Sentence Count**: 2
  - **Paragraph Count**: 1
  - **Average Sentence Length**: 5
  - **Most Frequent Words**: 
    - this: 2
    - is: 2
    - a: 2
    - test: 2
    - hello: 1

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.
