# Rails reference installs

We’re in the process of upgrading to a current version of
[Ruby on Rails][rails]. To help with the process, we’ve generated base
installations for multiple versions and provided diffs between each major
version.

Like Rails itself, this code is [provided under the MIT license](./LICENSE).

  [rails]: https://rubyonrails.org/
  [rails new]: https://guides.rubyonrails.org/getting_started.html#creating-the-blog-application "Rails Guide: ‘Creating the blog application’"

## How to use

1. Make sure the [`versions`](./versions) file has all the Rails versions
  you're interested in (currently 4.2 through 7.0).
2. Run `./install-versions`, which runs [the `rails new` command][rails new]
  for each version.
3. Run `./diff-versions`, which iterates through each version, summarizing the
  from the previous version.
