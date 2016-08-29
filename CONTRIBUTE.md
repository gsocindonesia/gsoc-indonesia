# Berkontribusi ke Pelatihan Google Summer of Code (GSoC) Indonesia - Materi Workshop

Dokumen ini disusun menggunakan [ReadTheDocs](http://readthedocs.io) dengan format reStructuredText. Silakan rujuk dokumentasi ReadTheDocs untuk informasi lengkap.

## Crash Course

1. `git clone` repository ini:

        git clone https://github.com/lskk/gsoc-indonesia.git

2. Install [Python 3](http://python.org). Untuk Windows, Anda bisa gunakan [Anaconda3](https://www.continuum.io/downloads).
3. Install Sphinx

        pip install sphinx sphinx-autobuild

4. Untuk menjalankan sphinx-autobuild dan meng-_generate_ dokumentasi terformat secara terus menerus:

        sphinx-autobuild . _build/html

5. Buka http://127.0.0.1:8000/ (yang menampilkan folder `_build/html`) di peramban web.
6. Sambil mengedit, dokumentasi terformat akan terus diperbarui oleh sphinx-autobuild.
