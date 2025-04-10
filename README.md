# CodeCollector
CodeCollector is a tool made for preparing prompt with relevant parts of code-base, and code-base management.

User picks relevant parts of code to include in final prompt for LLM.

# Features

-Allows to group items (marked code-parts and whole files) by "features". User just selects checkboxes the single items or "features" to have them added for final prompt for LLM.

-Allows to add separate code-parts inside single file, and track them, so you will always see it's content if it would be edited. 
It's done by marking these code-parts by markings (made by commenting the code) with unique IDs.
CodeCollector keeps track of these unique IDs in it's database

-Allows to add (by path/filename) whole file, for CodeCollector to track them

-Lets user see which files weren't yet marked or added to CodeCollector database

-Lets user see (when marking code for CodeCollector database) which parts of a file are already marked, and allows to skip to unmarked parts

-Lets user add whole folders of files (with deduplication - warnings about already added items)

-Lets user see recent changes of all code-parts/whole files, and their backup versions (which it automatically creates)

---

# Future CodeCollector features - to be implemented:

-codebase analysis to find all interconnected/related code (so LLM would not miss anything when implementing/fixing)

-ability to quickly accept new code from LLM to existing code-base (to individual code-parts/files), showing difference and analyzing for task conformity

# Releases

https://github.com/u5893405/CodeCollector/releases/download/alpha/code-collector.build.18.march.exe
