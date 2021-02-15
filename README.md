# `shannon`: Collection of Compression Algorithms

![]( https://imgs.xkcd.com/comics/digital_data.png)

This repository is to serve as a collection of compression algorithms implemented in **Python** and/or
**Rust** as a learning exercise.

#### Book

In addition, I am putting together (very work-in-progress) book where I will jot down concepts and
toy problems I come across, which will hopefully improve my understandings.  This is built with
[Jupyter-Book](https://jupyterbook.org/) using this [website](https://whitead.github.io/dmol-book/)
as inspiration.

This can build locally with:

```bash
$ cd book && jupyterbook build . && open _build/html/index.html
```
Alternatively, visit www.compression-cookbook.com

### References and Resources

* [Zstandard Blog post](https://engineering.fb.com/2018/12/19/core-data/zstandard/)
* [Smaller and faster data compression with Zstandard](https://engineering.fb.com/2016/08/31/core-data/smaller-and-faster-data-compression-with-zstandard/)
* [Zstandard Zstandard Compression RFC](https://www.rfc-editor.org/rfc/pdfrfc/rfc8478.txt.pdf)
* [FSE decoding : how it works, Yann Collet's Blog](http://fastcompression.blogspot.com/2014/01/fse-decoding-how-it-works.html)
* [Finite State Entropy - A new breed of entropy coder](http://fastcompression.blogspot.com/2013/12/finite-state-entropy-new-breed-of.html)
* [Compression with LZ77, Tim Guite](https://timguite.github.io/jekyll/update/2020/03/15/lz77-in-python.html)
* [The Hitchhiker’s Guide to Compression, Online Book](https://go-compression.github.io/)
* [The Hutter Prize](http://prize.hutter1.net/index.htm)
* [Data Compression Explained by Matt Mahoney](http://mattmahoney.net/dc/dce.html)
* [Data Compression Programs by Matt Mahoney](http://mattmahoney.net/dc/)
* [SO: What is the difference between different "compression" systems?](https://askubuntu.com/questions/436679/what-is-the-difference-between-different-compression-systems#:~:text=The%20actual%20compression%20algorithms%20zip,a%20top%20choice%20these%20days.)
* [SO: How are zlib, gzip and zip related? What do they have in common and how are they different?](https://stackoverflow.com/questions/20762094/how-are-zlib-gzip-and-zip-related-what-do-they-have-in-common-and-how-are-they/20765054#20765054)
* [SO: Difference: LZ77 vs. LZ4 vs. LZ4HC (compression algorithms)?](https://stackoverflow.com/questions/28635496/difference-lz77-vs-lz4-vs-lz4hc-compression-algorithms/28635890#28635890)
* [Yann Collet explains zstd](https://www.youtube.com/watch?v=jl9ncLcMlVY&t=95s)
* [Leonardo's Blog (Mr. MPEG)](https://blog.chiariglione.org/)
* [Encoder Complexity Hits the Wall!](https://www.linkedin.com/pulse/encoder-complexity-hits-wall-david-ronca/)
* [An Overview of H.264 Advanced Video Coding](https://www.vcodex.com/an-overview-of-h264-advanced-video-coding/)
