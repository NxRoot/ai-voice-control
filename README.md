# AiVC - AI Voice Control

This project was developed in C# using .NET CLI.
 
[WATCH DEMO VIDEO](https://www.youtube.com/watch?v=y3oFwVHh8Yk)

<a href="https://www.youtube.com/watch?v=y3oFwVHh8Yk"><img src="https://i.ibb.co/Vpp4JKMT/Captura-de-ecr-2025-04-04-152350.png" style="width: 80%;"></img></a>

## Features

* 💯 &nbsp;Control your PC using speech recognition.
* ✍️ &nbsp;Create your own scripts and execute as commands.
* 🚀 &nbsp;Fastest speech recognition in the world.

## How to Install
| Exe    | Description | Releases |
| -------- | ------- | ------- |
| <a href="https://github.com/NxRoot/ai-voice-control/archive/refs/heads/master.zip"><img style="min-width: 40px;min-height: 40px; width: 40px;" src="https://i.ibb.co/Vcqcs813/icon-3.png"/></a> | Download the latest version   | [Download](https://github.com/NxRoot/ai-voice-control/archive/refs/heads/master.zip)    |

## Requirements

* [.NET Framework 4.7](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net47).

## Configuration

* Click the `Config` button inside the tray icon on windows taskbar.

<img src="https://i.ibb.co/zh96Ddm6/Captura-de-ecr-2025-04-04-165141.png"></img>

* This will take you to the `config.json` file inside the download folder. 
* After making your changes you must restart the application.

```
[
    {
        "input": ["open google"],
        "command": "start https://google.com"
    },
    {
        "input": ["open netflix"],
        "command": "start https://netflix.com"
    },
    {
        "input": ["open youtube"],
        "command": "start https://youtube.com"
    },
    {
        "input": ["open chat gpt", "open chatgpt"],
        "command": "start https://chatgpt.com"
    },
    {
        "input": ["open console", "open terminal"],
        "command": "start"
    }
]
```

## &nbsp;
⭐ If you find this useful!
