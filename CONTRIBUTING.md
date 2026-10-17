# Contributing to Niko

Thanks for helping. Niko apps are for people who can't read, older people and disabled people, so every change is judged by one question: does it make the app easier for them?

## Ways to help

- **Testing.** Use an app with someone who would actually rely on it. Watch where they get stuck and open an issue describing what happened. You don't need to write code.
- **Accessibility reports.** If something doesn't work with TalkBack, large fonts, Switch Access or another tool, use the accessibility issue form.
- **Translations.** Each app speaks and shows text in the phone's language. Translation setup is coming; until then, open an issue for the language you can help with.
- **Code.** The apps are in private development for now. Code contributions open once the source is published.
- **App ideas.** Use the app idea form. Ideas that come from someone who has the problem are the most useful.

## Before you write code

1. Open or comment on an issue first so we can agree on the approach.
2. Read the principles in the [organisation profile](https://github.com/NikoApps). In short: one job per app, no ads or tracking, works offline, usable without reading, nothing moves, and it keeps working after Android updates.
3. Don't add dependencies that need Google Play Services, Firebase, analytics or network access. F-Droid won't accept them and neither will we.

## Pull requests

- Keep each pull request small and focused on one change.
- Use [Conventional Commits](https://www.conventionalcommits.org/) for commit messages, for example `feat(clock): add quiet hours`.
- Test with TalkBack on and with the largest font size. Mention it in the pull request.
- Update the README or store description if the change affects users.
- Screenshots or a short screen recording help a lot for UI changes.

## Accessibility bar

Every change must:

- Work with TalkBack, with every control labelled.
- Work at the largest system font size without text being cut off.
- Keep touch targets at least 56dp.
- Keep text contrast at WCAG AAA (7:1).
- Not depend on reading to understand what something does.

## Licence

By contributing, you agree that your contributions are licensed under the GNU General Public License v3.0, the same licence as the project.

## Conduct

Everyone taking part follows the [Code of Conduct](CODE_OF_CONDUCT.md).
