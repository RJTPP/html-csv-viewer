# 📋 CSV/JSONL Table Viewer


A single-file, zero-dependency **viewer** for `.csv`, `.tsv`, `.jsonl`, `.ndjson`, and line-based `.json`.  
Works fully **offline**, supports **resizable columns**, **filtering**, **pagination**, **paste-to-load**, and **export**.

## Features
- Single HTML file, no build, no deps  
- Works offline, no data uploads  
- CSV/TSV delimiter auto-detect, JSONL streaming parse  
- Long text truncation with “Expand” + “Copy”  
- Resizable & auto-fit columns (double-click)  
- Case-insensitive search by all fields or single field  
- Pagination (10–500 rows)  
- Export filtered/full data as CSV or JSONL  
- Paste modal for raw CSV/JSONL text  

## Usage
1. Save as `index.html`.
2. Open in a modern browser (Chrome/Edge/Firefox/Safari).
3. Load data by:
   - Drag & drop a file  
   - **Browse** button  
   - **Paste Data** modal  

## Tips
- Double-click column resizer = auto-fit  
- Search + Export = export filtered data  
- Column widths & overflow setting are saved in `localStorage`  

## Privacy
- 100% client-side, no network calls.  

## License

This project is released under the [MIT License](LICENSE).