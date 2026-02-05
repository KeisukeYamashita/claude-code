# Money Forward Commands

A collection of commands for Money Forward Cloud Expense.

## Commands

| Command | Description |
|---------|-------------|
| `expense-commute` | Submit commute expenses to Money Forward Cloud Expense |

## Install

### Set up marketplace

> [!TIP]
> If you've already setup your marketplace, there is no need to do this everytime.

First, register the marketplace to your Claude Code.

```console
claude plugin marketplace add KeisukeYamashita/claude-code
```

### Install the plugin

You can run `/plugins` command on Claude Code and search the plugins in `Discover` tab or you can run this command:

```console
claude plugin install money-forward-expense@KeisukeYamashita/claude-code
```

Also install [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser) for operating on the browser.

```console
npm install -g agent-browser

# Install the browser
agent-browser install
```

## Usage

After installation, you can run the following commands in Claude Code.

### Submit Commute Expenses

```
/money-forward:expense-commute I commuted 5,20,25 this month.
```
