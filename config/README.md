# Config
When using this you **must create a config.json** in the **config directory**, just copy the **example_config.json** content and just fill in whatever you need!

# Values
| Key | Description |
| --- | --- |
| token | This is the token for your Discord bot. |
| channel_to_post_in | This is the channel in which the bot should post bug reports, make sure this is the channel ID and the bot can write to the channel. | 
| reply_timeout_in_seconds | The timeout in seconds after which the bot will shutdown the bug report. |
| report_cooldown_in_seconds | The timeout in seconds after which a user can report a new bug. |
| attachments_message | The style for the message which will be displayed when an attachment is posted in the bug report. |
| goodbye_message | The message which will be displayed when a bug report has been finished. |
| timeout_message | The message which will be displayed when a user is taking too long to answer a question. |
| submitted_by_message | The style for the message which will be displayed when the user posted a bug report. |
| cooldown_message | The style for the message which will be displayed when the user is still on a cooldown. |
| welcome_message | The style for the message which will be displayed when the user sends a message to report a new bug. |
| questions | The information needed in order to display a question. |
| questions.question | The style for the message which will be displayed when the user is prompted a question. |
| questions.display | The style for the message which will be displayed when the bug reported is posted. |
| questions.answers_possible | The answers which are possible for this question, may be empty. |
| questions.wrong_possible_answer | The response when a user enters a wrong answer to a fixed question, can't be empty if a fixed question is required. |