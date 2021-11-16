# Slack emoji

Automatically set your Slack status emoji based on the current window you have open.

## Requirements:

- Mac OS (requires AppleScript)
- Ruby (a new enough version to have JSON, YAML & Date gems included)
- A Slack API token
- cUrl
- Permissions to access accessibility options for your terminal (via System preferences > Security & Privacy > Privacy > Accessibility)

## Usage:

Don't.

But if you must, make sure your statuses.yml is up to date (with valid app names and emoji
names), and that you `SLACK_TOKEN` is set as an env variable, and then run it with `./run`.
You probably want to set this to run on a schedule as a cronjob - see Slack's [docs](https://api.slack.com/methods/users.profile.set) for more info on
rate limits.
