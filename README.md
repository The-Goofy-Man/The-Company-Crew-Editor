# Lethal-Company-Crew-Editor

A Lethal Company crew editor that is open source, built-in C#, .NET 8.0, using WPF. If you are looking for a download/release click the releses tab right there -----> <br><br>
Click below to watch the previous maintainers YouTube video showcasing the tool👇<br><br>
[![YouTube Video](https://img.youtube.com/vi/GG6tZs23O1Q/0.jpg)](https://www.youtube.com/watch?v=GG6tZs23O1Q)

## Table of Contents
- [Background](#background)
- [Features](#features)
- [Goals](#goals)
- [Usage](#usage)
- [Contributing](#contributing)
- [Developers](#developers)

## Background
This project was created because I was curious about how Lethal Company worked as a whole so I began taking apart piece by piece. Their crew system intrigued me and looking at current Lethal Company crew editors I saw a lack of user-friendly design and a lack of features within these crew editors.

## Features
- Automatic or Manual crew folder finder. Automatic looks for the crew files in their default directory while manual allows you to pick a folder to search
- Adapative crew file picker. If your folder has multiple or perhaps only a single crew file, the program does not force you to have all 3 crews in the same folder allowing you to copy a specific crew file to an isolated folder and tinker with it there safely.
- Feature-rich including player stat editor, ship unlock editor, game stats editor, and scrap/item editor.
- User-friendly UI
- Decide between saving the modified crew file to a different directory or directly to the game's crew files (through automatic finding)
- And other QOL features behind the scenes
![LCcrewEditor_QxRnPOCVzw](https://github.com/ArshansGithub/Lethal-Company-crew-Editor/assets/111618520/2495d997-6c6d-4e08-b669-5a6aeaf93881)

### Goals
- [ ] Make a raw editor for mods that use the same crew system the game does
- [ ] Code refactoring because I rarely use C# or .NET 

## Usage
Ensure you have .NET 8.0 installed, simply download the latest release, run the executable, and enjoy tinkering with your crews :)

## Contributing

Contributions are welcome. You can contribute by reporting issues, suggesting improvements, or submitting pull requests. To get started:

    Fork this repository.
    Create a new branch for your feature or bug fix: git checkout -b feature/your-feature.
    Make your changes and commit them.
    Push to your fork: git push origin feature/your-feature.
    Create a pull request.

Please ensure your code adheres to proper coding standards and includes relevant tests.

## Developers

If you are looking for IDs for the monsters, items, story logs, bestiaries, moons, and more... Look no further, I spent many hours scouring the source code and game objects to create the best enums containing all the IDs and their respective labeling.
https://github.com/ArshansGithub/Lethal-Company-crew-Editor/blob/main/LCcrewEditor/LCEnums.cs
