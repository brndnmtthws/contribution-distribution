# [This is the source code for this blog post](https://brndn.io/posts/the-10x-engineer-is-a-myth-its-more-like-100x/)

A quick analysis of the distribution of contributions from the top 100
contributors (limited by GitHub's API) from top GitHub repos.

See [100x-engineer.ipynb](./100x-engineer.ipynb) for details.

## Set it up

Install the necessary dependencies within a virtualenv using [Poetry](https://python-poetry.org/):

```console
poetry install
```

## GitHub API

If you wish to run the code, you'll need to [create a GitHub personal access
token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens)
and add it to your `.env` like this:

```console
echo GITHUB_ACCESS_TOKEN=github_pat_herpderp > .env
```

## Source Data

Big ups to the peeps over at <https://github.com/EvanLi/Github-Ranking> for
creating the source data.
