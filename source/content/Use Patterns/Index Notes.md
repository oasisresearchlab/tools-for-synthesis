---
Type: Use Pattern
---
![[Pasted image 20240626180430.png]]
## Motivation and Description

Index notes are constructs that help users [[🎣 Retrieve Information Artifacts|retrieve]] and [[♻️ Reuse Information Artifacts|reuse]] information by [[🏗️ Consolidate Materials for Active Sensemaking|bringing related materials together in one place]]. 
## Example(s)

### Manually curated topical index  
One [[Tana]] user created a [[Note Page]] titled “Topics/Index” to manually curate all topical [[Tag]]s. The tags were organized in alphabetical order within [[Note Block]]s. She used versioning to manage different iterations of the index, noting:

> _This is the space where you can gather together all of the topics that interest you until you can refine them further._  

The iterative nature of this manual index suggested its potential to evolve into an [[Incubator Notes|incubator]] over time.

![[Pasted image 20240704000322.png]]

### Structured search for related topics
Another [[Tana]] user built a course note page that linked to related source notes. Using a [[Structured Queries|structured query]], he generated an index of topics that appeared in the [[Supertag]] [[Metadata|field]] of linked source notes.

![[Screenshot 2024-01-30 at 1.47.10 PM.png]]

### Indexing literature and permanent notes
A third [[Tana]] user created an index of literature notes and permanent notes using a [[Structured Queries|structured query]] of notes that were of type "topic" (i.e., had a "topic" [[Supertag]] applied to them). Each of these topic notes had nested [[Structured Queries]] underneath them for literature and permanent notes that had the relevant topic in their [[Metadata]] under the "topic" field. 

![[Pasted image 20240413011330.png]]


## What's needed to enact this pattern

In addition to the tools mentioned above, this pattern can be supported by any tool that includes the following technical primitive(s):
- [[Structured Queries]]
- [[Tag]]
- [[Metadata]]
- [[Internal Hypertext Links]]