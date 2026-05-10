# comics/

Drop all your comic images here.

## Naming convention
Use a clear, consistent naming pattern. Example:
- 001-cover.jpg   ← the square thumbnail shown in the grid
- 001-a.jpg       ← first panel
- 001-b.jpg       ← second panel
- 001-c.jpg       ← third panel (if it exists)

## Then update comics.json
Add one entry to comics.json like this:

{
  "id": "010",
  "title": "O título do teu comic",
  "date": "2025-05-10",
  "cover": "comics/010-cover.jpg",
  "images": ["comics/010-a.jpg", "comics/010-b.jpg"]
}

That's it. The site updates automatically.

## Image tips
- Square images work best (same width and height)
- JPG is fine, PNG works too
- Keep file sizes reasonable — compress before uploading (squoosh.app is free and great)
