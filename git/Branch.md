# Git Guidelines 
> _What may be a hassle at first soon becomes habit, and eventually a source of pride and productivity for all involved._

## Branch

### Semantic Branch name

Each branch name should include a **type**, a **user** and a **name**:

`<type>/<user>-<name>`

Name should not exceed 34 characters. This allows the branch to be easier to read on github as well as in various git tools and produces a nice.

##### Type

Must be one of the following:

- **feat**: A new feature;
- **fix**: A bug fix;
- **docs**: Documentation only changes;
- **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc);
- **refactor**: A code change that neither fixes a bug or adds a feature;
- **test**: Adding missing tests;
- **chore**: Changes to the build process or auxiliary tools and libraries such as documentation generation.

##### User

The user could be the first 3 characters of your git username or the name you prefer to be called.

##### Name

The name contains succinct description of the change:

- Use the imperative, present tense: "change" not "changed" nor "changes";
- Lowercase the name;
- No dot (.) at the end;
- No dot user special characters;
- Separate words with dashes (-) or underscore (_), instead of white-space.

##### Branch examples

`feat/user-add-beta-sequence`

<hr>

**P.S**: The pull request must always be made to the branch ` develop `, will not be accepted PR's for the ` master `

