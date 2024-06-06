# GitLab
GitLab is a DevOps tooling platform that uses git for src ctrl and CI/CD pipelines for building, testing and deploying.

## GitLab Architecture
1. GitLab Server: This is what manages everything. Streamlines and platforms the repos, workflows. Manages the pipelines but delegates what needs to be done to the Gitlab Runner. Doesnt run the steps but manages them.
2. GitLab Runners: Runs all the steps that needs to be done given by the server. 
   - does all the small tasks when the pipeline is ran. e.g uploading artifacts

### What it uses
YAML - data serialization language

### Why GitLab?
1. Modern tool with continuous updates being made - Jenkins losing market share
2. Simple, scalable
3. Docker first approach