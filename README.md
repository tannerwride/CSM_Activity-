# CSM_Activity

In this activity, we will walk through the process of identifying CircleCI features in a `config.yml` file and look for areas of optimization. 

## Prereqs 

- Permission to view customer config files and builds
- Completion of the CSM training in CircleUP titled "Filler"

## Viewing Customer Configuration Files 

There are several ways to view customer config files. 

- On the Dashboard, through the "three dots"

<img src="images/configfrompipeline.png">

- While viewing a workflow

<img src="images/configfromworkflow.png">

- While viewing a job

<img src="images/configfromjob.png">

- From the Projects page

<img src="images/configfromprojects.png">

- From the Insights page, when viewing a Workflow
          
<img src="images/configfrominsights.png">

The ability to view config from several locations makes jumping to viewing config easy, depending on what you may be doing. If you are troubleshooting a specific workflow, you can switch to the config quickly. If you are working on optimization by viewing insights, you can easily view the associated configuration file, etc.

### Viewing Older Configuration Files

When viewing config, CircleCI will also alert you if the config file you are viewing is out of date, as seen below. 

<img src="images/olderconfig.png">

## Customer Examples

Let's look at a few simple example configs and where we might suggest optimizing the config.

### Example 1

For this first example we will practice identifying what CircleCI features are being used in the build. Navigate to this [customer build](https://app.circleci.com/pipelines/github/ethereum/remix-project/6479/workflows/6951972b-3edf-47ee-9345-45dce4d2f9a6). 

Here we are viewing a completed workflow. This was a successful build that completed in 21m47s. 

<img src="images/buildallsuccess.png">

**What can we identify from this workflow page?** 

Is this customer running concurrent jobs? 

- [ ] Yes
- [ ] No 

**Review the Config**

Let's hop into the config. Remember from above how to view a config from the workflow. 

Is this configuration file up to date? 

- [ ] Yes
- [ ] No

