# Expo CLI Development Server Port Conflict

This repository demonstrates a common issue encountered when using the Expo CLI: the development server failing to start due to a port conflict.  The problem arises when the port specified in the Expo CLI command is already in use by another process (e.g., another application, a previous Expo instance). 

This example provides a basic Expo application and illustrates the solution to resolve the port conflict.

## How to Reproduce

1. Clone the repository.
2. Run `expo start`.
3. If the default port (19000) is already in use, the server will fail to start.
4. Then, use the solution to fix the issue.

## Solution

The solution involves specifying a different port using the `--port` or `-p` flag with the `expo start` command.