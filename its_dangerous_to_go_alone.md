# It's dangerous to go alone! Take this!
## On finding your way in a code that's new to you

# Why did I write this talk?
- I like talking about tooling
- I wish someone told me before

# Things In The Way Of Finding Your Way
- Ruby
- Where do you start?
- Domain Specific Knowledge

# How does Ruby get in the way?
- Meta-programming Magic
- Flavour/Domain Specific Languages

# Ruby Tools
Let's go through a code base together and I'll show you how I follow stuff around currently

# Searching
- language server - Solargraph tries it best
- searching, fuzzy finding
  - (neo)vim - anyjump.vim
  - VSCode - vscode-dumb-jump

# Ruby Tools
The way Ruby is designed makes it hard for static tools to follow the code around
A solution to Ruby is Ruby
- Debugger driven development
- Find an entry point to drop a debugger in
- Pry: show-source
- Step through executing code

# Ruby Tools
Lost in the library?
- `bundle open <library>` and drop a binding

# Environmental Changes
- Type with Sorbet and RBS


# Entry Points
- Where can I start that touches the least amount of code I don't care about?
- Is there a way I can find a test?
  - Rails conventions - alternate file finders rails.vim, vim-projectionist, VSCode - alternate-file (never used it)
- What does this look like through the UI?
- Is there a pretty specific string I can start looking for the code?

# How do we gain Domain Knowledge
- Ask someone
- What is our vocabulary?
- How much do I need to know to get this working?

# Domain Knowledge Tools
Ask someone

# Why am I asking?
  - I need a shortcut vs Put me on the path
  - Avoid XY problems

# Why am I not asking?
- Unproductive
  - I don't want to appear like I don't get it
  - They must be busy
- Productive
  - I want to understand it in my own way and clarify my assumptions

# What is our vocabulary?
What level are we talking about?
- general progamming and technology terms
- Language specific terms
- Framework or Pattern specific terms
- Domain specific terms

# Understand your assumptions
If language is used in a way that we haven't come across, we should ask about it and document it
- If something has been around long enough, it could have changed enough that the name is misleading
- Evolutionary pressure on code to become one thing when it started as another
  - Ear -> Gill

# How much do I need to know to get this working?
- probably not that much
- it is a skill to know you are dangerous

# How do I build a map of the code in my head?
Reading and understanding code that is hard to understand is less like geography and more like archaeology.
A complete understanding will be more like a story than a map.


## How we can empower those that come after us by changing the environment
- Teach the tools to become code archaeologists
- Drawing maps
  - Documentation? or do you just get two problems?
- Better road signs
  - Naming is hard
- Cleaning up after ourselves
  - Who has the time
- Be kind to ourselves and those that follow
