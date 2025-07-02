# ⚙️ Node.js Multithreaded Worker Example

A simple Node.js project demonstrating how to use the native `worker_threads` module to offload CPU-intensive tasks using multiple workers.

---

## 📂 Project Structure

├── index.js # Main entry – single-threaded execution
├── index-four-workers.js # Entry for 4 parallel workers
├── worker.js # Worker logic (runs in separate threads)
├── four-workers.js # Logic to spawn and manage 4 workers
├── package.json
└── package-lock.json
