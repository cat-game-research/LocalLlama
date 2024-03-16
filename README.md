# LocalLlama

LocalLlama is a cutting-edge Unity package that wraps OllamaSharp, enabling AI integration in Unity ECS projects. It's designed for developers looking to incorporate multi-agent systems for development assistance and runtime interactions, such as game mastering or NPC dialogues.

## Features

- **Local and Remote Execution**: Run llama2 AI locally or via client-server architecture.
- **Multi-Agent System**: Support for multiple AI agents.
- **Development Tools**: Code authoring, project editing, testing, and troubleshooting within Unity.
- **In-Game Console**: Access AI functionalities at runtime through an in-game console.
- **Editor Integration**: Use menu commands and panels for easy access in the Unity editor.
- **C# Binding**: Includes a C# DLL for direct interaction with OllamaSharp.

## Installation

1. Open your Unity Project
2. Navigate to the Package Manage
3. click on the + icon in top left
4. select install with git url
5. paste `https://github.com/cat-game-research/LocalLlama.git` into the field.

## Development

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/LocalLlama.git
   ```
2. Run the setup script:
   ```
   bin\setup.bat
   ```

## Usage

Add LocalLlama as a package in Unity, and it will be downloaded from GitHub. Utilize the in-game terminal or editor menus to interact with the AI. For detailed usage, refer to the `Examples` directory.

## Contributing

Contributions are welcome! Please adhere to the [Unity Style Guide](https://github.com/cat-game-research/unity-style-guide).

## License

LocalLlama is available under the MIT License. See `LICENSE.md` for more details.

## Support

For support or feedback, join our Discord community (coming soon).

## Citation

If you use LocalLlama in your research or project, please cite as follows:

```
@misc{LocalLlama,
  author = {cat-game-research},
  title = {LocalLlama - Unity Package and API for local Llama2 models using OllamaSharp},
  year = {2024},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\\url{https://github.com/yourusername/LocalLlama}}
}
```
