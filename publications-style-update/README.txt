PUBLICATIONS LAYOUT UPDATE

1. Upload the layouts and static folders INSIDE this package into the repository root, merging with the existing folders.
   Do not upload the ZIP itself, or replace/delete existing folders.
   This adds two new template files and five publication images.

2. Edit content/home/publications.md.
   Change ONLY the widget line to:
   widget: publications-visual
   Optionally change title: Publications to title: Selected Publications.
   Keep the existing weight and other content.

3. Commit the changes. Wait for the Netlify production deploy to complete, then refresh the website.

Publication titles, authors, dates, and links are read from the existing content/publication entries.
Five studies have image rows. Other publications remain visible as compact entries.
The approved BP illustration is included. Figure links open the full-size image.
The existing navbar, Contact, Prior Projects, and other sections are unchanged.
To undo the layout, restore the previous widget value in content/home/publications.md.

This package is ready to upload; it has not been pushed or deployed.
