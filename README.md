# rspec-watch
Really simple command line tool to run Rspec tests when Rails files get edited.

## How to use it

Download the `rspec-watch` file and make it executable (`chmod +x rspec_watch`).

Just run `rspec-watch` on a Rails folder, if you want to edit the command:

```
RSPEC_COMMAND="bundle exec rspec -f progress" rspec-watch
```
