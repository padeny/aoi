
# Aoi (葵)

[中文说明](/README-cn.md)

Ghost in the Shell powered by ChatGPT

**Aoi** is an AI-based conversational agent powered by ChatGPT. With Aoi, you can have natural language conversations with an AI in the terminal that can understand your queries and execute appropriate commands.

## Features
You can use Aoi as a terminal version of ChatGPT, Besides, Aoi comes with several built-in features that can help you be more productive:

- `/code` - Generate code snippets and **auto copy** them to the clipboard, e.g. `/code go generate random numbers`
- `/db` - **Auto load database schema** and **execute SQL**, e.g. `/db postgres://user:passwd@host/db list tables`
- `/shell` - Generate shell command and **execute it**, e.g. `/shell view listening ports`
- `/ssh` - Generate shell command and execute it on the remote host, e.g. `/ssh {host} view listening tcp ports`
- `/tldr` - Get a tl;dr explanation of a command
- `/trans` - Translate text to a specified language
- `/copy` - Copy the last reply


## Getting Started
You can download Aoi from the GitHub [release page](https://github.com/shellfly/aoi/releases). Alternatively, you can use Go to install Aoi on your system:

```bash
go install github.com/shellfly/aoi@latest
```

Set your OpenAI API key as an environment variable, and then run the `aoi` command.

```bash
export OPENAI_API_KEY=<your_api_key>
aoi
```
If necessary, you can also customize the OpenAI API BASE URL as an environment variable.

```bash

export OPENAI_API_BASE_URL=<your_custom_api_base_url>
```

## Demos

### shell
[![shell](/doc/shell.gif)](https://asciinema.org/a/XjCGaMNf8Qp2nQ1UDlehjm5AN)

### database
[![pg](/doc/pg.gif)](https://asciinema.org/a/568712)
## Contributing
If you find any issues with Aoi or have suggestions for new features, please feel free to create an issue or submit a pull request on the GitHub repository. Contributions from anyone and everyone are welcome!
