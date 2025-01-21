# Git commit message

To write a great git commit message, take a look at these guidelines and suggestions.

Contents:

- [Top priorities](#top-priorities)
- [Begin with a short summary line](#begin-with-a-short-summary-line)
- [Continue with a longer description](#continue-with-a-longer-description)
- [Summary examples](#summary-examples)
- [Summary keywords](#summary-keywords)
- [Real-world examples](#real-world-examples)
- [Use semantic versioning](#use-semantic-versioning)
- [Specifics for right and wrong](#specifics-for-right-and-wrong)
- [Specifics for length](#specifics-for-length)



## Top priorities

For the best git commit messages:

  * Read these guidelines and suggestions, then discuss them with your teammates.

  * Emphasize clear communication, because commit messages help you and your teammates.
  
  * Use a git commit template, such as ours [here][git commit template].


## Begin with a short summary line

Begin with a short summary line a.k.a. message subject:

  * Start with an imperative present active verb: Add, Drop, Fix, Refactor, Optimize, etc.

  * Use up to 50 characters; this is the git official preference.
  
  * Finish without a sentence-ending period.


## Continue with a longer description

Continue with a longer description a.k.a. message body:

  * Add a blank line after the summary line, then write as much as you want.
  
  * Use up to 72 characters per line for typical text for word wrap.

  * Use as many characters as needed for atypical text, such as URLs, terminal output, formatted messages, etc.

  * Include any kind of notes, links, examples, etc. as you want.
  

## Summary examples

Summary examples of good commit messages:

  * Add foo

  * Drop foo

  * Fix foo

  * Refactor foo

  * Optimize foo


## Summary keywords

We recommend these summary keywords because they use imperative mood, present tense, active voice, and are verbs:

  * **Add**: Create a capability e.g. feature, test, dependency.

  * **Drop**: Delete a capability e.g. feature, test, dependency.

  * **Fix**: Fix an issue e.g. bug, typo, accident, misstatement.

  * **Bump**: Increase the version of something e.g. a dependency.

  * **Make**: Change the build process, or tools, or infrastructure.

  * **Start**: Begin doing something; e.g. enable a toggle, feature flag, etc.

  * **Stop**: End doing something; e.g. disable a toggle, feature flag, etc.

  * **Optimize**: A change that MUST be just about performance, e.g. speed up code.

  * **Document**: A change that MUST be only in the documentation, e.g. help files.

  * **Refactor**: A change that MUST be just a refactoring patch

  * **Reformat**: A change that MUST be just a formatting patch, e.g. change spaces.

  * **Rearrange**: A change that MUST be just an arranging patch, e.g. change layout.

  * **Redraw**: A change that MUST be just a drawing patch, e.g. change a graphic, image, icon, etc.

  * **Reword**: A change that MUST be just a wording patch, e.g. change a comment, label, doc, etc.

  * **Revise**: A change that MUST be just a revising patch e.g. a change, an alteration, a correction, etc.

  * **Refit/Refresh/Renew/Reload**: A change that MUST be just a patch e.g. update test data, API keys, etc.

We recommend these summary keywords for things that don't fit into the above categories:

  * **Major**: Anything that causes a major version increase.

  * **Minor**: Anything that causes a minor version increase.

  * **Patch**: Anything that causes a patch version increase.

## Real-world examples

Real-world examples show how we use imperative mood, present tense, active voice, and verbs:

  * **Add** feature for a user to like a post

  * **Drop** feature for a user to like a post

  * **Fix** association between a user and a post

  * **Update** dependency library to current version

  * **Make** build process use caches for speed

  * **Start** feature flag for a user to like a post

  * **Stop** feature flag for a user to like a post

  * **Optimize** search speed for a user to see posts

  * **Document** community guidelines for post content

  * **Refactor** user model to new language syntax

  * **Reformat** home page text to use more whitespace

  * **Rearrange** buttons so OK is on the lower right

  * **Redraw** diagram of how our web app works

  * **Reword** home page text to be more welcoming
  
  * **Revise** link to update it to the new URL

Real-world examples for things that don't fit into the above categories:

  * **Major** overhaul of our API from version 1 to 2

  * **Minor** improvement of our API from version 1.1 to 1.2

  * **Patch** our API from version 1.1.1 to 1.1.2


## Specifics for right and wrong

Capitalize the summary.

  * Right: Add feature

  * Wrong: add feature

Finish the summary without a sentence-ending a period.

  * Right: Add feature

  * Wrong: Add feature.

If the summary ends with an non-sentence-ending period, use it.

  * Right: Add feature for U.S.A.

  * Wrong: Add feature for U.S.A

Use imperative mood: present tense, active voice, and lead verb.

  * Right: Add feature

  * Wrong: Adds feature (this is indicative mood, not imperative mood)

  * Wrong: Added feature (this is past tense, not present tense)

  * Wrong: Adding feature (this lead is a gerund, not a verb)

  * Wrong: Feature added (this is passive voice, not active voice)


## Specifics for length

Keep it short but get across everything you changed