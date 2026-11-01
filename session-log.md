AABE course folder, version 2026-1
2026-11-01

## 2026-11-01, session 1, part 2: skills, starting with folders

What the student did: asked the agent to draw the course folder as a tree and propose a thesis folder with the four habits. Answered the folder-context questions on storage, parent project and name. Approved the path.

Result: folder-context started and asked before writing. The agent created /Users/tinabarratttommervik/Documents/master-thesis as a standalone local project. It holds AGENTS.md, CLAUDE.md, README.md with a Folder context section, log.md, and empty folders sources/, work/ and outputs/. thesis.docx was not created.

Added later the same day: the agent copied skills/folder-context/SKILL.md to /Users/tinabarratttommervik/.claude/skills/folder-context/SKILL.md for Claude Code. The checksum matched the course copy. Not yet checked that a new session lists the skill. No copy for Codex.

Added later the same day by the agent: the tree and the proposal as the agent drew them during the part 2 task.

The course folder as the agent drew it:

```
AABE/
  .agents/
    skills/
      folder-context/
        SKILL.md
  .claude/
    skills/
      folder-context/
        SKILL.md
  AGENTS.md
  CLAUDE.md
  my-page/
    index.md
  session-log.md
  session1/
    01-language-models.md
    02-skills-and-folders.md
    03-what-an-agent-is.md
  skills/
    folder-context/
      SKILL.md
```

The agent's proposal for the thesis folder, before the student chose the name master-thesis:

```
thesis/
  AGENTS.md        rules the agent reads first, with the language rule copied in
  CLAUDE.md        one line that points Claude Code to AGENTS.md
  README.md        what the thesis is about, and a "Folder context" section
  log.md           what you did in each session, with dates
  sources/         raw data and papers as you got them, never changed
  work/            scripts and notes the agent may change
  outputs/         tables and figures made from sources/ by the scripts in work/
  thesis.docx      the current draft, always under this one name
```

The four habits in the proposal: one project outside AABE. AGENTS.md and README.md at the top. Raw files in sources/ and never edited. Dated names without spaces for incoming files, and one stable name for the draft.

## 2026-11-01, session 1, part 1: what a language model is

Logged after part 2, because the entry was missed at the time.

What the student did: asked the agent to describe AGENTS.md in five short lines and name one thing a language model often gets wrong.

Result: the agent's five lines were: start each session with the log line, a summary and a question about the part. Explain each step and ask before changing files. Never handle keys, tokens or passwords. Guide the small tasks without doing them, and log the result. Write plainly, with no flourishes and no unchecked numbers. The thing models get wrong: a confident number or fact the model never looked up. The check: ask where it came from and open the source, for example count the files in session1 in Finder.

## 2026-11-01, session 1, part 3: what an agent is

What the student did: asked the agent to go through the session using session-log.md, naming the tool, what came back and the next decision for each step, and to judge the goal.

Result: the log held only the part 2 entry, so the agent took the earlier steps from the conversation and said so. Tools used: Bash (cat, find, mkdir), Skill (folder-context), AskUserQuestion and Write. Goal: a thesis folder with the four habits, made only after the student's yes. Judgement: the path, name, folder list and asking first were checkable and were checked. "Raw data kept raw" is only a rule and is untested. "Names that sort" cannot be checked until dated files exist.

## 2026-11-01, Deliverable 1: your GitHub page

What the student did: asked the agent to put their name in my-page/index.md, add a link to https://github.com/tinatoem/tinatoem.github.io and upload the file "as in part 4". Handed in https://tinatoem.github.io on Canvas.

Result: the agent changed the heading to "Mica" after the student approved the file. It added the line "Source for this page" with the repository link. No part 4 exists in the course folder, and my-page has no Git setup, so the agent did not upload. The browser pane needed a GitHub sign-in it never got. Claude in Chrome was not connected. Canvas attempt 2 was not approved: "No link to a repository on GitHub". The agent read the live page and the raw file on GitHub, and both still had the old content without the link. Still to do: upload the local index.md, check the live page, hand in again.

## 2026-11-01, session 1, part 3 task repeated

Result: the log ended at the skill install, so the agent took the my-page and GitHub steps from the conversation. Tools: Read, Edit, Bash, the browser pane and Claude in Chrome. Goal: a live page that passes Deliverable 1. Judgement: the Canvas check list is precise. The agent's own working goal was not, because it counted the local file as progress and did not check the live page before the hand-in. "As in part 4" could not be acted on.
