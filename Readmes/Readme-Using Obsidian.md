Parent: [[HOME-Personal Knowledge Management Systems]]
Status: #readme
Tags: #obsidian 
Synopsis:  **Using the Obsidian tool**, including notes on Obsidan Markdown

## First Steps

# TODO-ObsidianScreenshot
Take a screenshot of Obsidian title bar update readme
	* Explain opening closing the bars
	* Expain how to get back to the folder view
	* Explain Backlinks 

In the Title Bar of the Window
*  📂 Folder Icon shows the file structure
*  🔎 Search for tags, files, or text
* 🔖 Bookmark icon shows your bookmarks



## Using Obsidian

1. First you have to **understand Markdown**, start with he official [Obsidian Markdown Reference](https://help.obsidian.md/Editing+and+formatting/Basic+formatting+syntax)
2. Learn how to use [Tabs in Obsidian](https://help.obsidian.md/User+interface/Use+tabs+in+Obsidian)
   
3. **Creating Notes/Applying Template:** 
	1. ctrl-n = create new note, or maybe
	2. ctrl+o = open -> Helps to find related notes
	3. After creating Note press   **"Ctrl-T"** to apply a template (See [[ZettelKastenSystem#Types of Notes]])
	
4. **Using Tags**
	1. **Taxonomy:** Visit the [[Readme-Tag Taxonomy]] to learn the tag names
	2. **Tag References:** Tap on a tag anywhere to show all references to a tag in the left pane
	    (click file folder icon in the top left of titl bard to get back to folder view)
	3. **Renaming Tags:** If the TagWrangler plugin is installed an enabled, right click on any tag to rename. 
	4. **Global Tag Map**: Clickthe Tag Map Icon (Below Search) in left sidebar to view the Tag Cloud
	5. **Local Tag Map:** use ellipsis at upper map of page -> Open Linked View -> Local Tag Map
		1. Use "Filters" to adjust depth of local tag map
		2. 

## Things that confused me:

I often expect Markdown Viewers to work like Word or Google Docs.  Markdown is not quite that capable.   These are things where I commonly am not able to accomplish exactly what I am setting out to do. 

* **Multi-Level Lists** In general, [Multi-level Lists](https://www.makeuseof.com/how-to-create-lists-obsidian/) in markdown are pretty easy, however in Obsidian, it is not easy to create second-level lists with a., b., c. .. Instead, use bullet points for second level lists as recommended in this [Obsidian feature request](https://forum.obsidian.md/t/multi-level-lists-and-alphabetic-lists/3889)
  
* **Indenting Text:**  Creating things like a list with titles and a paragraph indent is not easy in Markdown.  Major flaw, IMO.   However, the web shares this characteristic. 
  
# Obsidian Markdown Notes

* **Separating Tags from Headers** : Headers have a space after the hasthag, Tags do not.
   
* Link to internal anchor (heading in note):   See [Obsidian: internal Links](https://help.obsidian.md/Linking+notes+and+files/Internal+links) .  
	*  Syntax:  [ [ Note Heading # internal anchor name] ]
	*  Example [[Readme-Using Obsidian#Things to learn about Obsidian]] 
	  
* **Images**.  To display an image use one of 
	* Obsidian Style    ! [ [ image-file-name ] |100x150]  (Works only in obsidian)
	* Relative file path:  :\[Title\]\\(../../image-file-name.png)
	* See [Stack Overflow: Changing Image Size in Markdown](https://stackoverflow.com/questions/14675913/changing-image-size-in-markdown)
