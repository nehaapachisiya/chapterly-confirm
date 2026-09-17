# confirm.chapterly.in

One page. It is where a parent lands after tapping **"Confirm my email address"**
in a Study Companion sign-up email.

Supabase confirms the account at its own endpoint and then redirects here, so
this page's only job is to say plainly whether it worked and what to do next —
including when it did **not** work, because Supabase redirects here on an
expired or reused link too.

The source of truth is `web/confirm/index.html` in the Study Companion
repository, where it is covered by tests. This repository is a publishing
target: edit it there, not here.

No analytics, no fonts, no images, no third-party requests of any kind.
