# Turbo Ethereum Jenkins configuration

## HowTo
This configuration does not contain the secret keys and credentials needed. If you want to use it you should have the credentials for the `eth-jenkins-bot` github account.

Use the [ethereum docker jenkins's image fork](https://github.com/arkpar/docker) and then point to this repository as the jenkins configuration directory.

## Things left TODO

- Windows and MacosX slaves and builds
- Use git hooks instead of polling the repos. For testing purposes we still poll every minute. That's an overkill and need to be changed.
