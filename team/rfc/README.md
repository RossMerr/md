# LoveOS RFCs

The RFC (request for comments) process provides a consistent and controlled path for discussing substantial, technical changes to loveOS. It works like this:

1. Write down your proposal as a markdown file
2. Create a merge request
3. Discuss it via GitLab line comments, face to face discussions or scheduled meetings with others
4. Get approval for the proposal
5. Adopt the proposal

📡 RFC creations and approvals are broadcasted automatically in the Microsoft Teams "rfcs" channel.


## When to follow this process
Developers should use this process to collaborate on the technical vision of the loveOS platform. Use this process whenever you want to discuss substantial, technical changes to the loveOS platform. The process fills the gap between "having an idea for an improvement" and "having actionable tasks". Some example RFC topics:
* Migrations
* Adopting new technology
* API design
* Architecture of a new loveOS vertical
* Shared usability / design / layout concepts across frontends
* Changes to the RFC process

Small technical improvements like refactorings might not require an RFC and can be submitted as a "Technical Debt" ticket instead.


## Process Steps

### 1️⃣ Write a proposal
* Prepare your participation by cloning this repo
* Whenever you want to propose/discuss something, copy `template.md` to `rfcs/foo-bar.md` and start to fill out the markdown template
* Add any assets (images, videos, ...) to `assets/`


### 2️⃣ Create a merge request
Once you feel ready to share your idea with others:
* Create a branch and commit your file
* Create a merge request and assign it to yourself to make you the owner

If you want to share an incomplete RFC and invite others to contribute missing parts, add the `WIP` prefix to the merge request name and remove it once you consider the RFC to be complete.


### 3️⃣ Discuss
Everyone is encouraged to give feedback and contribute changes to open merge requests:
* Give 👍/👎 to the merge request to show your overall appreciation.
* Start a discussion by commenting on a line.
* React to a comment with an emoji. Use 👍 and 👎 to "vote" on comments.
* Propose changes through comments first. When the owner approves, you may commit those changes to the actual file.
* Start face to face discussions or schedule meetings if appropriate. Important results however should be posted as comments to keep essential parts of the discussion documented.

The goal here is to work towards consensus and gain the support of others with convincing discussion arguments but also with incorporating feedback into the markdown file. Feel free to keep merge requests open for weeks or months or during proof of concept implementations. Consensus and clarity is more important than speed.


### 4️⃣ Approve
A merge request is approved and can be merged by the owner if
* it has at least 3 👍
* it has more 👍 than 👎
* it has no open discussions
* it has no WIP prefix
* a reasonable amount of time (~3 days) has passed without any new discussion activity

If there is absolutely no chance to reach a consensus, the owner should close the merge request.


### 5️⃣ Adopt

Once an RFC is merged, the owner is responsible to carry out the "adoption strategy" section of the RFC, but is not obligated to do everything on her/his own. The RFC owner should rather act as an advocate for its adoption by
* talking to management about necessary support (people, time, etc) and scheduling
* creating tickets once the implementation starts (usually of type "Technical Debt")
* keeping track of the overall progress

Ownership ends when the RFC is fully implemented.


## Process results
By following the process steps, the following artifacts are created:
* A folder with RFC markdown files describing concepts, that everybody agrees on (rfcs/ folder on master branch)
* An overview of ongoing discussions (open merge requests)
* An archive of past discussions (merged/closed merge requests)


## Ownership
* Everyone can open an RFC.
* Everybody can contribute to open RFCs via comments or commits.
* It is also fine to collaborate on an RFC as a group.
* However, every RFC should have one formal owner (the merge request assignee), who does the housekeeping and some moderation to prevent the RFC from getting stuck.
* Ownership ends when the RFC is fully implemented.
