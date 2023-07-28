# React Text-to-Speech API
<br>

![React Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/1200px-React-icon.svg.png)
<br>

This project is a simple, efficient and robust Text-to-Speech API developed using React.js. This API converts user-inputted text into synthesized speech and then stores the resulting audio as an audio file within a GitHub repository. It is a powerful tool for content creators, developers, educators and anyone who wants to convert text into speech.

## Table of Contents

1. [Features](#features)
2. [Technologies](#technologies)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contribution](#contribution)
6. [License](#license)

## Features <a name="features"></a>

- Text to Speech Conversion: Convert any inputted text into synthesized speech.
- File Generation: Store the synthesized speech as an audio file.
- GitHub Integration: Save the audio files directly to a GitHub repository.

## Technologies <a name="technologies"></a>

- React.js
- Web Speech API
- GitHub API

## Installation <a name="installation"></a>

Firstly, you'll need to have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed on your computer. 

Clone the repository:

```bash
git clone https://github.com/9to5Network/react-text-to-speech.git
cd react-text-to-speech
```

Install dependencies:

```bash
npm install
```

Then, you need to create a `.env` file at the root of the project and add your GitHub Personal Access Token as `GITHUB_TOKEN`:

```env
GITHUB_TOKEN=your_personal_access_token
```

## Usage <a name="usage"></a>

To start the development server:

```bash
npm start
```

Then, open your web browser and visit `http://localhost:3000`. Enter the text you want to convert into speech into the text field and hit the 'Convert' button. The resulting audio will be saved as an audio file and stored in the specified GitHub repository.

## Contribution <a name="contribution"></a>

Contributions, issues and feature requests are welcome. Feel free to check issues page if you want to contribute.

## License <a name="license"></a>

React Text-to-Speech API is [MIT Licensed](./LICENSE).

---

Made with 💖 by [9to5Network Limited](https://www.9to5.live)
