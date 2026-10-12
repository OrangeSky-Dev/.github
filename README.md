# OrangeSky Dev · organization profile

This repository maintains the public GitHub profile for
[OrangeSky Dev](https://github.com/OrangeSky-Dev).

## Contents

| File | Purpose |
| --- | --- |
| [profile/README.md](profile/README.md) | English profile displayed on the organization overview |
| [profile/assets/orange-sky.svg](profile/assets/orange-sky.svg) | Light-mode (dawn) SVG banner with accessible title and description |
| [profile/assets/orange-sky-dark.svg](profile/assets/orange-sky-dark.svg) | Dark-mode (dusk) SVG banner with accessible title and description |
| [brand/orangesky-avatar.jpg](brand/orangesky-avatar.jpg) | 1024 × 1024 avatar for the organization and its teams |
| [brand/orangesky-avatar.svg](brand/orangesky-avatar.svg) | Vector source of the avatar |

Banner text is converted to outlines (Sora and JetBrains Mono, both under the
SIL Open Font License) so it renders the same on every platform. To change the
wording, set the new text in those fonts and outline it again in both banners;
the path data is not meant to be edited by hand.

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
