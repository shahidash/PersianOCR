# Persian OCR
A simple persian OCR system based on Recurrent Neural Networks written in Pytorch and OpenCV
![OCR Result Image](https://raw.githubusercontent.com/amirabbasasadi/PersianOCR/master/OCR_result.png)  

The program uses [Shotor dataset](https://github.com/amirabbasasadi/Shotor), A synthetic dataset which I created for Persian OCR.

## References
This paper helped me a lot, however my architecture is not same
- https://arxiv.org/abs/1805.09441
- [Pytorch Tutorial on RNNs](https://pytorch.org/tutorials/intermediate/char_rnn_classification_tutorial.html)  
For word segmentation using dilation see this:
- https://stackoverflow.com/a/10970473/4334320

The text of the image which I used to show the final result is a translation of this book:
- The Theory That Would Not Die, Sharon McGrayne
