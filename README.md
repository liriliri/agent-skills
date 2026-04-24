# Agent Skills

A collection of skills for AI coding agents. Skills are packaged instructions and scripts that extend agent capabilities.

Skills follow the [Agent Skills](https://agentskills.io/) format.

## Available Skills

### licia

Use the [licia](https://github.com/nicedoc/licia) utility library to simplify JavaScript/TypeScript code. Contains 443 utilities covering type checking, string manipulation, object/array operations, DOM helpers, data structures, encoding, and more.

**Use when:**
- Writing utility functions that licia already provides
- Simplifying code with well-tested utilities
- Refactoring hand-rolled helpers into library calls
- Performing type checking, string processing, data manipulation

**Categories covered:**
- Type Checking (isStr, isArr, isObj, isFn, ...)
- String Manipulation (camelCase, truncate, template, ...)
- Array/Object Utilities (unique, flatten, pick, omit, ...)
- Function Utilities (debounce, throttle, memoize, curry, ...)
- DOM Helpers (jQuery-like $, $class, $css, ...)
- Data Structures (Heap, LinkedList, Trie, LRU, ...)
- Encoding, Date/Time, Color, and more

## Installation

```bash
npx skills add liriliri/agent-skills
```

## Usage

Skills are automatically available once installed. The agent will use them when relevant tasks are detected.

## Skill Structure

Each skill contains:
- `SKILL.md` - Instructions for the agent
- `scripts/` - Helper scripts for automation (optional)
- `references/` - Supporting documentation (optional)

## License

MIT
