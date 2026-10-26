# Dr. Todd’s You Can’t Make This Sh*t Up

Crazy short stories from a career in emergency medicine.

A small web app for dictating short stories one at a time and turning them into a book, with a title page, contents and one chapter per story.

## Using it

1. Open the site and tap **Record a story**.
2. Tap the microphone on your phone keyboard and tell the story. You can also type or paste.
3. Reorder stories with the arrows. Each story becomes a chapter.
4. Open **Read the book** to see it formatted, then save it as an **.epub** e-book (Apple Books, Google Play Books, Kindle via Send to Kindle) or a printable **.html** page.

Leave out patient names, dates and other identifying details.

## Where stories are saved

- **On this website:** stories are saved in your browser on that device only. Clearing browser data deletes them, so save the e-book regularly as a backup.
- **In Claude:** the Claude version of this app keeps one shared book for everyone it’s shared with and adds a “Clean up with Claude” button that tidies dictated text.

## Files

- `index.html` is the whole app: one self-contained page with no build step. It loads fonts from Google Fonts and JSZip from cdnjs for the e-book export.
