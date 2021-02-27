# Vietnamese handwritten OCR task using Convolutional Recurrent Neural Network

## Summary
* OCR (Optical Character Recognition) is the task in which we need to tranfer text in images to ASCII characters.

![](https://i.imgur.com/GDJG3fK.png)


* OCR has always been a challenging task especially with a language containing diacritics as Vietnamese. A wide range of agorithm have been introduced, but the results are still very humble except CRNN (Convolutional Recurrent Neural Network).
* The notebook presents the process of building CRNN model for OCR task

## Implementation and Result
* The process includes several stages:
    *  Image preprocessing
    *  Data pipeline
    *  Building model
    *  Fine-tuning model
* The result which is evaluated by three criterion is very descent.
    * Character Error Rate: 0.046258110958333584
    * Word Error Rate:      0.1680945648048793
    * Sequence Error Rate:  0.8246575342465754
