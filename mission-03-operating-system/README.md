cat > notes.md << 'EOF'
# Mission 3 Notes

## Task 3.1: Explore my operating system

| Information explored | What it tells you | My observation (privacy-safe) |
|---|---|---|
| Operating system / system details | Identifies the operating system, its version, build number and processor architecture. | My computer uses macOS. The version is 27.2.0, and the processor architecture is arm64. |
| Current account identity | Identifies which user account is currently active in Terminal. | The currently active account is [redacted]. |
| Available and used storage | Shows the total storage, used storage, available storage and percentage of storage occupied. | My main filesystem has 926 GiB of storage, 344 GiB used and 545 GiB available. |
| System activity snapshot | Shows running processes, CPU activity, memory usage and system load. | I observed multiple running processes, including background system processes and applications. CPU and memory usage showed the current activity of my computer. |

## Task 3.2: Processes

1. **What is a process?** A process is a program or application that is currently executing on a computer. Whenever I open an application, the operating system creates a process to run it.
2. **What does the PID column represent?** PID stands for Process Identifier. It is a unique numerical ID assigned to each running process so that the operating system can identify and manage it.
3. **Two example processes:**
   1. Google Chrome: a browser process that handles web browsing.
   2. Finder: a macOS process that manages files and folders.

## Task 3.3: Paths and permissions

An absolute path specifies the complete location of a file or folder starting from the root directory. A relative path specifies the location in relation to the current working directory. Absolute paths provide the full location, whereas relative paths depend on where I am currently working.

- Absolute path example from my repo: /Users/[redacted]/mission-02-terminal/README.md
- Relative path example from my repo: mission-02-terminal/README.md

**What permissions does the owner have?** Based on the permission string `-rw-r--r--`, the owner has read (`r`) and write (`w`) permissions but does not have execute (`x`) permission.

## Task 3.4: Operating-system responsibilities

| OS responsibility | Your explanation | Example |
|---|---|---|
| Process management | The operating system manages running programs and decides how the CPU's time is shared between them. | Running Google Chrome and a music player at the same time. |
| Memory management | The operating system manages RAM and allocates memory to different applications when they need it. | Giving Google Chrome memory to open and run multiple browser tabs. |
| Device management | The operating system controls hardware devices and helps applications communicate with them through drivers. | Connecting and using a keyboard, mouse or printer. |
| File management | The operating system organises, stores, retrieves and manages files and folders. | Creating, renaming, copying and deleting files in Finder. |
| User interface / shell | The operating system provides ways for users to interact with the computer through graphical interfaces or command-line interfaces. | Using Finder to manage files or Terminal to execute commands. |
| Security and permissions | The operating system protects files and system resources by controlling who can access or modify them. | Requiring permission to access certain files or change system settings. |
