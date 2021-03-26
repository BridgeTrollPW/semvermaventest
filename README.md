# semvermaventest

# Release
* Entscheidung was die nächste Version werden soll
* `mvn -B gitflow:release -P release-major`
* `mvn -B gitflow:release -P release-minor`
* `mvn -B gitflow:release -P release-patch`

# Hotfix

# Feature / Task
* ganz normal einen td-..... task-branch anlegen
* beim pr checken `mvn gitflow:feature-finish -DfeatureBranch=ta-.... -DkeepBranch=true`