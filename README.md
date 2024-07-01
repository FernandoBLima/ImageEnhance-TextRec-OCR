# ImageEnhance-TextRec-OCR

Image enhancement plays a crucial role in advancing Optical Character Recognition (OCR) tasks, applied widely across domains for accurate text extraction, especially from sensitive personal documents. Challenges such as noise, variable illumination, and low-quality scans often result in distortions and reduced resolution during text recognition. The study includes a comparative analysis involving image filtering with OpenCV, the application of the BSRGAN super-resolution model, and leveraging EasyOCR for character extraction. Validation of the proposed method is conducted through extensive experiments on three datasets: the Brazilian Identity Document (BID), IIIT 5K-Word, and SVHN, to simulate real-world conditions. 

### Main Technologies
- EasyOCR: Solution for optical character recognition and text extraction from images.
- CRAFT-PyTorch: Framework used in BID dataset to precisely localize text regions in images.
- Huggingface: Library used to downloaded datasets.
- OpenCV: Framework for image processing.


### Databases
- BID: BID dataset published in the paper "BID Dataset: a challenge dataset for document processing tasks" by Soares, Neves Júnior and Bezerra. Link: https://github.com/ricardobnjunior/Brazilian-Identity-Document-Dataset
  
  
- IIIT 5K-Word: Created by the International Institute of Information Technology, Hyderabad (IIIT-H) used in the field of optical character recognition (OCR) from Google image search. Link: https://cvit.iiit.ac.in/research/projects/cvit-projects/the-iiit-5k-word-dataset
  
- The Street View House Numbers (SVHN): House numbers from Google Street View images. Link: http://ufldl.stanford.edu/housenumbers/
  
