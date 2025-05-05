# 🧩 Sliding Puzzle Game

This is a classic *sliding puzzle* (15-puzzle) game built with Python and `pygame`. Instead of numbers, an image is split into tiles. Your goal is to rearrange the scrambled tiles to restore the original image.

## 📸 Screenshot (Example)
<img width="997" alt="Screenshot 2025-05-05 at 17 29 57" src="https://github.com/user-attachments/assets/8c3e59b6-8159-45e0-ae92-e43921435c18" />

## 📦 Requirements

- Python 3.7+
- [`pygame`](https://www.pygame.org/)
- [`matplotlib`](https://matplotlib.org/) (used internally but not required for gameplay visuals)

## 🗂 Project Structure

```
project/
├── main.py
├── puzzle.py
├── image.jpg       # Image used for the puzzle
```

> Make sure `image.jpg` is present in the same folder. You can replace it with any other image of your choice.

## ▶️ Running the Game

```bash
python main.py
```

## 🎮 Controls

Use the **W, A, S, D** keys to move the empty tile:

| Key | Action         |
|-----|----------------|
| W   | Move tile up   |
| A   | Move tile left |
| S   | Move tile down |
| D   | Move tile right|

## 🔥 Features

- Smooth animations for tile movement
- Random shuffling at game start
- Easy customization of puzzle size and image
- Built using `pygame` with real-time rendering

## 📄 License

MIT License
