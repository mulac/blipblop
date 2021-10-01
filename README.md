# blipblop

## Requirements
1. Make sure Go is installed (it's super easy)
2. done

If you haven't used Go before, welcome to the simple life...

> Mixing languages is better than writing everything in one, if and only if using only that one is likely to overcomplicate the program - Eric Steven Raymond

## Go Modules

This is a monorepo - all root folders are seperate modules.  The **core** module is where all the 'core' Go data is stored, this should not depend on any other module.  Go modules allow us to separate dependancies between projects.  The go.mod file lists the dependancies, go automatically manages these as you import them, downloading and installing them whenever you compile or run your code.

## Contributing
Make your change in a feature branch i.e. `scraper/feature/apify-concurrent`

Make sure you're code is readable and you have `go fmt` your files before pushing.

Then submit a PR which must get approval from at least one other dev.

