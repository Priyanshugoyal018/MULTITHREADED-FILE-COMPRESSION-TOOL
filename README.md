# MULTITHREADED-FILE-COMPRESSION-TOOL
Company : CODETECH IT SOLUTION
Name : Priyanshu Goyal 
Intern id : CT08DG1149
Domain : C++ Developer
Duration : 8 Weeks
This is a C++-based multithreaded file compression and decompression tool using a simple Run-Length Encoding (RLE) algorithm. It processes files in chunks and compresses/decompresses them in parallel using multithreading, improving performance for large files.

## Features
✅ Compresses large files using multithreading
✅ Simple Run-Length Encoding (RLE) algorithm
✅ Decompression support included
✅ Thread-safe logging using std::mutex
✅ Customizable chunk size (default: 1MB)
✅ Works on .txt, .csv, .log, and other text-based files

## How It Works
The file is read in chunks (1MB each).
Each chunk is sent to a separate thread for compression/decompression.
Compressed output is written as compressed.rle.
Decompressed output is written as decompressed.txt.
Compression is based on Run-Length Encoding, where repeated characters are stored as char + count.
## OUTPUT

