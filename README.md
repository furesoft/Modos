# Modos
Modos is a modular operating system. It will be focused on modularity. It consists of the main Components that every OS need. All other stuff is optional and can be installed/removed when you want

While the setup is going it will display a Dialog which components you want to install. You can select from a public repository or you ca use a custom one. Every no needed Application or Feature can be removed

Included in the Base-Kernel:
- Pluggable Driver System
- different drivers thats have to be to run and communicate (Network, FAT, Keyboard, Mouse, Drawing, UI-Compositor)
- Pluggable Virtual Filesystem
- Pluggable Program environment. You could focus on non-managed applications or managed .net applications. Modos will install the .Net Executor by default. You can easily create your own environments
- Event-Handling System
- Message based Communication between Applications
- Procces-Management

Possible Modules:
- Multi-User
- Different Filesystems
- Different Runtime Execution Engines (Native, .Net)
- Server-Module to only use terminal
- Paket Manager
