# Contributing to ChunkyPNG

I will gladly accept any contributions from anybody to improve this library. However, I like to keep
the scope and complexity of this project relatively small. This way, with the limited amount of time I
dedicate to this project, this library remains a solid piece of software that many people rely on in
their workflow.

## Scope

The scope of this library is defined as:

1. Reading and writing any PNG image that conforms to the spec, with proper handling of images that do not.
2. Basic canvas drawing and compositing operations to create new or edit existing images.
3. Remain compatible with Ruby versions that are widely used.

I will close issues and pull requests that go beyond this scope. If you want to work on something,
but are not sure if it will be in scope, feel free to reach out to me!

## Reporting bugs

- First, see if somebody else has reported the problem already.
- Try to include as much relevant information as possible, so I can recreate the problem.
- If possible, include the PNG image that is causing the issue.
- If possible, include a code snippet that exposes the problem.

## Pull requests

Title and description:

- If you are not yet done, please include `[WIP]` in the title of your pull request.
- Explain why your changes are relevant in the description of your pull request.
- If your changes improve performance, include benchmark methodology and results in the PR.
  See BENCHMARKING.md for more information.

Code:

- Don't break backwards compatibility.
- Follow code conventions. They are not defined, so look at the code around you.
- Add Yardoc comments as documentation.

Specs:

- Always include specs that test your changes, to prevent me from breaking your code later.
- If your specs use PNG files, try to keep them as small as possible to keep the test suite snappy.
- Make sure that the specs are passing for all Rubies on [Travis CI](https://travis-ci.org/wvanbergen/chunky_png/).

Misc:

- Add an entry to CHANGELOG.md.
- Do not change `ChunkyPNG::VERSION`
