# Git Guidelines 
> _What may be a hassle at first soon becomes habit, and eventually a source of pride and productivity for all involved._

## Commit


### Semantic Commit Messages

Each commit message should include a **type**, a **scope** and a **subject**:

`<type>(<scope>): <subject>`

Lines should not exceed 62 characters. This allows the message to be easier to read on github as well as in various git tools and produces a nice.

##### Type

Must be one of the following:

- **feat**: A new feature;
- **fix**: A bug fix;
- **docs**: Documentation only changes;
- **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc);
- **refactor**: A code change that neither fixes a bug or adds a feature;
- **test**: Adding missing tests;
- **chore**: Changes to the build process or auxiliary tools and libraries such as documentation generation.

##### Scope

The scope could be anything specifying place or module of the commit change. For example webpack, redux, user, etc...

##### Subject

The subject contains succinct description of the change:

- Use the imperative, present tense: "change" not "changed" nor "changes";
- Capitalize the subject line;
- No dot (.) at the end.

##### Commit examples

`feat(user): add beta sequence`
