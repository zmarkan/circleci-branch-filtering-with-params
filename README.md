# Just an experiment

workflow:

- job A that runs all the time
- "deployment" job B that runs on select branches
- job B that uses branch id to do stuff (ie select environment to deploy to)