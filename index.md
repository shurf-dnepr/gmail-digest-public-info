# Gmail Telegram Digest

A private, personal-use assistant that reads the owner's incoming Gmail messages and sends a morning summary to the owner's Telegram chat. It runs daily around 09:30 Europe/Kyiv.

The application requests Gmail read-only permission. It does not send, delete, archive, label, or mark emails as read. There is no public registration.

Email text is processed by Google's Gemini Developer API Free Tier to generate summaries. GitHub Actions runs the application, and Telegram delivers the summaries.

[Privacy policy](privacy.md) · [Terms of use](terms.md)

This website contains application information only. The application source code, credentials, messages and delivery state are private.
