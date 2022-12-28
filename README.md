# GoDiscordBot Template
GoDiscordBot is a Discord bot template repository that helps you quickly get started builing a Discord bot in go.

Get GoDiscordBot in your discord [here](https://link-to-bot.com.

Bot Commands:
```
/command1 - does this
/command2 - does this 
/command3 - does this
```

## Development:
1. Compile and run the project.

    ```
    TOKEN=abc123 go run main.go
    ```

2. Alternatively, build and run the project inside of a container.

    ```
    docker build -t bot . && docker run -d --env TOKEN='abc123' bot
    ```