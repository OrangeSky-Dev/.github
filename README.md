# OrangeSky Dev · organization profile

This repository maintains the public GitHub profile for
[OrangeSky Dev](https://github.com/OrangeSky-Dev).

## Contents

| File | Purpose |
| --- | --- |
| [profile/README.md](profile/README.md) | English profile displayed on the organization overview |
| [profile/assets/orange-sky.svg](profile/assets/orange-sky.svg) | Light-mode SVG banner with accessible text |
| [profile/assets/orange-sky-dark.svg](profile/assets/orange-sky-dark.svg) | Dark-mode SVG banner with accessible text |

GitHub displays `profile/README.md` from the default branch of this public
`.github` repository on the organization overview. The root README is for
maintaining this repository. See [GitHub's organization profile documentation](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile).

## Editing the profile

1. Keep the profile in English, with a concise organization introduction and clear
   paths to downloads, documentation, and contributions.
2. Check project descriptions against their current documentation. Link to
   releases and documentation rather than duplicating versions or installation instructions.
3. Use absolute GitHub URLs in the profile so links work from the organization
   overview as well as from this repository. Keep banner assets in this repository
   and update both color variants together.
4. Run `git diff --check`, inspect the rendered profile in light and dark modes
   at desktop and mobile widths, and check every changed destination before pushing.

Usque links currently point to `GeorgeXie2333/usque-app`, its current repository.
After a transfer to `OrangeSky-Dev/usque-app`, verify the new location and update
all project links in the profile together.

The profile displays the domain `orangesky.dev` as text. Add a website link or
public contact email when the destination is ready to receive visitors or mail.

Contribution and security links point to each project's own policies. This
repository does not currently define organization-wide default community files.
