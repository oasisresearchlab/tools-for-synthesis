---
Type: Use Pattern
---
![[Pasted image 20240704095945.png]]

## Motivation and Description

Users add metadata to notes to provide contextual information that supports effective [[🎣 Retrieve Information Artifacts|retrieval]] and [[♻️ Reuse Information Artifacts|reuse]] of the information in the notes for sensemaking. Metadata enables quick filtering by type, creation date, or other attributes. Some users also use metadata to [[🎢 Track Status of Sensemaking|track progress]]—for example, through [[Reading Status Markers]].
## Example(s)

### Creating metadata via command line

One [[Zettlr]] user created notes using [[Commandline]] tools, incorporating [[Metadata]] at the time of creation. Each note was automatically assigned an ID based on the date and time of creation, a note type (e.g., literature note, concept note), and optional tags.

![[terminal metadata.png]]  
![[Pasted image 20240428151209.png]]

### Metadata for source notes
A [[Tana]] user imported metadata for a collected book from [[Zotero]] into [[Tana]]. Using Tana's Supertag feature (which marked the note as a [[Source Note]] of type `#book`), he created [[Metadata|fields]] containing background information about the book. Some metadata was implicit—for example, a sun-like button at the end of a note block indicated reading progress. In this case, the icon showed the book had not yet been read.

![[Pasted image 20240704094005.png]]
## What's needed to enact this pattern

In addition to the tools mentioned above, this pattern can be supported by any tool that includes the following technical primitive(s):
- [[Metadata]]