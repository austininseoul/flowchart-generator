# Flowchart Generator

A web service that generates flowcharts using JavaScript and the Claude API.

## Features

- Generate flowcharts from natural language descriptions
- Renders flowcharts using the Mermaid.js library
- Simple and intuitive user interface
- Integration with Anthropic's Claude API for intelligent flowchart generation

## Getting Started

### Prerequisites

- Node.js (v14.0.0 or higher)
- An API key from Anthropic for Claude

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/austininseoul/flowchart-generator.git
   cd flowchart-generator
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file based on the `.env.example` file and add your Claude API key:
   ```
   CLAUDE_API_KEY=your_claude_api_key_here
   PORT=3000
   ```

4. Start the server:
   ```bash
   npm start
   ```

5. Open your browser and navigate to `http://localhost:3000`

## Usage

1. Enter a description of the flowchart you want to create in the text area
2. Click the "Generate Flowchart" button
3. Wait for the flowchart to be generated and displayed

## Example Input

```
Create a flowchart for troubleshooting a lamp that doesn't work. Check if it's plugged in first, then check if the bulb is burned out. If it's not plugged in, plug it in. If the bulb is burned out, replace it. Otherwise, repair the lamp.
```

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express
- **Flowchart Rendering:** Mermaid.js
- **AI Integration:** Anthropic's Claude API

## License

This project is licensed under the MIT License - see the LICENSE file for details.