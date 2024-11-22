# LLMs in Action: How Booking.com Scans, Detects, and Monitors Fake and Unsafe Content
### Presentation: [Pyladies Workshop 20 Nov 2024 - Booking.com  (2).pdf](https://github.com/pyladiesams/llms-scan-reviews-nov2024/blob/72d310e253ddd8e5a73f092b09299d39651e7556/Pyladies%20Workshop%2020%20Nov%202024%20-%20Booking.com%20%20(2).pdf)

## Workshop description
Explore the power of LLMs in this hands-on workshop featuring real use cases from Booking.com. Learn how to scan and detect fake and unsafe content in reviews, and discover how AI is applied to keep reviews trustworthy and the platform secure. 

The workshop will be divided into two parts. The first part will introduce the business use case and explain how LLMs come to the rescue in detecting and preventing fake content. In the second part, participants will get hands-on experience working with script-generated reviews, gaining an overview of relevant models from Hugging Face, and training a model specifically for this purpose. You’ll also learn practical applications using Hugging Face's powerful transformers library.

Whether you're interested in LLMs, online safety, or the mechanics of content moderation, this session offers an in-depth look at the cutting-edge tools that help maintain a safe digital environment.

## Requirements
- Google Colab with GPU.
- If downloading this repository, Git Large File Storage from https://git-lfs.com/.
  
## Setting Up Notebook for Part II (Hands-On)

Download the files from Google Drive https://drive.google.com/drive/folders/1VGcRvOlyto0SxMmU9Y5Ds2ySgASB5-IE?usp=sharing and upload to your Drive. 

Then:
1. Open the Notebook in Google Colab.
2. Enable GPU Runtime:
- Go to Runtime > Change runtime type in the Colab menu
- Set Hardware accelerator to GPU
- Click Save
3. Mount your Drive. This can be done with a cell:
  ```
  from google.colab import drive
  drive.mount('/content/drive')
  ```
4. Add the Drive files to the Colab runtime:
```
import sys
sys.path.append('/content/drive/MyDrive/<PATH_TO_YOUR_FILES>')
```
 
## Credits
This workshop was set up by @pyladiesams and @flozefi.
