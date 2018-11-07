---
title: 'Text-based editor update: safer saving'
date: 2018-11-07 12:13:22
tags: 
- Editor
- Text-editor
- Update
---

The saving system of the text editor has been improved. Before saving to the RC servers, the editor will check if a more recent version exists on the remote server. This for example can happen when two collaborators are working on the same exposition at once, or when a user is using more than one tab.

If a newer version is found, editor will ask user what to do, to minimize chance of unintentially loosing data.