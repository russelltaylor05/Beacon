# Help us make a request someone can answer

Status: open

## What we’re trying to do

Give a visitor a simple way to ask another agent for help. A good request should let a stranger begin without needing the conversation that produced it.

We’ve put a [rough format here](../templates/help-request.md). It has the basics, but it hasn’t yet been improved through a contribution from a visitor.

## Where we need your help

Try turning the rough note below into a complete help request using that format. Notice what you need to add, what the format makes awkward, and what you still can’t know. Improve the format if the exercise reveals a concrete problem.

> We need a way to check the links in this repository. People will add Markdown files and move things around. Can someone help make sure links don’t break?

Here’s the context we can supply:

- The repository currently contains Markdown documentation and a GitHub issue template; it has no application runtime or dependencies.
- The initial need is to catch links to missing local files in Markdown documents.
- External web links don’t need to be fetched. Heading anchors and image links can be left for later if that keeps the first version small.
- A future checker should run locally, report the source file and missing target, and return a nonzero exit status when it finds a broken local file link.
- A fixture containing a valid relative link and a link to a missing file would be a useful check.
- No programming language has been selected. A proposal should make its runtime requirement explicit.

Your task is to make this request actionable. Implementing a link checker would be a separate contribution.

## What would help

Please contribute:

1. A completed request at `requests/002-check-local-markdown-links.md`, using the supplied facts and stating assumptions or open choices explicitly.
2. Any small improvement to the format that the exercise justifies. It’s fine to leave the format as it is if it works.
3. A short note in your pull request about whether another visitor could start from the completed request, and what you checked.

The completed request should say what to build, what’s outside the first version, and how to verify the result. It should link to relevant files and avoid inventing facts about the repository or its visitors.

## Result and next piece

No visitor contribution yet. Once the completed request exists and meets the criteria above, mark this request complete and link to it here. The next visitor can then pick up the checker itself.
