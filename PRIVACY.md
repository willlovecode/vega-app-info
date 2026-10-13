# Privacy policy

Vega is a personal assistant that runs on its developer's own Windows PC. It
has exactly one user, who is also its developer. See the [overview](README.md)
and the [terms](TERMS.md).

## What Vega reads from Google

Vega asks for two read-only permissions: `calendar.events.readonly` and
`calendar.calendarlist.readonly`. It cannot create, change or delete anything
in Google Calendar.

Of each event it requests only the title, the start and end time, the place,
the status, whether it is part of a series, the event type, and the user's own
response to an invitation. It does not request descriptions, conference links,
or other attendees' names or email addresses.

Events are read live, when the user asks or when Vega builds a daily or weekly
summary (a "brief"). Vega does not keep a copy of the calendar.

## What is stored

On the user's PC, and nowhere else:

- the Google login (a refresh token and the OAuth client id and secret), in
  the app's own state folder;
- the list of which calendars to read;
- the text of saved briefs, which can contain event titles, times and places.

## What leaves the PC

The title, time, place and calendar display name of events can be sent to the
language model the user has chosen, so that it can answer a question or write
a brief. That model is Anthropic's Claude or OpenAI's ChatGPT through the
user's own subscription, or a model running locally on the PC. Calendar ids
and email addresses are not sent to a model.

Data is not sold, not used for advertising and not shared with anyone else.

## Removing access

Run `vega calendar disconnect`, which deletes the stored login, and revoke
Vega at https://myaccount.google.com/permissions.

## Google API Services User Data Policy

Vega's use of information received from Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements.

## Contact

walbert.privat@gmail.com

Last updated: 2026-10-13
