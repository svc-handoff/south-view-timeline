# South-View Cemetery: Lives That Shaped Atlanta

Interactive timeline of notable people buried at South-View Cemetery in Atlanta, built with TimelineJS (Knight Lab) for a Georgia Tech class project in partnership with South-View Cemetery and the Praise House Project.

## Updating the timeline

The timeline reads the "South-View Timeline Data" Google Sheet every time the page opens. To add or change a person, edit the sheet and refresh the page. No code changes are needed.

- One row per person. Name, Born, Died and Theme are required.
- Milestones are written as `year: what happened`, for example `1952: Opened the pavilion`.
- People who share a value in "Connected through" are linked to each other. Separate several values with a semicolon.
- Photo can be a file in the `images` folder (`images/name.jpg`) or a full web address.

## Historical events

The gray bars at the top of the timeline are historical events. They come from the sheet's **Events** tab, one row per event:

- **Event**, **Start** and **End** (years) are required. Use the same year for Start and End for a one-day event, and put the exact date in **Dates shown**.
- **Summary** can have several paragraphs; press Ctrl+Enter (Cmd+Enter on a Mac) inside the cell for a new paragraph.
- **People in this story** lists people separated by semicolons, written as `Name: what they did`. A name that matches someone on the timeline becomes a link, and that person's card links back to the event.
- **Sources**, **Source links** and **Credit** work like the people tab. Set **Show on timeline** to No to hide an event.

If the Events tab can't be read, the page uses the copy saved in `index.html`.

If the sheet can't be reached, the page shows the copy saved in `index.html` and says so in the header.

Content is preliminary and pending review by South-View. Photos are used with permission from South-View Cemetery or credited to their sources.
