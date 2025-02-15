# About

Collection of utilities I use on the command line. Not organized in any specific way.

Mostly Python scripts. Increasingly Python scripts designed around [uv](https://docs.astral.sh/uv/), using `#!/usr/bin/env -S uv run --script` and [PEP 723](https://peps.python.org/pep-0723/) script dependency comments to simplify running without managing Python virtual environments.  Many thanks to [Simon Willison](https://simonwillison.net/2024/Dec/19/one-shot-python-tools/) for evangelizing this approach.

My related browser-based repository: [mbafford/browser-tools](https://github.com/mbafford/browser-tools) - some scripts here have HTML "run anywhere" versions there.

# Scripts

- `dates2cal` [html version](https://tools.bafford.us/dates2cal) - Takes date ranges from stdin and outputs a 3 column yearly calendar with represented dates marked on the calendar.
- `summarize_json` [html version](https://tools.bafford.us/summarize-json) - Takes JSON data and provides a summary of the fields, data types, and values represented in.  Syntax similar to [gron](https://github.com/tomnomnom/gron) but more about understanding the full dataset vs. individual records.