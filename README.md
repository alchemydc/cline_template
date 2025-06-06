# cline_template
Scaffold for vibe-coding projects with [Cline](https://cline.bot/)

After cloning, `mv cline_template $NEW_PROJECT_NAME` && `rm -rfv .git` to create a new name and delete the git history for the project.

The Cline VScode plugin will find the available Cline Rules in [.clinerules/clinerules-bank](.clinerules/clinerules-bank) and you can use the toggles within the plugin to enable or disable specific rules.  They will all be enabled by default, which is likely not what you want.  I recommend enabling just the memory-bank rule for starters.

Then, edit [.ai/memory-bank/projectbrief.md](.ai/memory-bank/projectbrief.md) to taste and run `initialize memory bank` from Cline cli within vscode.

NB: agentic AI can be a tremendous force multiplier for people that *already know what they're doing*, but it will create unmaintainable insecure spaghetti code without close oversight.  If you're tackling a project of any serious scope, I recommend taking a look at [BMAD METHOD](https://github.com/bmadcode/BMAD-METHOD) which does a nice job of encapsulating a mature SDLC in various agent personas to create artifacts that will keep tools like Cline, Roo, Cursor, Augment et-al on the rails.
 