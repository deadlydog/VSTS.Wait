# Wait Azure DevOps Extension

This [Azure DevOps (i.e. TFS) extension][ExtensionInAzureDevOpsMarketplaceUrl] provides a task that can be used to pause the Build or Release pipeline for the specified amount of time.

**Note:** This extension currently only supports *Windows* agents, but there are plans to also support Linux and Mac agents in the future.

If you find this extension useful, please [rate and review it][ExtensionRatingAndReviewInAzureDevOpsMarketplaceUrl].

Current build status: [![Build Status](https://dev.azure.com/deadlydog/OpenSource/_apis/build/status/AzureDevOps.Wait?branchName=master)](https://dev.azure.com/deadlydog/OpenSource/_build/latest?definitionId=21&branchName=master)
[![Deployment Status](https://vsrm.dev.azure.com/deadlydog/_apis/public/Release/badge/baf297a4-1582-49bd-b9ca-6d38492faafa/3/3)](https://dev.azure.com/deadlydog/OpenSource/_release?definitionId=3)

## Usage

Simply specify the number of milliseconds, seconds, or minutes to wait for, and the process will pause for that amount of time before continuing.

## Screenshots

Task that waits for 5 seconds:

![Task][TaskImage]

Output of task that waits for 2 minutes:

![OutputImage]

## Issues

If you find a problem with this extension, or would like additional functionality added to it, [create a new GitHub Issue][ExtensionGitHubRepositoryIssuesUrl] with your feedback.

You can also [view the change log here][ExtensionChangeLogUrl].

## Donate

Buy me a poutine for providing this extension open source and for free :)

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CZP8CU53RJ29W)

<!-- Links -->
[TaskImage]: src/Images/Task.png
[OutputImage]: src/Images/Output.png
[ExtensionInAzureDevOpsMarketplaceUrl]: https://marketplace.visualstudio.com/items?itemName=deadlydog.WaitBuildAndReleaseTask
[ExtensionRatingAndReviewInAzureDevOpsMarketplaceUrl]: https://marketplace.visualstudio.com/items?itemName=deadlydog.WaitBuildAndReleaseTask#review-details
[ExtensionGitHubRepositoryIssuesUrl]: https://github.com/deadlydog/AzureDevOps.Wait/issues
[ExtensionChangeLogUrl]: https://github.com/deadlydog/AzureDevOps.Wait/blob/master/docs/ChangeLog.md