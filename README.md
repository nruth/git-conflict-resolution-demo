To trigger the merge conflict:

    git checkout master
    git merge no_lemons

output will be something like:

    Auto-merging pancakes.md
    CONFLICT (content): Merge conflict in pancakes.md
    Automatic merge failed; fix conflicts and then commit the result.

now you can either:

  * (recommended) edit the file manually, save the finished version, then `git commit`
  * use `git mergetool` (can be confusing, especially on Mac)

It may be helpful to say something about how/why you resolved the conflict in your merge conflict commit message.

Recipe adapted from [Delia Smith](http://www.deliaonline.com/recipes/cuisine/european/english/basic-pancakes-with-sugar-and-lemon.html).