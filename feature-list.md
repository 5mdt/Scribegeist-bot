# 📋 Scribegeist-bot – Feature List

| 🧩 Feature                      | 📝 Description                                                                 | 👤 User Story                                                                                        |
| ------------------------------- | ------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------- |
| **Voice Message Transcription** | Automatically transcribes voice messages and replies with text in group chats. | *As a chat member, I want voice messages to be transcribed so I can read them instead of listening.* |
| **Multithreaded Processing**    | Uses multithreading to handle multiple audio messages concurrently.            | *As a user in a busy group, I want multiple transcriptions to happen smoothly, without delay.*       |
| **Welcome Message**             | Greets users when added to a new chat.                                         | *As a group admin, I want the bot to confirm it was added and is working.*                           |
| **`/help` Command**             | Provides basic instructions and supported commands.                            | *As a user, I want to know how to interact with the bot if I need help.*                             |
| **Healthcheck Endpoint**        | Exposes a `/health` REST endpoint for monitoring.                              | *As a dev/ops person, I want to check if the bot is running and healthy in production.*              |
| **REST API Mode**               | Can run as an HTTP service.                                                    | *As a developer, I want to deploy the bot in a Docker or cloud environment easily.*                  |
| **Direct Script Mode**          | Supports CLI-based execution.                                                  | *As a developer or tester, I want to run the bot directly without setting up a full server.*         |
