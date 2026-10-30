# Privacy policy

Updated: 30 October 2026

This application is operated for the personal use of its owner. It accesses only accounts that the owner explicitly connects.

## Data and purpose

With Gmail read-only authorization, the application reads incoming email senders, subjects, timestamps and message text, including archived and already-read mail. This is used to identify messages requiring attention and prepare a daily summary. It does not modify the mailbox or send email replies.

## Processing and sharing

GitHub Actions processes the messages in a private repository's workflow. Message text is sent to Google's Gemini Developer API Free Tier for summarization with the owner's consent. Under the free service's terms, Google may use submitted content to improve its products and human reviewers may process it. Summaries are delivered through Telegram to the owner's configured chat. These providers process data under their respective terms and privacy policies.

The application does not sell email data, use it for advertising, or make it publicly available.

## Storage

Credentials are stored in GitHub Actions secrets. Delivery checkpoints and encrypted pending summaries are stored in a private repository branch; older versions may remain in Git history. Successful delivery clears the current pending summary. Application logs avoid message contents and credentials. Delivered summaries remain in Telegram until removed there. Provider retention rules may also apply.

## Control

The owner can stop scheduled runs, remove stored credentials, and revoke the application's access through Google Account permissions. Revocation prevents further Gmail reads but does not erase previously delivered Telegram messages, repository history or data retained by service providers. Those records must be managed separately with each provider.

This is a personal-use application with no public sign-up. For support, use the developer contact shown on the Google authorization screen.

