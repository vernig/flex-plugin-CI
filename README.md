# Automate Flex plugin publishing through GitHub Actions 

This repository is an example of how to use GitHub Actions to deploy a Twilio Flex plugin. You can have a look to [this file](  https://github.com/vernig/plugin-automation/blob/master/.github/workflows/main.yml) for an example configuration.

# Gotachas

Note that warning in any of the steps, will stop the process in GitHub Actions. This is different from what happen locally. The reason for that is that when `process.env.CI` is set to  `true` all warning are treated as error. You can see that in action in the branch `ci-error`. 
