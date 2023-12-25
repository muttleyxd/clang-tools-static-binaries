# clang-tools static binaries

Includes clang-format, clang-tidy and clang-query.

## Download

Grab clang-tools static binaries for your platform from [Releases](https://github.com/cpp-linter/clang-tools-static-binaries/releases) tab!

## Motivation behind this repo

I use to contribute to different repositories and they often use different versions of clang-format.

I could either compile clang-format for each one I want to have or I could try messing up with my package system (I use Arch Linux btw) and try installing all of them on my system.
This can very quickly get out of hand, hence I created this repository.

These binaries aim to:
- be as small as possible
- not require any additional dependencies apart from OS itself

## How can I trust this repository?

- Verify sha512sums of binaries against output from GitHub Actions to make sure binaries are not modified
- Fork this repository and run GitHub actions on your behalf
- Build manually using steps using commands from [.github/workflows](https://github.com/cpp-linter/clang-tools-static-binaries/tree/master/.github/workflows)

## More clang-tools

If there's any interest I could add more tools, or a build for new OS (ex. FreeBSD)
