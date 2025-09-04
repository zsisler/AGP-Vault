---
Created: 2025-09-04
tags:
  - studysesh
---
###### [Study Session Topic - 2025-09-04](https://kclifeinsurance-my.sharepoint.com/:fl:/g/personal/terrannie_scott_kclife_com/EfURg34HFNNJsAn1SkZXXmQBgX4oNtCFDWxO4SlZxRg1iA?nav=cz0lMkZwZXJzb25hbCUyRnRlcnJhbm5pZV9zY290dF9rY2xpZmVfY29tJmQ9YiFJQ0Z3U3NSc2FVcTBxRHhWVEFIaWRnWDlpX0xxSFNKSHY1anhqRHlrSnh0dU5yMmdFQnVuUjc4bE9qRWVCX01WJmY9MDFVV09aUVhYVkNHQlg0QllVMk5FM0FDUFZKSkRGT1hURSZjPSUyRiZmbHVpZD0xJmE9VGVhbXMmcD0lNDBmbHVpZHglMkZsb29wLXBhZ2UtY29udGFpbmVy) - Release Process Overview
---
### Order of Operations
- [ ] Build KCLEngine (Earlier the better)
- [ ] Update KCLIllustrationDLL Reference w/ KCLEngine build
	- [ ] Build DLL in nuget for IKCLife & KCLIllustrationDLL
	- [ ] Update KCLEngine DLL references in iKCLife, legacy website
- [ ] Jenkins process (dev is built nightly)
	- [ ] KCLEngine Dev/Live Pipeline
	- [ ] KCLIllustrationDLL Dev/Live Pipeline
	- [ ] IKCLife Dev/Test/Live
	- [ ] Legacy Website Dev/Test/Live
- [ ] KCLIC build to prod in Azure Devops
- [ ] Mobile
	- [ ] Android within VS2022
	- [ ] Apple build within VS2022 distribute manually on Mac (ask Chad)

See: [[Release Procedure for Illustration System]] 
###### Notes:
release branch strategy: Jenkins Test env looks for "Release-" branch name

#### Q's:
- Can we build engine / DLL early in sprint instead of release?
- Can we get rid of iKCLife KCLIllustrationDLL dependency?
- Can we get some updates to naming conventions?
- Optimize KCLEngine nuget?