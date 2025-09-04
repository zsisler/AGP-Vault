---
Created: 2025-09-04
tags:
  - procedures
---
> KCL Engine builds first. 

- Update Master branch by merging in Develop branch from current release
- Create PR and title it "Merging develop into master for current release #.##"
- Get approvals for release from the AGP team and KD
- Merge KCLEngine https://github.com/kclife-it/KCLEngine dev to master
- Kick off Jenkins build KCLEngine Live (Get KD's approval; takes ~1hr+)

---

> KCLIllustration DLL builds second.

- Update KCL Engine Build Nuget Package # (1.0.###.0 taken from KCLEngine on Jenkins)
- Create PR and title it "Merging develop into master for release #"
- Get approvals for release from the AGP team
- Merge KCLIllustrationDLL https://github.com/kclife-it/KCLIllustrationDLL dev to master
- Kick off Jenkins build KCLIllustrationDLL live (Get KD's approval; takes ~5min)

---
> Final Updates.
>  
- Update KCLIllustrationWebsite (Legacy website) and iKCLife
  
###### See: [[Study Session - 2025-09-04]]

