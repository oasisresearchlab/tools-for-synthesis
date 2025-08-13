---
Type: Use Pattern
---
## Motivation and Description

Source materials in scholarly sensemaking are often in formats not well-suited for direct use in hypertext-based notetaking systems. To bridge this gap, users create _source notes_ to [[🚛 Transfer Information Artifacts Between Different Locations|represent source materials in their digital notebooks]], enabling them to easily [[🎣 Retrieve Information Artifacts|retrieve]] the original materials, such as a paper's corresponding PDF file.

Source notes also serve as anchors that support the development of more complex notes (e.g., summaries, syntheses) while [[🌱 Track Provenance of Information Artifacts|keeping them connected to their origins]].
## Example(s)

### Creating source notes from external reference managers

One user used Supertags in [[Tana]] to create notes for source materials, particularly papers. Information such as [[Metadata]] and highlighted text was copied from [[Zotero]] into Tana. In Tana, this was structured into a [[Note Block]] where:

- The paper title was the top-level note block and tagged with a "paper" Supertag - this marks it in Tana as a note of type "paper", with the corresponding [[Metadata|schema for metadata]].
- Highlights became child note blocks.
- Metadata fields of the "paper" were filled with structured bibliographic data.  
    This process was typically done in the user’s daily notes.

![[Pasted image 20240410230954.png]]

### Linking source notes to original files

Another user created [[Note Page]]s for literature notes in [[Obsidian]] using a [[Template]] for consistency. In the note metadata, he added [[External File Links]] pointing to files stored in [[DevonThink]]. This allowed him to work with literature notes in Obsidian while keeping a direct connection to the original file stored elsewhere.

![[Pasted image 20240429113142.png]]  
![[Pasted image 20240429113217.png]]

## What's needed to enact this pattern

In addition to the tools mentioned above, this pattern can be supported by any tool that includes the following technical primitive(s):

- [[Metadata]]
- [[Tag]]


