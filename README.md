Manage your github watchings

 - create a [application token](https://github.com/settings/applications) with read access
 - `gem install github-watching`
 - `github-watching sub-command arguments`
 - follow instructions

```
bundle

# list unwatched owned repos
github-watching unwatched grosser
Loading /users/grosser/subscriptions page 1
...
Loading /users/grosser/subscriptions page 4
Loading /users/grosser/repos page 1
...
Loading /users/grosser/repos page 5
122 unwatched repos
grosser/active_record-comments
grosser/addressable
grosser/airbrake_tools
grosser/air_man

# TODO: more features
```

Author
======

[Michael Grosser](http://grosser.it)<br/>
michael@grosser.it<br/>
License: MIT
