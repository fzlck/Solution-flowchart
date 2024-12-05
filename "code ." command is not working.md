| Estimated waste of time     | Frustratometer |
| ----------- | ----------- |
| 30 mins - 1 hour      | ![](https://geps.dev/progress/10?dangerColor=006600)       |



TLDR: Throw VS Code in the Applications Folder, uninstall code, reinstall code

---

```mermaid
flowchart TD
    A{Is VS Code in the Applications Folder?}
    A -- Yes --> B[cmd + shift + p]
    A -- No --> C[Please put it there]
    C --> B
    B --> D['uninstall code']
    D --> E['install code']
    E --> F{Did it work?}
    F -- Yes --> G[Well done, but we are not done yet]
    F -- No --> h[Touch grass]
    G --> H[Please restart your box]
    H --> I[Does 'code .' still work?]
    I -- Yes --> J[Well done]
    I -- NO --> h
```

---


  References:
  
  https://stackoverflow.com/questions/29955500/code-is-not-working-in-on-the-command-line-for-visual-studio-code-on-os-x-ma

  https://stackoverflow.com/questions/69004740/vs-code-denied-permission-unlink-usr-local-bin-code
