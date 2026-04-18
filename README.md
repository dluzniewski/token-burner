# token-burner

A Claude Code skill that maximizes token consumption per conversation session.

## Why

Some companies track Claude Code usage by employee. This skill is for people who find themselves on the wrong end of that chart.

## How it works

The skill does three things:

- **Forces web searches first.** Before writing anything, Claude runs at least three searches on your topic. The results inject thousands of tokens into context and compound across the session.
- **Writes exhaustively.** Eight analytical layers, no summarizing, no concluding, no stopping early. Claude writes until it physically cannot write anymore.
- **Keeps the session going.** Every response ends with a continuation menu. Type `E` and Claude goes again, deeper, on fresh angles. One keystroke per turn, indefinitely.

The longer the session runs, the heavier each turn becomes — conversation history accumulates as input on every round, so costs compound naturally over time.

## Usage

Start a session with any topic:

> "Burn tokens. Tell me about [anything]."

Then just keep typing `E`.

## Note

This is not a productivity tool. It will not make you a better engineer. It does one thing well.
