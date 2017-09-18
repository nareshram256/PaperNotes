## [A Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576)
Leon A. Gatys, Alexander S. Ecker and Matthias Bethge, Submitted on 26 Aug 2015

TLDR; 

### Key Points

### Notes / Questions

### Results

* Code1: [anishathalye's neural-style](https://github.com/anishathalye/neural-style)

 ```
  python neural_style.py --content <content file> --styles <style file> --output <output file> --network <pre-trained vgg network>
  python neural_style.py --content examples/2-content.jpg --styles examples/2-style2.jpg --output examples/test.jpg --network imagenet-vgg-verydeep-19.mat
 ```
 * Content + Style = Output
<p align="center">
<img src="https://github.com/gcunhase/PaperNotes/blob/master/notes/imgs/neuralstyle_content.jpg" height="300" alt="Content" hspace="20">
 <img src="https://github.com/gcunhase/PaperNotes/blob/master/notes/imgs/neuralstyle_style.jpg" height="300" alt="Style">
</p>

<p align="center">
 <img src="https://github.com/gcunhase/PaperNotes/blob/master/notes/imgs/neuralstyle_output.jpg" width="300" alt="Output">
</p>


* Code2: [andersbll's neural_artistic_style](https://github.com/andersbll/neural_artistic_style)
  * [Installation steps](http://blog.josephmisiti.com/making-neural-art)
 
 
* [code3](https://github.com/cysmith/neural-style-tf), [code4](https://github.com/lengstrom/fast-style-transfer)

