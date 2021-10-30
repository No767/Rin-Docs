# Branches

There are 2 main branches: master and dev. Master is the branch that contains the stable code. This is meant later on for production use. Dev is where all of the code gets pushed and made. If you want the latest and greatest, check out the dev branch
  
If you are still confused by this, here's a table to help you.

| Branch | Purpose of Branch |
|  :--:  |    :--:           |
| Master | Stable Code only meant for production use |
| Dev | Unstable code that includes features being worked on. This is the branch to test certain stuff, and to add new code and features until it's deemed complete and/or stable. Please note that if you want to contribute, if it's not for a fix, please pr into the dev branch instead. This way I'm able to recieve the newest updates |

# Release Target

Currently, I (the project lead maintainer) don't have a place to host the bot. Though Rin has a docker image only accessible to me that has everything (including env vars and api keys), I am currently working on something in order to get this up and running for production use. Rin is fairly close to V1 Release. V0 is currently development/semi-stable releases of Rin, and V1 will be LTS and for production use