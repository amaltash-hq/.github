# Amaltash

Free finance calculators for your AI chat, with charts you can change. Plus AI investing in plain English: turn your idea into rules you can read.

[Website](https://amaltash.com) · [Calculator docs](https://amaltash.com/mcp/calculators) · [Trading docs](https://amaltash.com/mcp) · [Plugins](https://github.com/amaltash-hq/mcp) · [Privacy](https://amaltash.com/policies/privacy#calculators-connector) · [Contact](https://amaltash.com/contact)

## Free finance calculators for AI chat

Ask a money question in your AI chat. Get the math and a chart you can change. No account needed.

- **Compound interest calculator.** Daily, monthly or yearly compounding.
- **Investment calculator.** See what a monthly amount could grow to.
- **Retirement calculator.** See how long savings may last. Test the 4% rule.
- **CD and high-yield savings calculator.** See the interest on a CD or a savings account.
- **S&P 500 calculator.** Replay real yearly S&P 500 returns since 1928.
- **Stock return and DCA calculator.** Compare a lump sum with dollar-cost averaging for a stock or fund.
- **Net worth calculator.** Add up what you own and what you owe. Compare by age.
- **Risk calculators.** Loss recovery, position size and T-bill ladder.

Every result says how it was worked out and what it assumes.

- Docs and examples: https://amaltash.com/mcp/calculators
- Plugins: https://github.com/amaltash-hq/mcp
- MCP server, no sign-in: `https://tools.amaltash.com/mcp`

## AI trading strategies

Amaltash uses AI to build Investing Strategies. Describe a trading idea in plain English. Amaltash turns it into clear rules you can read. Like algo trading, without writing code.

- **Test before you fund.** Each Strategy is backtested on years of market data. Backtested results are hypothetical. They don't promise future results.
- **You approve it.** You approve every Strategy before it goes live.
- **You set limits.** Each Strategy has limits, like a stop-loss. Limits help manage risk. They can't stop every loss.
- **What it covers.** US stocks, ETFs and crypto.

The trading plugin lets an AI assistant build and backtest Strategies and use paper trading. Real money needs a separate permission that you turn on. Each live Strategy waits for your approval. An assistant can never withdraw money.

Learn more at https://amaltash.com

## Install in Claude Code

```
/plugin marketplace add amaltash-hq/mcp
/plugin install calculators@amaltash
/plugin install trading@amaltash
```

## FAQ

**Is it free?**
The calculators are free. The trading plugin needs an Amaltash account. See [pricing](https://amaltash.com/pricing).

**Do I need an account?**
Not for the calculators. You don't sign in, and they don't ask for personal data. The trading plugin asks you to sign in to Amaltash.

**Where does the data come from?**
Stock answers cover more than 12,000 US stocks and funds. That data updates nightly. S&P 500 and retirement math use yearly US returns since 1928, from NYU Stern. The net worth check uses the Federal Reserve's 2022 Survey of Consumer Finances.

**Can the calculators trade or move my money?**
No. They only do math. They can't trade or move money.

**Which AI apps does it work with?**
Claude Code, with the plugins above. Any AI app that supports MCP can add the calculator server at `https://tools.amaltash.com/mcp`.

**Is this investment advice?**
No. Read the note below.

**Who makes Amaltash?**
Amaltash Advisors LLC.

## Important

Results are for education only. They are not investment advice or a promise of future results. Projections are hypothetical. Past results don't predict future ones. You can lose money.
