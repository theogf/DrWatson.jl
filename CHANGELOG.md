# 0.3.0
* Added `test` as a directory of the default project (#43)
# 0.2.1
* Improve type-stability of return value of `dict_list` (#41)
# 0.2.0
* Changed `path` and `projectpath` arguments of various functions (e.g. `tagsave`, `current_commit`) to `gitpath` universally.
* make keyword arguments of `tagsave` positional arguments instead (to work with the macros)
* Added two new macros: `@tag!` and `@tagsave`: these do the same thing as `tag!, tagsave` but in addition are able to record both the script name that called them as well as the line of code that they were called at.
# 0.1.0
This is the first beta release! Changelog is kept with respect to here!
