Parent:  [[HOME-Personal Knowledge Management Systems]]
Status:  #readme 
Tags:
Synopsis: **How to Install Obsidian and  set up this knowledge vault** .
## Reference 
This knowledge vault is based on [[Author-Artem Kirsanov]].
## Installing Tools
1. Install Obsidian from the [download] page.

## Obsidian Plugins
Currently the obsidian plugins are included in the  git repo 
## I. Creating a New Vault

1. Create the vault folder on your local hard drive, 
2. Set up your Syncing system, for example with GitHub:
	* In your  GitHub account, create a new repository
	* Clone the repository to a folder on your local drive 
3. Launch Obsidian, and  open the folder as an Obsidian Vault
4. Create the following folders in the repo: 
	  - Zettelkasten (notes)
	  - Templates
	  -  References
	  - Resources

# II. Obsidian Settings
1.   Visit the settings (gear icon in the lower left).
	*  Files and Links:  
		* -> Default Location for New Notes -> "In the Folder Specified Below" -> "Zettelkasten"
		* -> "Default Location for Attachments" -> Folder -> "Files"
	* Appearance -> Themes -> select a theme.
	* Hotkeys -> Templates -> Ctrl-T
	* **Core Plugins**
		* -> Tag Pane -> Enable
		*  -> Templates -> Enable
		*  -> Zettelkasten Prefixer -> (Leave Off) - Prefixes note names w YYMMDD
	* **Community Plugins**
		* You may need to  turn off Safe Mode (!), or "enable community plugins" (That was on by default for me)  
		* NOTE:  There are Lots of Plugins!  -  Don't go too far down the rabbit hole
		  
		*  [Admonition](https://github.com/javalent/admonitions) - Fancy formatting, like "Question", "equation" etc.
		* ~~[Sliding Panes](https://github.com/deathau/sliding-panes-obsidian) - Display notes side by side~~  (Replaced by Obsidian Tab feature)
		* [Mermaid Tools]() - Draw mermaid Diagrams
		* [Mind Map](https://help.obsidian.md/User+interface/Use+tabs+in+Obsidian) Display Mind maps from Markdown
		* [Tag Wrangler](https://github.com/pjeby/tag-wrangler) - Global Search and replace of Tags
		
	* **Templates**
		* Template Folder Location -> Templates	  

# III. Create Note Template(s)
 
 1. Select the template folder 
 2. Enter boilerplate as seen in the [[AtomicNote]] note.
 3. To apply a template, open a note, then press Cmd-T, and type template name. 

# IV. References folder
This system is often used for scholarly articles, or books, where referencing source material is  important.    The references folder might contain, for example data about a  book or an author or both.  

You can insert references by using double square brackets, and typing the note title.  (Obsidian will autocomplete easily)

# IV. Create Zettels (slips, or Notes)
The main value of this system comes from having references and tags attached to your notes, so it is imperative that yo

1. Have an Idea, or read something you want to save. 
2. Look for existing notes:  open the Zettelkasen folder, and press "ctrl-O", and begin typing a title.   This will display al list of related notes - you may end up adding your new stuff to an existing note.   Or if you type enough words to get no search results, you can press Enter to create a new note. 
    Alternative:  Ctrl-N to directly create a new note. 
 3. Press Cmd+T and assign the ZK-CoreIdea template. 
 4. Fill in your note,
 5. Assign tags - Use autocomplete to find existing notes
 6. Decide if you need a separate Reference page, or just fill in references in the ref section.  



# References 
Additional Readmes: 

 * [[Readme-Tag Taxonomy]]
 * [[Readme-Using Obsidian]]

 