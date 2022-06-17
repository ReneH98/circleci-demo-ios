# Circle-Ci

[![CircleCI](https://circleci.com/gh/CircleCI-Public/circleci-demo-ios/tree/master.svg?style=svg)](https://circleci.com/gh/CircleCI-Public/circleci-demo-ios/tree/master)

## Setup

1. `bundle install`
1. Add your team data to `fastlane/Appfile`
1. `bundle exec fastlane scan` to build the app and run tests
1. `bundle exec fastlane match init` to set up code signing via Fastlane
   Match
1. Push the changes
1. Create a CircleCI project for the repository
1. Edit the `.circleci/config.yml` file as needed
1. Done

## Initial proposal

Because we both work in small start-ups, we decided to dive deeper into the topic of reliable software releases, as this will be a major topic coming up very soon in our work life. Even though we work in different companies, we both develop apps and therefore our release process should be somehow comparable.

Based on the literature Continuous Delivery - Reliable Software Releases Through Build, Test and Deployment Automation we want to dive deeper into the topic. Especially the chapters Continuous Integration & Continuous Delivery will be used in an attempt to deploy a small application from the dev commit to production release.

For instance using a small iOS application that can be shipped automatically by the continuous delivery process. For that matter we also want to use github for the CI part.

In the Automation process we obviously want to include proper unit testing!

Also, we thought about using CircleCI for the CI/CD, because it offers a huge amount of features and is used by 1 Million developers already.