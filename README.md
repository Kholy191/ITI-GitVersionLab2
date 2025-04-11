## Q1 = How to delete branch remote and local

- git branch -d branch*name /*for soft branch: delete only merged branches\*/
- git branch -D branch*name /\_Force Delete: delete the branch in any case*/

## Q2 = Annonated vs Lightweight

- Annonated tags have messages, Date, and the name of the creator
- while Lightweight named with the name of Commit and has no stored data
- Annonated is better in Releasing versions
- git tag -a v1.0 -m "Release version 1.0" /_Anonnated_/
- git tag v1.0 /_ LightWeight_/

## Q3 = When to use Rebase?

- When u need to get a much cleaner project history.
- when u want to make the branch up to date with all data from the base
- it should never be used on a branch which is shared with another developer (Unless both developers are kind of git experts).
- Source: "https://medium.com/@harishlyadav/when-to-use-git-rebase-explained-3c8192cba5c7"

## Q4 = How to list tags

- git tag

## Q5 = How to delete tags

- Local: git tag -d tag_name
- remote: git push origin --delete tag_name

![The Image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRLat8bZvhXD3ChSXyzGsFVh6qgplm1KhYPKA&s)
