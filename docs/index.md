# Ktisis Documentation Hub
Welcome to the new home for Ktisis' documentation, guides, and more! This site is an ongoing work in progress that will evolve with our tool and contributions from users like you.

## About Ktisis
[Ktisis](https://github.com/sleepybnuuy/ktisis-testing) is a robust posing tool that enhances the capabilities of FFXIV's GPose mode. It follows in the footsteps of [CMTool](https://github.com/imchillin/CMTool) and [Anamnesis](https://github.com/imchillin/Anamnesis) to allow users to pose characters with control over individual bones, while also offering a full suite of controls over other aspects of photo or video scene composition.

???+ info "Standard features include:"

    - Manipulate poses using any bones on a character's skeleton
    - Customize their appearances, animations, and expressions
    - Save and load `.chara` and `.pose` files compatible with other posing tools

??? info "Advanced controls including, but not limited to:"

    - Add and pose over 40 actors at once (compatible with other plugins and MCDF data!)
    - Spawn as many light sources as you need, with settings beyond vanilla limits
    - Undo, redo, flip poses, or load vanilla face expressions with ease
    - More easily position arms, legs, and tails using Inverse Kimenatics in and out of posing
    - Weather, time of day, and broader environment editing

### Update History
- 12/19/25: [v0.3.15](https://github.com/ktisis-tools/Ktisis/releases/tag/v0.3.15) - FFXIV 7.4 update support
- 12/7/25: [v0.3.14](https://github.com/ktisis-tools/Ktisis/releases/tag/v0.3.14) - MCDF/IPC updates, more bone-drift fixes, UI tweaks
- 11/26/25: [v0.3.13](https://github.com/ktisis-tools/Ktisis/releases/tag/v0.3.13) - pose flipping, bone offsets, expression loading, scrollwheel input, & more

## About the Docs
Changes to this wiki are accepted via [pull request](https://github.com/sleepybnuuy/ktisis-docs/pulls). Files are written in markdown (the same text language used by Discord!), so you don't have to be a programmer to make any additions. We recommend [forking this repository](https://github.com/sleepybnuuy/ktisis-docs/fork), making your changes on a new branch using [GitHub's web editor](https://github.dev/github/dev) or [Github desktop](https://github.com/apps/desktop) with a text editor of your choice, then submitting the change to this repo for review.

Known gaps in info or pages that need writing/improvement will be listed in the **TODO** section below, but feel free to create any new content you want, provided it's not duplicating existing work or adding ambiguity, clutter, or incorrect information. We'll do our best to help keep everything straight through the review process.

You can reach us for further discussion in the #ktisis-docs channel of the official Discord.

### TODO

Rough draft sitemap:

```
Home
FAQ

Posing:
    Overlay Controls (bones, presets, offsets, entity nodes)
    Pose Mode (unique capabilities - flip pose, apply/stash, reference poses, pose expressions - plus I/O)
    IK Usage

Actors:
    Actor Management
    Animation
    Gaze Control
    IPC Support (penumbra, glamourer, c+, MCDF)

Scene:
    Lighting
    Camera Controls
    *Secret Feature #1
    *Secret Feature #2

Windows:
    Workspace
    Actor Editor
    Environment Editor
    Camera Editor
    Pose View
    Configuration

Guides:
    Migrating to v0.3
    GPosing Tips
    Lighting Crash Course
    Gizmo & Transform Usage
    Community Resources (links to additional guides, utility spreadsheets)
    Tools (links to other plugins, reshade/gposingway?, useful simpletweaks etc)

Known Issues
Updates (plugin & wiki changelogs)
About (readme, socials links, docs contributors)
```

### Changelog
- 1/14/26: first draft
