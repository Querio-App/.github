# Culture

1. **Blameless** — “*If a person makes an error, it is because a system let the person make the error.” —* [Medium **Article](https://medium.com/dazn-tech/building-a-blameless-culture-301662a59317#id_token=eyJhbGciOiJSUzI1NiIsImtpZCI6ImMzN2RhNzVjOWZiZTE4YzJjZTkxMjViOWFhMWYzMDBkY2IzMWU4ZDkiLCJ0eXAiOiJKV1QifQ.eyJpc3MiOiJodHRwczovL2FjY291bnRzLmdvb2dsZS5jb20iLCJhenAiOiIyMTYyOTYwMzU4MzQtazFrNnFlMDYwczJ0cDJhMmphbTRsamRjbXMwMHN0dGcuYXBwcy5nb29nbGV1c2VyY29udGVudC5jb20iLCJhdWQiOiIyMTYyOTYwMzU4MzQtazFrNnFlMDYwczJ0cDJhMmphbTRsamRjbXMwMHN0dGcuYXBwcy5nb29nbGV1c2VyY29udGVudC5jb20iLCJzdWIiOiIxMDEwMTkzNzcxMzI3MTE3MDA5MjEiLCJlbWFpbCI6InJvYmVydHNvbmd3aW9uMjFAZ21haWwuY29tIiwiZW1haWxfdmVyaWZpZWQiOnRydWUsIm5iZiI6MTc0NDc0NzgwMCwibmFtZSI6Ikd3aW9uIFJvYmVydHNvbiIsInBpY3R1cmUiOiJodHRwczovL2xoMy5nb29nbGV1c2VyY29udGVudC5jb20vYS9BQ2c4b2NJUVY5RDhGTUhLRW1GVWExZ3R3LUJpX2lBWDNjakpMSUE2Q0oyeDdEQ3llY0RmX3c9czk2LWMiLCJnaXZlbl9uYW1lIjoiR3dpb24iLCJmYW1pbHlfbmFtZSI6IlJvYmVydHNvbiIsImlhdCI6MTc0NDc0ODEwMCwiZXhwIjoxNzQ0NzUxNzAwLCJqdGkiOiJiNWM4YjcxYzQyOTM2ZmJhYThhMzgxNGFhMTJkYmIzZGE3MDg0ZTUyIn0.oqdIVJuK0kEjfLaw7DlzLh4rSrBMjNDXpJcB3uR7I1BNvl9niFXdDunZ6qR-T8w3VG0nAzgthVkmPsUZPkBdym8DhZK-o6_l_ZvrdPYTAwi5I290HSkWMgs6_grFMLE9d9fxltrrbXttSayTcy61fDpKFbdKd-3jlQYOdXifbVgBk88__UmAfe-TT1sa3Q3r853RmU364c2CaWR1Kwe3bj7ukCEgD37fX4HYpCpM3MAMEC6wsOK4DQTM6Okf8Sh8QGEPyNL727Fqbmm6thkTukKZ9YFPcneQl95Ow_rClRvQTAmfRrKoVN-lSjle1xss4CmK15Q0iVIURLjCRJOkaw) 
2. Help bring things to life and keep each other accountable.
3. Constantly do demos, find product shortcuts that make the engineering simpler and help ship fast, always ship fast. 
4. Guidelines feel like chores at the beginning, until they don’t. They become second nature and help work like an A team. 

# Kanban

1. It’s everyones responsibility.
2. Keep it up to date and try to follow priorities. 
3. See a bug, make a ticket. 
4. Tickets without details are worst than no ticket at all. Write full sentence titles and add clear descriptions. 
5. Javi is chief delegator, not ticketmaster. 
6. Prep for Engineering Weekly.
    1. Is your kanban up to date? 
    2. Anything tech debt, infra, etc we should discuss? 

# Communication

1. Over-communicate instead of under. 
2. Quick question? Quick huddle. Can’t answer? No problem. 
3. Sync before embarking on a big feature. 
    1. Consider if an [ADRs](https://www.notion.so/ADRs-8eb124b1bdfb477f951d1df4fe0331b6?pvs=21) would be helpful? 
    2. Can we ship a small end to end subset to reduce uncertainty and apply some [**Design in Practice**](https://www.youtube.com/watch?v=c5QF2HjHLSE&ab_channel=ClojureTV)?

# PR Reviews

1. Reviewing code > writing code → Unblocking other devs and help ship is top priority. 

# Coding Style

1. Variable naming
    1. camel + pascal in TS, snake in Python. 
    2. If a variable denotes a denomination, suffix the denomination e.g. `textAreaPx` or `timeoutLengthMs`. 
    3. long variable names with details > shorter ambiguous names. 

# Branches & Commits

1. Create branches off GitHub issues/tickets. 
    1. Branch names will be provided and issues/tickets will auto close.
2. Write your own commit messages | pr descriptions | docs, AI is sloppy and lacks detail.
3. **Linear git history.** linear history is easier to read back, easier to bisect over and easier to revert if necessary. 
    1. in practice this means rebasing over merging almost always.
    2. note that rebasing does not have to mean squashing. 
4. Please fill in the `pull_request_template` in your PRs.
