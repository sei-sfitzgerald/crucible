# Admin Practice Area

Gameboard administrators configure the global Practice Area content here. In the main navigation bar, click **Admin**, then **Practice Area**.

## Practice Page Greeting

The text here appears on the Practice Area page and introduces players to the Practice Area. The greeting is authored in Markdown, which allows you to create a nicely formatted message. Customize the greeting to meet your needs.

More information about Markdown, including the syntax guide, can be found at [www.markdownguide.org](https://www.markdownguide.org).

## Suggested Searches

Suggested searches appear on the Practice Area homepage just below the greeting and direct players to useful or interesting subsets of available practice challenges. These searches act as filters for tags attached to a challenge. (When a challenge is created, the developer can optionally add tags that describe the skills needed to solve the challenge.)

Only tags that match the suggested searches are displayed to the player when browsing the Practice Area. This ensures players see relevant tags that help them find the challenges they are interested in.

To enter suggested searches, list one search term per line.

## Certificate Template

Admins configure the certificate template here by entering HTML into the **Certificate Template** field. Players save certificates in PDF format for each practice challenge they fully complete. More information on certificates can be found in the [Profile screen](profile.md) documentation.

For your convenience, here are several variables you can include in your template to display information about the player's performance on a practice challenge.

- `{{playerName}}`: The player's approved username
- `{{score}}`: The player's score on the challenge
- `{{date}}`: The date the player completed the challenge
- `{{challengeName}}`: The name of the challenge
- `{{season}}`: The season the challenge was originally played in competitive mode
- `{{track}}`: The track the challenge was originally placed in competitive mode
- `{{time}}`: The amount of time the player spent solving the challenge

Additional information about creating certificate templates can be found in the [Configuring Certificate Templates](admin-completion-certificates.md) topic.

## Session Limits

Admins use these controls to set limits on practice sessions, including:

- **Maximum Concurrent Users:** How many players can be active at once
- **Default Session Length:**  How long in minutes practice sessions are by default
- **Maximum Session Length:** How long in minutes the maximum length a single practice session lasts
