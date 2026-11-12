# Mica

Master of Science in Business, major in Economics, BI.

Source for this page: [github.com/tinatoem/tinatoem.github.io](https://github.com/tinatoem/tinatoem.github.io)

## What I built in this course

- Session 1: this page.
- Session 2: [Using an MCP server](using-mcp.html)

Using an MCP server
Session 2, step 4. Second-year students: the Acemoglu model.

1. What an MCP server is, and why I trust datarobot.no/mcp
An MCP server is a program on the web or on your laptop that sends your agent tools, resources, and prompts and instructions when it connects. You can trust datarobot.no/mcp because its owner is known and its six ac_ tools only do narrow, visible calculations that check themselves against the numbers in Acemoglu (2024), though you should still spot-check a figure yourself.

2. My prompt and the tool my agent called
First run, with the paper's inputs:

Use the datarobot MCP server. List its tools for Acemoglu (2024), "The Simple Macroeconomics of AI". Run the one that computes the TFP gain over ten years with the paper's own inputs, and tell me which tool you called, what went in and what came back.

Second run, with the share of exposed tasks at 0.30:

Use the datarobot MCP server. Run the Acemoglu (2024) tool for the TFP gain over ten years with the paper's inputs, then again with the share of exposed tasks raised from 0.20 to 0.30. Tell me which tool you called, what went in, what came back, and which of the paper checks did not match.

The tool my agent called both times: ac_hulten on datarobot.no/mcp.

3. Both results
Inputs in both runs, from the paper: profitable share 0.23, labour cost saving 0.27, labour share 0.535, capital share 0.43, capital grows with output, ten years.

Run	Share of exposed tasks	GDP share of tasks affected	Overall cost saving	TFP gain over ten years	GDP gain over ten years
The paper's inputs	0.20	0.046	0.144	0.66 percent	1.17 percent
My change	0.30	0.069	0.144	1.00 percent	1.75 percent
4. Why the second result follows from the first
The share of tasks affected by AI rose by half, from 0.046 to 0.069, while the cost saving per task stayed at 0.144. Because the TFP gain is the affected share multiplied by the cost saving, it also rose by half, from 0.66% to 1.00%.

5. A number the paper prints that does not follow from its other numbers
The paper prints the annual TFP growth as 0.064% (pp. 29 and 42), but this does not follow from its own ten-year gain of 0.66%. Spread over ten years, 0.66% is about 0.066% per year (compounding gives the same result when rounded), so the printed figure should have been 0.066%.

- Session 2: [Our tutor, the design](https://tinatoem.github.io/team10/design.html)
