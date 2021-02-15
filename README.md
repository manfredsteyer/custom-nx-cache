# Custom Nx-Cache

Example for an custom Nx Cache that is just copying the cached files from another folder for the sake of demonstration. 

- See ``tools/task-runners``
- See nx.json
  - The taskRunner points to our custom implementation
  - Adjust folders accordingly
- Build custom-task-runner: ``npm run build:custom-task-runner``
- ``nx build luggage --with-deps``