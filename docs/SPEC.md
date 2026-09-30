# Proiproi: Product Specification

This is the public summary of Proiproi's MVP. It describes what the product does and why. Implementation details are not included.

---

## 1. Overview

Proiproi is a lightweight platform for anyone with a project and an incomplete team. Hobbyists looking for a co-creator, independent creatives recruiting collaborators, and professionals assembling specialist teams all share the same need: a simple, low-friction way to post what they are building and connect with people who want to help make it real.

The product is intentionally broad in who it serves and intentionally narrow in what it does. Post a project, define your roles, find your people, locally or globally.

| Problem | Solution |
| --- | --- |
| There is no dedicated, lightweight tool for connecting people around a shared project. Freelance platforms are transactional and payment-first. Social media is noisy and ephemeral. Nothing puts the project itself at the centre. | A project-first discovery platform where the work is the primary unit. Users post what they want to make, what roles they need filled, and where they are. Others discover projects on a map or through search and apply to join. |

## 2. Who it is for

Proiproi serves three equally weighted groups. The product, onboarding copy and skill taxonomy work for all three without favouring any one.

**Hobbyists and side-project makers.** People with an idea they want to pursue outside of work. No professional credentials required.

**Independent creatives.** Freelancers and independent practitioners in music, film, visual art, writing, design or photography, assembling a collaborator team for a specific project.

**Professionals and specialists.** Domain experts who want to lend their skills to a project they believe in, or who need to recruit specialist collaborators for their own work outside their primary employer.

## 3. Core principles

- **Accessible.** No portfolio required and no credential checks. A hobbyist and a professional use the same interface.
- **Lightweight.** Under five minutes from idea to posted project. Every step is optional except a title, a description and at least one role.
- **Project-first.** The project is the primary object, not the person. Profiles support projects; they do not replace them.
- **Local and global.** The creator chooses the scope for each project. Both are first-class experiences.
- **Useful for everyone.** The taxonomy, filters and discovery tools surface relevant results at every skill level.

## 4. Features

### 4.1 Accounts and profiles

| Feature | Description |
| --- | --- |
| Sign-in | Google and Apple sign-in |
| Profile | Display name, short bio (280 characters), skills (chosen from the taxonomy plus free-form tags), location (a city, or global), and an avatar |
| Featured work | Up to three projects and three communities can be featured on a profile. Each shows a cover image (or a category icon), name, category and the person's role |
| Stats | Projects created, collaborations joined, and communities, shown as large numbers |
| Visibility | Profiles are visible to any signed-in user |
| Editing | Every profile field can be edited at any time |

### 4.2 Onboarding

A four-step flow after first sign-in, with a progress bar along the top:

1. **Welcome.** The value proposition with three tiles: post a project, discover nearby, apply and connect.
2. **Profile basics.** Display name (required), bio and avatar (optional).
3. **Skills and location.** Choose skills from the taxonomy, or add your own. Set a city or go global.
4. **You're all set.** Shortcuts to post a first project, explore projects or discover communities.

Steps 2 and 3 can be skipped.

### 4.3 Creating a project

A five-step flow: Basics, Category and visibility, Location and scope, Roles, Review.

| Step | What happens |
| --- | --- |
| Basics | Title and description (500 characters) are required. A cover image and up to three feature media items are optional |
| Category and visibility | Choose a category. Choose whether the project is public or visible only to a community, and which community |
| Location and scope | Choose local or global. Local projects need a map pin, set by address search, dragging the pin, or using your current location. Global projects may optionally have a pin |
| Roles | Add at least one role (see 4.4). Choose whether to allow expressions of interest and whether people may apply to multiple roles |
| Review | A read-only summary with edit links for each section. Publish the project or save it as a draft |

**Feature media.** Up to three items per project: images, files (PDF or document) and YouTube or Vimeo links. On mobile they appear as a swipeable slideshow labelled "From the creator".

### 4.4 Roles and applications

**Role cards.** Each project has up to six roles. A role has a title (required), a description (150 characters), skill tags, an experience level (Learning, Any, Intermediate or Professional) and the number of spots available.

**Application questions.** Creators can add up to five questions per role. Question types are free text, single choice and multi-select, and each can be required or optional. If a role has no questions, applicants write a single message (300 characters). When questions are present, an optional "Anything else to add?" field is always included.

**Expressing interest.** For people who do not see their exact role. It is on by default and creators can turn it off per project. The form is a short free-text message (300 characters). Creators see expressions of interest separately from role applications everywhere.

**Application status.** Every application is Pending, Accepted or Declined. Applicants see live status in their Inbox.

**Reviewing applications.** Creators open the Applications dashboard from their project, choose a role, see everyone who applied, and open an application to read the full answers. They can accept or decline with an optional note.

### 4.5 Invites

Creators and administrators can invite people directly. Write the message first, choose the role, then search for people by skill tag or name. Invited people accept or decline from their Inbox.

### 4.6 Project members and permissions

| Role | Permissions |
| --- | --- |
| Creator | Full control: edit everything, manage roles, create and edit tasks, accept or decline applications, send invites, assign member roles, archive or close the project |
| Administrator | Edit the description, roles, feature media and tasks. Can view applications and send invites. Cannot accept or decline applications or change anyone's role |
| Member | Read-only access to the project. Can mark their own assigned tasks complete |

People accepted through an expression of interest join as members with the label "General contributor".

### 4.7 Tasks

Project managers create tasks with a title, an optional description, an optional due date and one or more assignees (any project member, or unassigned). Each project has a task list that can be filtered by open, complete or all, and searched by title. Overdue tasks are highlighted and completed tasks are dimmed. Members can see every task and mark their own complete.

A cross-project All Tasks screen, reached from Home, shows upcoming tasks across every project, with filters for status, "assigned to me" and project.

### 4.8 Project files

Each project has shared file storage for its team. Any member can upload. Each file is visible either to everyone on the project or to managers only, and managers can change that afterwards. Files can be pinned, and members are notified when a file is added.

### 4.9 Discovery

**Map view.** Projects appear as pins. Tapping a pin opens a project preview. The map can go full screen, and "Search this area" re-runs the search after you pan.

**Scope.** Two options: Local and All. Local shows local-scoped projects within a radius, drawn as a circle on the map. All adds global projects that have a pin.

**Below the map.** A compact list of the nearest projects, each with its name, category, open roles and distance.

**List view.** Every project, local and global, sorted by recency.

**Filters.** Scope, category, radius (10 to 100 km, for Local scope) and experience level.

**Search.** Full-text search across project titles, descriptions and role titles. Results can be switched between Projects, Roles, Communities and People, with the matching role highlighted.

### 4.10 Communities

Communities bring people together around a craft or interest.

| Feature | Description |
| --- | --- |
| Create | Name and description are required. A cover image and category are optional |
| Join modes | Open (join instantly), Application (write a message and wait for approval) or Invite-only. The mode can be changed at any time |
| Roles | Creator (full control), Administrator (manage members, pin projects) and Member |
| Community page | Cover, description, pinned project, community projects, and a members preview. Creators also see a join-request count and a Review join requests button |
| Projects | Projects can be made visible to a single community only |
| Deleting | The creator can delete a community. Community-only projects are deleted with it. Public projects are unaffected |

### 4.11 Home and Inbox

**Home** is a hub with shortcuts to Explore, Inbox, Communities and Profile, a prominent Post a project button, your three most recent unread notifications, and summaries of your projects, communities and upcoming tasks.

**Inbox** has four tabs:

| Tab | Contents |
| --- | --- |
| Received | Incoming applications, expressions of interest and community join requests |
| Sent | Your own applications and expressions of interest, with status badges |
| Invites | Project and community invites, with Accept and Decline |
| Activity | System alerts such as accepted applications, approved join requests and inactivity warnings, grouped by date |

### 4.12 Notifications

Push notifications for new applications, accepted or declined applications, expressions of interest, invites, new project files and inactivity warnings. Each type can be turned on or off in Settings.

### 4.13 Project lifecycle

Inactive projects are archived rather than left cluttering discovery:

| Day | What happens |
| --- | --- |
| 23 | Push notification warning the creator |
| 30 | Project is archived |
| 58 | Final deletion warning |
| 60 | Project is permanently deleted |

Creators can restore an archived project within 30 days.

### 4.14 Safety

Proiproi is for collaboration, not hiring. Content that is spam, paid work disguised as collaboration, or harassment is removed. People can report projects, communities and profiles, and block other users.

## 5. Skill taxonomy

A starter set of tags. People can also add free-form tags.

| Domain | Tags |
| --- | --- |
| Music | Songwriting, Mixing, Mastering, Music Production, Vocals, Guitar, Bass, Drums, Keys, Violin, Brass, Sound Design, Composition, Lyrics |
| Film & Video | Cinematography, Directing, Screenwriting, Editing, Colour Grading, Sound Design, Production Design, Acting, Producing, VFX, Motion Graphics |
| Visual Art | Illustration, Painting, Concept Art, Pixel Art, 3D Modelling, Sculpture, Printmaking, Comics, Storyboarding, Lettering, Inking |
| Design | UI Design, UX Design, Graphic Design, Brand Identity, Typography, Motion Design, Product Design, Industrial Design |
| Photography | Portrait, Landscape, Documentary, Product, Street, Drone, Photo Editing, Retouching |
| Writing | Copywriting, Fiction, Non-fiction, Screenwriting, Poetry, Editing, Proofreading, Technical Writing, Journalism |
| Software & Apps | iOS Development, Android Development, Web Development, Backend, Frontend, React Native, Firebase, UI Engineering, QA, Data Engineering |
| Games | Game Design, Unity, Unreal, Narrative Design, Level Design, Game Art, Game Audio, Playtesting |
| Podcast | Hosting, Audio Editing, Research, Writing, Production, Sound Design |
| Research | Literature Review, Data Analysis, Interviewing, Survey Design, Writing, Visualisation |

## 6. Navigation

**Mobile:** a bottom bar with Home, Explore, a raised amber Post button, Inbox and Profile.

**Web:** a sidebar with Home, Explore, Communities, Inbox, Profile, Settings, Support and a Post project button. The web app also has a landing page and a support page.

## 7. Design

Clean and minimal, with warmth. The goal is LinkedIn-level credibility with a collaborative feel: warm off-whites in light mode, warm near-blacks in dark mode, and a single amber accent (#E8913A) across both. The typeface is Plus Jakarta Sans. Dark mode follows the device setting automatically.

## 8. Success metrics

Targets for the first eight weeks after launch:

| Metric | Definition | Target |
| --- | --- | --- |
| Activation | Share of sign-ups who post or apply within 7 days | 40% or more |
| Project creation | Projects posted per week | 20 or more |
| Application rate | Applications per open project | 2 or more |
| Match rate | Share of projects with at least one role filled | 30% or more |
| Retention | Share of month-one users who return in month two | 25% or more |

Tracked without a target: how many projects receive an expression of interest, and how often a filled role goes to someone whose skill domain differs from the project's category.

## 9. Out of scope for v1

Business accounts, agency profiles, paid job boards, client and contractor hiring, in-app messaging, portfolio links, endorsements and verified credentials, direct video upload, budgets and timelines, saved searches and recommendations. See the [roadmap](../ROADMAP.md) for what is planned next.
