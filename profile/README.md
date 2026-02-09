# Culture

1. Help bring things to life and keep each other accountable.
2. Constantly do demos, find product shortcuts that make the engineering simpler and help ship fast, always ship fast. 
3. Guidelines feel like chores at the beginning, until they don’t. They become second nature and help work like an A team. 

# Kanban

1. It’s everyones responsibility.
2. Keep it up to date and try to follow priorities. 
3. See a bug, make a ticket. 
4. Tickets without details are worst than no ticket at all. Write full sentence titles and add clear descriptions. 

# Communication

1. Over-communicate instead of under. 
2. Quick question? Quick huddle. Can’t answer? No problem. 
3. Sync before embarking on a big feature. 
    1. Consider if an [ADRs](https://www.notion.so/ADRs-8eb124b1bdfb477f951d1df4fe0331b6?pvs=21) would be helpful? 
    2. Can we ship a small end to end subset to reduce uncertainty and apply some [**Design in Practice**](https://www.youtube.com/watch?v=c5QF2HjHLSE&ab_channel=ClojureTV)?

# PR Reviews

1. Reviewing code > writing code → Unblocking other devs and help ship is top priority. 

# Branches & Commits

1. Create branches off GitHub issues/tickets. 
    1. Branch names will be provided and issues/tickets will auto close.
2. Write your own commit messages | pr descriptions | docs, AI is sloppy and lacks detail.
3. **Linear git history.** linear history is easier to read back, easier to bisect over and easier to revert if necessary. 
    1. in practice this means rebasing over merging almost always.
    2. note that rebasing does not have to mean squashing. 
4. Please fill in the `pull_request_template` in your PRs.
