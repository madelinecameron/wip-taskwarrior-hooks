## WIP-TaskWarrior Hooks

Create, update and delete WIP to-dos from TaskWarrior. You obviously must have a [wip.chat](wip.chat) subscription for these hooks to be useful.

### Setup
1. Download and install [TaskWarrior](https://taskwarrior.org/download/)
2. `task init`
3. Download and install hooks
	- If you are using the binaries, copy them to the hooks directory (Possibly `~/.task/hooks`)
	- If you are using the JS files, also copy them to the hooks directory but make sure to run `npm install` first
4. Ensure that the hooks have run permissions
	- `task diagnostics` will tell you any issues and specifically if they need run permissions
5. Go to [wip.chat/api](wip.chat/api) and copy your API key
6.  Add the API key to TaskWarrior config
	- `task config wip.api_key <api key>`
7. Enjoy!

### Future work
- Syncing your WIP todos and TaskWarrior tasks on startup