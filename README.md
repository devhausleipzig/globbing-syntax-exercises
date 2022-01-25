# globbing-syntax-exercises
Globbing syntax exercises in the context of .gitignore and Git repos

## Outline

See the GNU globbing reference below for the more general BASH globbing syntax.

### Focusing on the variant of globbing used in .gitignore files

- Comment line: #
- Path section separator: /
- Single character wildcard: ?
- Character set and ranges: [ ][ - ]
- Wildcard: \*
- Globstar: \*\*
- Negative glob: !

## Resources

- [gitignore - Git Documentation](https://git-scm.com/docs/gitignore)
- [GNU Globbing Reference](http://tldp.org/LDP/GNU-Linux-Tools-Summary/html/x11655.htm)

## Getting the .gitignore highlighting to work on VSCode for these exercises
- `git reset`
- `git rm -rf my-little-project`
- `git commit -m "Remove my-little-project folder"`
- `git checkout HEAD~1 my-little-project`
- `git reset`