# Security policy

This is the default security policy for every repository of
[AC-CREATION-AI](https://github.com/AC-CREATION-AI) that does not have its own `SECURITY.md`.
A repository's own policy takes precedence.

## Supported versions

All projects are experimental. Only the **latest commit of the default branch** and the **latest published
release** (if any) get fixes. Problems in upstream projects belong to their own maintainers; we do not report
to or on behalf of them.

## Reporting a vulnerability

**Do not open a public issue.**

Use GitHub's private vulnerability reporting: open the **Security** tab of the repository concerned and click
**Report a vulnerability**. If that is not available, open a public issue that says only "I need to report a
security problem privately" with no details, and a maintainer will set up a private channel.

Please include:

- the affected commit or release, and the component;
- how to reproduce it, using **synthetic files only**. Never attach game files, keys or firmware, even to show
  a parser bug: describe the structure or build a minimal crafted file;
- the impact you expect.

We aim to acknowledge reports within 7 days. This is a volunteer project, so there is no guaranteed fix time.
We credit reporters unless they ask us not to.

## In scope

- Memory-safety or parsing bugs that a crafted file can trigger.
- Anything that could leak user files, keys or saves outside the app's storage.
- Supply chain: CI workflows, release signing, bundled binaries, dependency pinning.
- Secrets committed to a repository or its history.

## Out of scope

- Bugs that need a modified device or root access the user already granted.
- Game glitches, crashes without a security impact, and performance problems: use the repository's bug
  report form.

## Legal and rights-holder requests

If you are a rights holder and believe something in one of our repositories infringes your rights, report it
privately through the same **Security** tab ("Report a vulnerability") with the exact file paths or URLs.
We review requests promptly and remove content that does not belong here. You can also use GitHub's DMCA
process. Our repositories contain and distribute no game, key or firmware.
