# The New Xposed Module Repo

### Module Submission

https://modules.lsposed.org/submission

### Repo Requirment

A valid repo should match the following requirements:

1. Repo name must be the package name of the Xposed module
1. Must have a nonempty repo description as the name of the Xposed module
1. Must have at least one valid release
1. A valid release must have at least one asset that has an apk file, and its tag name must be `VersionCode-VersionName`


### Best Practice to release

Create a release and upload a valid apk file with an arbitrary tag name. The bot will help you to correct the tag name.

**Note that** editing only the release asset won't trigger the bot. So DO NOT upload your apk separately without modifying the release's content.
