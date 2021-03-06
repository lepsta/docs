## uju

A version control tool for source code

### Synopsis

A version control tool for source code

```
uju [flags]
```

### Options

```
  -A, --deamon_address string   The URL of the System daemon (default "http://localhost:6060")
  -h, --help                    help for uju
      --repo string             Repo ID, name or path to use for the current operation
  -v, --version                 Display the current version of this program
  -y, --yes-all                 Silences the prompts a proceed as though the users answeres Yes to all prompts
```

### SEE ALSO

* [uju apply](uju_apply.md)	 - Pushes current state to nodes after changes introduced through undo or revert.
* [uju cat](uju_cat.md)	 - Prints file content at a specific revision. Defaults to current soft state.
* [uju changes](uju_changes.md)	 - Displays a list of files that have changed on the soft state.
* [uju commit](uju_commit.md)	 - Commits soft state changes to the hard state
* [uju config](uju_config.md)	 - Used to access / manage Uju configuration
* [uju conflicts](uju_conflicts.md)	 - Lists files that have conflicts with the current state
* [uju diff](uju_diff.md)	 - Shows the changes between two revisions of a file
* [uju discard](uju_discard.md)	 - Discards uncommited file changes from the soft state.
* [uju docs](uju_docs.md)	 - Generates commandline interface documentation
* [uju download](uju_download.md)	 - Download the repo from a server replica.
* [uju export](uju_export.md)	 - Exports repository files at the specified state to a directory
* [uju git](uju_git.md)	 - Run Git commands on an Uju repo.
* [uju init](uju_init.md)	 - Initialize a new repo
* [uju log](uju_log.md)	 - Shows the history of the current state. If file name is specified it will show history of that file in the current state.
* [uju login](uju_login.md)	 - Log in using your Lepsta account credentials.
* [uju logout](uju_logout.md)	 - Log out of System on this machine
* [uju ls](uju_ls.md)	 - Lists all files in the current state.
* [uju merge](uju_merge.md)	 - Merges the supplied hard state into the current hard state
* [uju publish](uju_publish.md)	 - Publishes repo online.
* [uju redo](uju_redo.md)	 - Redo changes to the specified revision.
* [uju replica](uju_replica.md)	 - Adds a replica repo to the current repo
* [uju repo](uju_repo.md)	 - Manage a repository
* [uju repos](uju_repos.md)	 - Lists all the repos.
* [uju rm](uju_rm.md)	 - Delete one or more repositories
* [uju state](uju_state.md)	 - Manage states. Default creates a new hard state
* [uju states](uju_states.md)	 - Shows a list of states on the repo.
* [uju stats](uju_stats.md)	 - Gets info from the running uju daemon
* [uju switch](uju_switch.md)	 - Switches to the state and start tracking changes under it.
* [uju system](uju_system.md)	 - System info / management
* [uju token](uju_token.md)	 - Generates access tokens for API access.
* [uju undo](uju_undo.md)	 - Undo changes to the specified revision.
* [uju update](uju_update.md)	 - Updates your files with the latest changes from the server replica.
* [uju upload](uju_upload.md)	 - upload to the Uju repo.
* [uju validate](uju_validate.md)	 - Validate a repository

###### Auto generated by spf13/cobra on 6-Sep-2020
