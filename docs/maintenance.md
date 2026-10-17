# Profile maintenance

This repository contains the public profile README for [Heavenfiend](https://github.com/Heavenfiend).

## Files and dependencies

- `README.md`: short introduction, development projects, and a university index.
- `assets/header.svg`: original static banner. Its dark background is part of the image; README page colors follow GitHub's theme.
- `assets/stack.svg`: static Skill Icons snapshot, fetched 2026-10-18. No runtime request to Skill Icons is needed.
- Typing line: [Readme Typing SVG](https://github.com/DenverCoder1/readme-typing-svg), hosted at `readme-typing-svg.demolab.com`. The light/dark variants use `picture`; text alternatives and the static banner preserve the introduction when the service is unavailable. GitHub caches external images, so updates may take time.
- Icons: [Skill Icons](https://github.com/tandpfun/skill-icons), MIT. See [third-party license](../LICENSES/skill-icons-MIT.txt).
- No workflows, secrets, packages, or scheduled jobs are needed.

## Verified public inventory (2026-10-18)

The authenticated repository list contained 25 owned repositories, 18 public. Private repositories are deliberately omitted from this file and the profile.

| Repository | Public evidence | Classification |
| --- | --- | --- |
| Predicta | Kotlin Android app; Compose, Room, Retrofit and Koin in app/build.gradle.kts | Android development |
| vk_homework1 | Android manifest, Kotlin MainActivity and Compose theme | Android practice; course/year unconfirmed |
| vkhomework2 | Compose GIF list, Retrofit API and repository | Android practice; course/year unconfirmed |
| Cryptography | Repository description and Lab1/README.md identify cryptography labs, Feistel, DES and DEAL | University / cryptography; year unconfirmed |
| computer-graphics | README explicitly identifies labs; C++ / Vulkan sources | University / computer graphics; year unconfirmed |
| DBMS | README identifies a SQL DBMS in C++; client/server and parser sources | C++ development; exact course/year unconfirmed |
| OOP, OOP2, OOP3, OOP4, OOP5, OOP6, OOP7 | Repository names and GitHub primary language C++; OOP has lab material | C++ / OOP collection; exact course/year unconfirmed |
| OS_2025, OS2, OS3 | C sources and lab reports; OS_2025 README describes pipes | C / systems labs; formal course/year unconfirmed |
| FIIT_FA | readme.md labels laboratory work; trees and big integer arithmetic in C# | Algorithms labs; formal course/year unconfirmed |
| FIIT_SP | README labels laboratory work; C++ allocator/container tree | C++ labs; formal course/year unconfirmed |

All 18 public repositories had empty Topics at inspection. Null repository descriptions are not treated as evidence. The language reported by GitHub for DBMS was null; C++ is confirmed by its README and sources. Do not infer a degree year from dates, group numbers, or repository suffixes. Linked repositories may contain starter or collaborative work; links do not assert sole authorship.

## Organization strategy

1. Keep the Profile README as the navigation hub. Use normal text/list links and a small two-column table; avoid fixed-width project grids.
2. Use native `details` sections for longer collections. Add **1st Year / 2nd Year / 3rd Year** only after the owner confirms the mapping; keep unknown items in an unassigned collection.
3. Later, add a small consistent vocabulary of Topics to confirmed repositories: `android`, `kotlin`, `jetpack-compose`, `university`, `coursework`, plus a verified subject and optional `year-1`, `year-2`, `year-3`. Topics are labels for search, not nested folders. No topics were changed for this MVP.
4. Recommend pinning Predicta, Cryptography, computer-graphics and DBMS. GitHub allows six repositories/gists combined; pins are a showcase, not a category tree. Pins were not changed.
5. GitHub Lists group starred repositories on the Stars tab and are public preview. They do not create folders or categories on the Repositories tab, so they are an optional reading list rather than the main portfolio index.
6. A separate catalog repository is unnecessary at this size. If the index grows, first add `docs/projects.md` here; consider a catalog only when it needs its own lifecycle.

## Possible next iterations (not implemented)

| Improvement | Benefit | Limits / maintenance |
| --- | --- | --- |
| Confirmed year groups + selected Topics | Easier navigation and search | Low; requires an accurate course mapping |
| Custom static project cards | Clearer project identity and screenshots | Low to medium; update images and alt text when projects change |
| Contribution Snake | Small animated accent | Medium; scheduled Action and maintained third-party action, preferably pinned by commit |
| One GitHub Stats card OR Activity Graph | At-a-glance public activity | Medium; external service reliability, caching and imperfect interpretation of activity |
| Automatic public project catalog | Reduces manual catalog work as the account grows | Medium to high; API pagination, visibility filtering, reviewed metadata and least-privilege workflow |

Animated banners and extra icon sets can be added later if they communicate something useful; they add motion or visual density without improving repository navigation.

## References

- [Profile README requirements](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme)
- [Theme-aware images and tables](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github)
- [Collapsed sections](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-collapsed-sections)
- [Repository Topics](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/classifying-your-repository-with-topics)
- [Profile pins](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/pinning-items-to-your-profile)
- [Starred repository Lists](https://docs.github.com/en/get-started/exploring-projects-on-github/saving-repositories-with-stars)
- [GitHub Actions](https://docs.github.com/en/actions/get-started/understand-github-actions)

## Safe updates

Check every added repository is public before linking it. Change only this repository unless the owner requests broader edits. After editing, inspect the actual GitHub profile at desktop and narrow widths, expand each section, check images and links, and review both themes.
