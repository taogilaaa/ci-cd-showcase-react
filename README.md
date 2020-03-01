# ci-cd-showcase-react

https://master-branch-ci-cd-showcase-react-taogilaaa.surge.sh/

A repository containing implementation of serverless technology + immutable deployments + continuous integration + continuous deployment for frontend (react), the goal is to showcase the benefits of these workflow

## Prerequisites

This project requires

- [nodejs](https://nodejs.org/en/)
- [yarn](https://yarnpkg.com/en/docs/install)

## Getting Started

### Installation

Use the package manager [yarn](https://yarnpkg.com/en/docs/install) to install dependencies.

```bash
yarn
```

### Example

Examples can be found on this project's [pull request](https://github.com/taogilaaa/ci-cd-showcase-react/pulls?utf8=%E2%9C%93&q=is%3Apr)

* [Change background color](https://github.com/taogilaaa/ci-cd-showcase-react/pull/2)

### Deployment

* Create a feature branch, and push the commits to this repo, the CI runner will run and detect changes, and deploy the artifacts to [surge.sh][surge]

## Test it yourself

### Using this Repository

1. Create a new branch and push the commits here
2. [Optional] Create a new pull request!

### Using a Fork

1. Fork this repository
2. Create github [access token][github token] to allow [travis ci][travis] to access repo and write to discussions
  ![access token](./assets/CI_Token_1.png)
  ![access token](./assets/CI_Token_2.png)
3. Register and get your [surge.sh][surge] secret key (on CLI, run `surge token` must be logged in)
4. Setup your repository settings on travis ci https://travis-ci.com/USER_NAME/REPO_NAME/settings and add `GITHUB_API_TOKEN`, `SURGE_LOGIN` (email) and `SURGE_TOKEN`
  ![travis env](./assets/Travis_Env.png)
5. Make a commit and push it !

[travis]: https://travis-ci.com/
[surge]: https://surge.sh/
[github token]: https://github.com/settings/tokens


This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
