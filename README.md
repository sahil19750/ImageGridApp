# 🖼️ Image Grid App (Android - Kotlin)

This is a high-performance image grid application built using **Kotlin**, **RecyclerView**, **Coroutines**, and a custom **in-memory + disk caching image loader**. It fetches images from the Acharya Prashant API and displays them in a 3-column grid, optimized for smooth scrolling and responsiveness.

---

## 🚀 Features

- ✅ Fast image loading with in-memory & disk caching
- ✅ RecyclerView with GridLayoutManager (3 columns)
- ✅ Coroutine-based network and disk IO handling
- ✅ Placeholder and error fallback images
- ✅ Scroll-state-based lazy loading
- ✅ Nearby image preloading for smooth scrolls
- ✅ Handles view recycling and fast flings safely


## 🛠️ Tech Stack

| Layer         | Library/Framework |
|---------------|-------------------|
| UI            | XML Layouts       |
| Logic         | Kotlin            |
| Async Tasks   | Kotlin Coroutines |
| Networking    | HttpURLConnection |
| Image Caching | LruCache + File   |
| Layout        | RecyclerView + GridLayoutManager |

---

## 🔧 Setup Instructions

1. **Clone the repo**
   ```bash
   git clone https://github.com/sahil19750/ImageGridApp.git
