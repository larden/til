# TIL
> Today I Learned
A collection of concise write-ups on small things I learn day to day across a
variety of languages and technologies. These are things that don't really
warrant a full blog post.

_2 TILs and counting..._

---
### Categories
* [Unix](#unix)

---
### Unix

- [Check/Set sys-root directory for cross compiler](unix/cross-compiler-sys-root.md)
- [Grep only specific files](unix/grep-only-specific-files.md)

## Usage
To auto-generate[^](##about "Go to About") the README.md file, you can run
```
    ./createReadme.py > README.md
```
If you are using git, you can install this script as a pre-commit git hook so
that it is autogenerated on each commit.  Use the following command:
```
    cd .git/hooks/ && ln -s ../../createReadme.py pre-commit && cd -
```

## About
I shamelessly stole this idea from:

 * [thoughtbot/til](https://github.com/thoughtbot/til) * [til-collective/til-collective](https://github.com/til-collective/til-collective)
 * createReadme has been copied from [](https://github.com/til-collective/til-collective/pull/6)
