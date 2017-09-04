# **PublishWorkflow**

### Description:
**Ever wanted to revert a workflow to a previous version?**

ServiceNow is a highly flexible application, allowing you to build incremental versions of a workflow. But there are times when you want the facility to revert to a previous version of a workflow. Since there is no such support out of the box, this utility will provide you an option to revert to different versions of the same workflow.

### Installation:
- Install the updateset found in **dist** folder.
- Installing the updateset will create a new UI action on workflow version table and a new script include, containing the scripts for the UI action functionality.

### Usage
- This adds a UI action called 'Publish Workflow' on workflow version table.
- This UI action will be visible only if the current workflow has more than one version and if the current version is not the published workflow version.
- Open an existing workflow version entry (wf_workflow_version) that you want to revert and click the **'Publish Workflow'** button. 
