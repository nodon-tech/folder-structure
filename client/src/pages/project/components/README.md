pages/project/components

Components in here are components broken out from project.view.tsx to separate out pieces of logic that is self contained so the main view file doesn't get too long/complicated.

Components here have more lax requirements on interfaces etc. as they're always local to the project.view and should not be reused in other places.

This should be the first place you put new components in when building. If a component is deemed useful in other places, it should be reviewed/refactored and promoted up the tree to appropriate components folder.
