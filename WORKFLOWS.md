# Workflows

## Integrated Environment

```markdown
┌───────────────────────────────────────────────────────────────┐
│                         Layer 0: OS / Terminal                │
│  Terminal Emulator (truecolor)  +  Shell(zsh/bash)            │
└───────────────────────────────────────────────────────────────┘
                │
                ▼
┌───────────────────────────────────────────────────────────────┐
│                         Layer 1: Session (tmux)               │
│  - Project sessions: llvm / system / paper / app              │
│  - Persistent panes: editor, build, debug, logs, remote ssh   │
└───────────────────────────────────────────────────────────────┘
                │
                ▼
┌───────────────────────────────────────────────────────────────┐
│        Layer 2: Cognitive Control Center (Emacs as Hub)       │
│  Org (tasks/notes) + Magit (git) + Dired/Projectile (nav)     │
│  + Compile/REPL + Diff/Review + LSP (optional)                │
│  + AI Orchestrator (Copilot + Claude prompts/log buffers)     │
└───────────────────────────────────────────────────────────────┘
                │
                ├──────────────────────────┐
                │                          │
                ▼                          ▼
┌──────────────────────────────┐  ┌─────────────────────────────┐
│  Layer 3A: Code Microscope   │  │ Layer 3B: Execution Surfaces│
│ (Helix: read/audit/deep code)│  │ (Shell/Build/Test/Debug)    │
│  - LSP jump/symbol trace     │  │ - build, unit tests, bench  │
│  - huge repo navigation      │  │ - lldb/gdb, perf, strace    │
│  - AST selection             │  │ - log tail, ssh, containers │
└──────────────────────────────┘  └─────────────────────────────┘
```


## Tmux Session Example

```markdown
┌──────────────────────────────┐
│ Pane 1: Emacs (org+magit+edit)│
├──────────────┬───────────────┤
│ Pane 2: Helix │ Pane 3: Shell │
│ (audit/read)  │ (build/test)  │
├──────────────┴───────────────┤
│ Pane 4: Debug/Logs/SSH        │
└──────────────────────────────┘
```

## Tasks


### Fast Prototype Creation

Vibe Coding: 
1. VSCode + Copilot
2. Emacs + Copilot

### Fine-grained Deep Coding

Using Helix:
1. Searching
2. Local functions/structure refactoring
3. Little bugs fixing

### Project Wrapping

Using Emacs:
1. magit stage
2. commit message
3. org mode
