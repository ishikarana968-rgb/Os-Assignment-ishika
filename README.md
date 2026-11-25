# Operating Systems Lab (CEC301) — Python

Practical file for **CEC301: Operating Systems**, B.Tech (CSE) Third Year.
**Author:** Himanshi Tyagi

## Programs

| No. | Topic | File |
|-----|-------|------|
| 1 | Process creation: `fork()`, `exec()`, `wait()` | `fork_exec.py` |
| 2 | Threads and synchronization | `thread_sync.py` |
| 3 | CPU scheduling: FCFS, SJF, Priority, Round Robin | `cpu_scheduling.py` |
| 4 | Producer-Consumer problem | `producer_consumer.py` |
| 5 | Readers-Writers problem | `readers_writers.py` |
| 6 | Dining Philosophers problem | `dining_philosophers.py` |
| 7 | Banker's Algorithm | `bankers.py` |
| 8 | Memory allocation: First, Best, Worst Fit | `memory_allocation.py` |
| 9 | Page replacement: FIFO, LRU, Optimal | `page_replacement.py` |
| 10 | Disk scheduling: FCFS, SSTF, SCAN, C-SCAN | `disk_scheduling.py` |
| 11 | File allocation: Contiguous, Linked, Indexed | `file_allocation.py` |

## Requirements

- Python 3.9+
- Linux / macOS / WSL for Program 1 (`os.fork()` doesn't work on native Windows)
- No external libraries needed

## How to Run

```bash
python3 cpu_scheduling.py
```

Output of the threaded programs (2, 4, 5, 6) may vary slightly between runs.
