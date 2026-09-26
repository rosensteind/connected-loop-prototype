# This site is frozen. Do not push to it.

This repository serves **the link Farnaz is presenting from**:

    https://rosensteind.github.io/connected-loop-prototype/

It is a snapshot, deliberately. Development happens in the private
`connected-loop` repository and is published elsewhere, so that work in
progress can never appear in the middle of somebody's presentation.

## The rule

Nothing is pushed here unless David asks for it by name, and never on the
morning of a meeting. A broken demo in a room full of people is not a bug
that can be fixed afterwards — the meeting is the deliverable.

## Where development goes instead

The live application, including sign-in and the connected build, is deployed
separately and will live at **theconnectedloop.co.uk**. That is the one that
changes. This one does not.

## What this snapshot contains

Updated 26 September 2026 at David's request, from `connected-loop` commit
`9e0019f`. A deliberately small update: the emergency button was a correction
he asked for, so it went out; the new landing-page diagram and the
"what the pupil decides" section are additions, so they are held back for the
domain. Built with `MINIMAL=1 demo/build-site.sh`, which is what holds them
back — the same source builds both versions.

- The landing page, opening on the guided walkthrough
- The nine-step walkthrough: three fictional pupils, a fictional fortnight
- One red emergency button in the sidebar, marked "use only in an emergency"
- Per-note sharing: whole team / one adult / nobody
- Information circles on every section
- Environment events and the adjustment lifecycle
- The policies page, in both the pupil and the adult wording

No real child's data has ever been in this, and there is no server behind it.
Everything runs in the reader's own browser.
