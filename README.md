# TODOTOGO  (WIP)

TODO-to-go is a tool to find any TODO go comment in source code and show where is it 

## Usage

```bash

# Show all TODO Comment in current working directory
todotogo 

# Show all TODO Comment in some-file.go
todotogo some-file.go

# Show all TODO Comment with tag "FIXME" in current working directory
todotogo -tag=FIXME 

# Show all TODO Comment with tag "FIXME" in some-file.go
todotogo -tag=FIXME some-file.go
```

## Limitation

TODO-to-go only working with single line comment of go language. No specific comment tag restriction

## More Information

TODO Comment is widely used ad-hoc code comment markup conventions to remind/give specific information for piece of code. 

Typically this is list of the comment tags:
- `NOTE`: Description of how the code works
- `HACK`: Not very well written or malformed code to circumvent a problem/bug.
- `XXX`: Warning about possible pitfalls.
- `FIXME`: This works, sort of, but it could be done better. (usually code written in a hurry that needs rewriting).
- `BUG`: There is problem here
- `TODO`: No problem, but addtional code needs to be written, usually when you are skipping something.
- `DOING`: Code is not completed yet

