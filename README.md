# Meteor HMR + Svelte issue reproduction

Editing files in packages cause a full reload instead of hot module replacement, at least when using `zodern:melte` with Meteor HMR.

This repostiroy demonstrates that behavior.

### Instructions

1. Clone repo
2. Run `npm install` in `/app/`
3. Run `meteor` in `/app/`
4. Edit `/packages/ui/Box.svelte` and see how the app reloads completely.