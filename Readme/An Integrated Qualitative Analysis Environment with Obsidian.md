# Guide to using this environment

The core idea of this [Obsidian](https://obsidian.md) vault: take each of the pieces of text you're working with, make it easy to traverse them, and add in ways of coding them and writing up what the codes mean. The environment only needs markdown files (and optional plugins for statistics). For the installation basics, see the [[Original installation readme from GitHub]].

This environment was built with a [grounded field theory](https://fulcra.design/a-brief-informal-guide-to-doing-grounded-theory) approach in mind. Deeply read each data point, highlighting the key points and looking for commonalities and oddities. As those interesting phenomena emerge, cluster and describe them under themes, also called **codes**. Check each theme/insight against one another and refine them, also through abstraction via **memos**. Once the data has been thoroughly reviewed, quantify the number of responses attributed to each of the themes (use the **Code Index** to classify) in order to get a sense of the most and least common themes through **statistics**. A final **report** based on this analysis might consist of a ranked list of these themes, sorted by how often they were reported, a description of each theme, and a selection of illustrative responses for them from students. 

# Preparing the data
First, make every data point its own markdown (`.md`) file, naming them sequentially starting at 1. The data points used are separate interviews.

Find the subfolder in this vault folder called "data points" (or rename it to whatever you'd like). Place all of your data points in this folder. 

(Optional: Putting the data points in each of their own files and numbering them sequentially is a trick: it allows us to use the core Daily Note plugin's "Next Daily Note" and "Previous Daily Note" commands to quickly traverse the responses. So, set those two commands to an easy-to-reach hotkey (I used <kbd>cmd</kbd>+<kbd>alt</kbd>+<kbd>→/←</kbd>. You will be using these commands at least once for every piece of data you're analysing!)

Second, find the folder in called "codes". In your new Obsidian vault, go to `Preferences → Files & Links → Default Location for New Notes`, and change this to your “codes” folder. This will mean that every new note you create from links or from the "New note" command will show up in this folder. At the right side of each code (like [[Ideengeber]]), you can find the backlinks of that note: these are all places where a code is mentioned.

## Coding the data
Just at the point when a quote is relevant for a code, add a link via: `[[` This was you can connect with existing codes. Write up a new link and ctrl+click to create a new code. (Or just create a new note with the other options of Obsidian, e.g. in the menu.)

### Review the data
What does it say? What's interesting about it? How might it help you answer your research question(s)? Think of the answers to these questions as themes: they are the interesting takeaways relevant to this piece of data. In the footer, write out these themes.

Here's the secret to making this whole set-up work: add each code as an internal `[[`link`]]`. That affords us several things:
- Codes are suggested when you start a new internal link `[[`, so that we can choose from the options instead of trying to recall them.
- The individual responses will be structurally related to the codes via backlinks (and visually linked to the codes via the graph view).
- Editing a code by renaming it will propagate the change to that code throughout the data.
- Finally, it makes codes themselves an object we can add information to. You can open a code-as-link as a note and describe it, embed exemplary instances of the coding from the responses, and so on.

You may want to keep a [[Code Index]], just to provide an easy place to organize and see all the codes you've identified at once. In the code Index, list each code you add to your data. Feel free to order them under headings or however else you'd like!

## Analyzing the data
When using grounded field theory, you should incrementally update, revise, and refine your theory—your encoding—as you review the data. The goal is to render visible all of the interesting insights that lie inside your data, to clearly explain what those findings are, and to continually check and re-check them as you continue to review your data. Apart from revising codes, use **memos**: theoretical abstractions that may also include lengthy literature references.

Here are key points to do:
1. refining existing themes by (a) summarizing and adding detail to them (commonly referred to as writing memos about the themes), perhaps using the Canvas options, (b) embedding particularly illustrative examples of them in the codes, (c) splitting up themes if they actually contain different important ideas, and (d) combining themes if they are significantly overlapping; and
2. as necessary, looking for themes of themes with the help additional memos: clusting and structuring the insights you've found inasmuch as the clustering makes your takeaways clearer or more impactful. 

# Reporting on the data
Once you've reviewed all the data at least once, you should have a set of themes clustering the different data points by the interesting insights they contain. Give an overview of all codes and their relations in the [[Report]]. Once you feel satisfied with the takeaways, it's time to write it up.

#### Quantifying your themes
An easy thing to do is quantify the number of data points associated with each theme. This gives you a quick estimate of how frequent or common these takeaways are found in your data. 

There are many many ways you may quantify the number of data points per theme. The simplest is just to use Obsidian's core Search functions. For each theme, enter `"[[` followed by the exact name into your search, then end the search query with `]]"`. This will search for exact mentions of the linked theme. Once the search has finished, tap on the Copy Search Results button above the search query text box. Last, in the options presented to you, change the List Prefix to "Numbered." This gives you a count for the number of results for each theme.

However, that could be tedious if you have a lot of themes to count. Instead, this environment uses the Dataview plugin. See the [[Statistics]] page. The plugin has to be installed via `settings>community plugins`

This generates a table listing each theme, the number of data points associated with that theme, and the number of other themes you've linked to that theme (if you have done so at all). 

When reporting on your themes, these counts give you some starting points. Why do the top themes appear so frequently? Why are the bottom ones rare? Speculate, theorize, debate, and discuss!

