
  ![on-push](../../actions/workflows/on-push.yaml/badge.svg)
  ![on-pull-request](../../actions/workflows/on-pull-request.yaml/badge.svg)
  ![on-schedule](../../actions/workflows/on-schedule.yaml/badge.svg)

  # TRAIL's Website

  Visit **[templerail.github.io/TRAIL-website](https://templerail.github.io/TRAIL-website)** 🚀

  ## Adding a Member

  To add a new lab member to the website, create a new `.md` file with the first and last name of the member. The naming convention should adhere to the following naming convention:

  `/_members/firstname-lastname.md`

  Fill in all relevant metadata at the top

| Field | Description | Subfields / Extensions / Notes |
|------|-------------|-------------------------|
| `name` | Full display name of the member. Used for headings and public-facing text. | |
| `image` | Relative path to the member’s profile image, typically used for website profile cards. | `.jpg`, `.png` |
| `role` | Role identifier used for sorting, filtering, or styling members. | `principal-investigator`, `phd`, `undergrad`, `postdoc` |
| `affiliation` | Institutional affiliation | Currently not being used as everyone is Temple affiliated |
| `aliases` | Alternative name spellings used for search, publications, or citation matching. | |
| `group` | Defines alumni or current member status | `current`, `alumni` |
| `links` | Collection of contact and external profile links associated with the member | `email`, `linkedin`, `home-page`, `twitter`, `orcid`, `github`, `youtube` |

Example:
  ```
  name: Philip Dames
  image: images/members/philip_dames.jpg
  role: principal-investigator
  # affiliation: Temple University
  aliases:
    - Philip Dames
    - Philip M. Dames
    - P Dames
    - PM Dames
  group: current
  links:
    email: pdames@temple.edu
    orcid: 0000-0002-7257-0075
    home-page: https://engineering.temple.edu/directory/philip-dames-tug85627
  ```

  Additional documentation on members can be found in the [official documentation](https://greene-lab.gitbook.io/lab-website-template-docs/basics/team-members)

  ## Adding a News Post

  To add a new news post, simply add a new `.md` file to the /_posts/ directory. The file should adhere to the following naming convention. This allows posts to be ordered chronologically.:

`/_posts/YYYY-MM-DD-title-of-your-post.md`

Below is a description of the metadata fields and uses
| Field | Description | Subfields / Extensions / Notes |
|------|-------------|-------------------------|
| `title` | Title of the news post | |
| `image` | Optional image related to news post | `.jpg`, `.png` |
| `author` | Author of the news post | |
| `tags` | Define the type of news post. Feel free to add new tags if the existing tags do not fit with the new post | `awards`, `promotion`, `paper-acceptance`, `etc.` |
| `last_modified_at` | Leave an empty string here to prevent "Last modified at <date>" from appearing on the post  | `""` |
Example:
```
title: NSF Career Award
image: images/blog/2022-08-18-nsf-career-award.jpg
author: Philip Dames
tags: 
    - awards
last_modified_at: ""
```

Additional documentation on news posts can be found in the [official documentation](https://greene-lab.gitbook.io/lab-website-template-docs/basics/blog-posts)

## Adding a New Project

To add a new project simply add a new `.md` file to the `_research-projects/` directory. The file should ahere to the following naming convention.

`/_research-projects/name-of-your-project.md`

Below is a description of the metadata fields and uses
| Field | Description | Subfields / Extensions / Notes |
|------|-------------|-------------------------|
| `title` | Title of the research project | |
| `image` | Optional image related to the project. This appears next to the description on the projects index page. | `.jpg`, `.png` |
| `author` | Short summary of the project. This appears as the description on the projects index page.  | |
| `funding` | Define names of funding sources and links to the funding page. | Each Entry should have a `name`. If applicable, the name should have a `url`. |
| `members` | Names of members currently working on this project. | Names of members should be in `firstname-lastname` format and should match member names exactly. |
| `tags` | Descriptors defining the type of project. | These tags must match the tags on the papers in order to work properly. Examples include: `distributed-tracking`, `dynamic-navigation`, `etc.` |

Example:
```
title: Distributed Tracking
image: images/projects/distributed-tracking.jpg
summary: The ability to track, predict, and reason about pedestrians and vehicles in dense urban environments.
funding:
  - name: NSF National Robotics Initiative
    url: https://www.nsf.gov/awardsearch/show-award/?AWD_ID=1830419
members: 
  - nathan-wolf-sonkin
  - alkesh-srivastava
tags:
  - distributed tracking
```

This version of research projects is a custom section and does not have official lab website template style documentation. In general the style follows the existing `members` and `news posts` sections. For any other questions, please ask [Nathan Wolf-Sonkin](https://templerail.github.io/TRAIL-website/members/nathan-wolf-sonkin.html).

## Images and Data

In general, all images should be stored in the `/images/` directory. Member images are stored in `/images/members/`, news images are stored in `/images/news`, and so on. 

Data related to a news post or research project such as locally stored research papers should be stored in their respective directories.

Example:

`_posts/2020-07-25-trail-will-present-1-paper-at-iros-2020.md` references an internally stored research paper. This paper is stored at `/news/papers/ChenDamesIROS2020.pdf` because it is a paper related to the news post.

# Official Documentation
For other any other questions, please check out the official [*Lab Website Template*](https://greene-lab.gitbook.io/lab-website-template-docs) documentation or [*GitHub repository*](https://greene-lab.gitbook.io/lab-website-template-docs).
