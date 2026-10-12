# OrangeSky Dev · organization profile

This repository maintains the public GitHub profile for
[OrangeSky Dev](https://github.com/OrangeSky-Dev).

## Contents

| File | Purpose |
| --- | --- |
| [profile/README.md](profile/README.md) | English profile displayed on the organization overview |
| [profile/README.zh-CN.md](profile/README.zh-CN.md) | Simplified Chinese version linked from the profile |
| [profile/assets/orange-sky.svg](profile/assets/orange-sky.svg) | Self-contained SVG banner with accessible text |

GitHub displays `profile/README.md` from the default branch of this public
`.github` repository on the organization overview. The root README is for
maintaining this repository. See [GitHub's organization profile documentation](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile).

## Editing the profile

1. Keep the English and Simplified Chinese versions consistent.
2. Check project descriptions against their current documentation. Link to
   releases and documentation rather than duplicating versions or installation instructions.
3. Use absolute GitHub URLs in the profile so links work from the organization
   overview as well as from this repository. Keep banner assets in this repository.
4. Run `git diff --check`, inspect both rendered Markdown pages, and check every
   changed destination before pushing.

Usque links currently point to `GeorgeXie2333/usque-app`, its current repository.
After a transfer to `OrangeSky-Dev/usque-app`, verify the new location and update
both language versions together.

The profile displays the domain `orangesky.dev` as text. Add a website link or
public contact email when the destination is ready to receive visitors or mail.

Contribution and security links point to each project's own policies. This
repository does not currently define organization-wide default community files.
