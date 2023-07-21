# Schoology Obsidian Plugin (SOI)
---

## Intro
This plugin integrates Schoology into the filesystem of Obsidian. The goal is (eventually) to allow students to never have to leave Obsidian, and can just interact with Schoology from Obsidian. 
*Features*:
- All Schoology courses are mirrored in the Obsidian file view, each as a folder.
- Write in Google Docs, Google Slides, and Google Sheets from Obsidian.
- Tag any of those files for organization



## Caveats
Google Docs, Slides, and Sheets are only currently editable from an embed web editor (it's just running docs.google.com in obsidian). Eventually, it'd be nice to be able to convert a Google Doc into a Markdown file, and vise versa. This would allow other plugins to more easily work with GDocs as if they were regular notes. I haven't been able to find any good implementations of GDoc to Markdown. Markdown to GDoc is easy - It's GDoc to Markdown which is hard. This is because GDocs are a "superset" of Markdown - everything in Markdown can be expressed as a Google Doc, but not everything in a Google Doc can be expressed in Markdown. I'm no expert here, but Markdown:
- Cannot express different fonts
- Only certain text sizes can be expressed in Markdown
- Cannot center, or left-align text
- Images cannot easily be moved or resized
- Paragraph spacing
 