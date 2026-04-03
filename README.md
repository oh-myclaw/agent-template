# ohmyclaw agent template

A starter set of files loaded into a new agent at https://ohmyclaw.ru.

## Required files

Files that must be present in the template repository:

* `HEARTBEAT.md`
* `IDENTITY.md`
* `SOUL.md`

## File contents

### [AGENTS.md](AGENTS.md)

The agent’s main instructions.

### [BOOTSTRAP.md](BOOTSTRAP.md)

Instructions loaded during the first interaction with the agent. Specify what the agent should ask the user and save into its instructions.
Usually, the file ends with a note that the agent should delete this file.

### [HEARTBEAT.md](HEARTBEAT.md)

The agent adds tasks to this file that it should complete later.
Every 5 minutes, the agent is started with instructions from this file.

### [IDENTITY.md](IDENTITY.md)

Information about the agent itself.
Within this template, based on [BOOTSTRAP.md](BOOTSTRAP.md), the agent asks the user for this information during the first interaction and writes it into the file.
You can adjust `BOOTSTRAP.md` and predefine key information about the agent in advance.

### [MEMORY.md](MEMORY.md)

General memory.
The agent also has specialized semantic memory.
It can store important facts in this file at its own discretion.

### [SOUL.md](SOUL.md)

The agent’s “soul”.

### [TOOLS.md](TOOLS.md)

Tools available to the agent.
Here you can specify which additional CLI tools and environment variables are available to the agent, and how to use them.

### [USER.md](USER.md)

Information about the user.
Relevant in the case of a personal agent.
