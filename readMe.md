# YouTube Manager — SQLite 

A small command-line YouTube video manager that stores video records in a local SQLite database.

## Files

- `youtube_manager_db.py` — CLI app providing simple CRUD operations for video records using `sqlite3`.

## Features

- List videos
- Add a video (name and time)
- Update a video's name/time by ID
- Delete a video by ID
- Persists data in `youtube_videos.db` (created automatically)

## Requirements

- Python 3.6+ (uses the standard library `sqlite3` module)

## Usage

Run the manager from the project directory:

```bash
python youtube_manager_db.py
```

Follow the on-screen menu to list, add, update, or delete videos.

## Notes

- The database file `youtube_videos.db` is created in the same directory as the script.
- No external dependencies are required.

## Next steps

- Add unit tests or a simple UI wrapper if desired.
- Let me know if you want a README variation (detailed usage examples, badges, or contribution guidelines).
