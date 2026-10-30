# BPL Dream

A small Python-based dream journal for capturing, listing, and searching dreams.

## Features
- Add a dream entry with title, mood, and notes
- List saved dreams
- Search dreams by keyword
- Persistent storage in a local JSON file

## Run
```bash
python dream_tracker.py add "Flying over a city" --mood "excited" --notes "I was gliding above neon rooftops."
python dream_tracker.py list
python dream_tracker.py search city
```

## Files
- `dream_tracker.py` - CLI app
- `dreams.json` - storage file created when you add entries
