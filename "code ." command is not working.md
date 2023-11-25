Estimated waste of time fixing this instead of doing your work: 30 mins to 1 hour

TLDR: Throw VS Code in the Applications Folder, uninstall code, reinstall code

---

```mermaid
flowchart TD
    A{Is VS Code in the Applications Folder?}
    A -- Yes --> B[cmd + shift + p]
    A -- No --> C[Please put it there, dear engineer with no license]
    C --> B
    B --> D['uninstall code']
    D --> E['install code']
    E --> F{Did it work?}
    F -- Yes --> G[Well done, engineer with no license but we are not done]
    F -- No --> h[Throw that overpriced thing away]
    G --> H[Please restart your box]
    H --> I[Does 'code .' still work?]
    I -- Yes --> J[Not bad for an engineer with no license]
    I -- NO --> h
```

---


  References because I did not come up with that (they didn't either but an engineer with no license needs validation hey)
  
  https://stackoverflow.com/questions/29955500/code-is-not-working-in-on-the-command-line-for-visual-studio-code-on-os-x-ma

  https://stackoverflow.com/questions/69004740/vs-code-denied-permission-unlink-usr-local-bin-code
