+++
title = "A Fast and Accurate Object Detection Algorithm on Humanoid Marathon Robot"
date = "2020-03-31"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.

authors = ["Eko Rudiawan Jamzuri", "Hanjaya Mandala", "Jacky Baltes"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "Indonesian Journal of Electrical Engineering and Informatics (IJEEI)"
#publication_short = "ISBI"

# Abstract and optional shortened version.

#abstract = "We propose a generalized focal loss function based on the Tversky index to address the issue of data imbalance in medical image segmentation. Compared to the commonly used Dice loss, our loss function achieves a better trade off between precision and recall when training on small structures such as lesions. To evaluate our loss function, we improve the attention U-Net model by incorporating an image pyramid to preserve contextual features. We experiment on the BUS 2017 dataset and ISIC 2018 dataset where lesions occupy 4.84% and 21.4% of the images area and improve segmentation accuracy when compared to the standard U-Net by 25.7% and 3.6%, respectively."

abstract = "This paper introduces a fast and accurate object detection algorithm based on a convolutional neural network for humanoid marathon robot applications. The algorithm is capable of operating on a low-performance CPU without relying on the GPU or hardware accelerator. A new region proposal algorithm, based on color segmentation, is proposed to extract a region containing a potential object. As a classifier, the convolution neural network is used to predict object classes from the proposed region. In the training phase, the classifier is trained with an Adam optimizer to minimize the loss function, using datasets collected from humanoid marathon competitions and diversified using image augmentation. An NVIDIA GTX 1070 training machine, with 500 batch images per epoch and a learning rate of 0.001, required 12 seconds to minimize the loss value below 0.0374. In the accuracy evaluation, the proposed method successfully recognizes and localizes three classes of marker with a training accuracy of 99.929%, validation accuracy of 99.924%, and test accuracy of 98.821%. As a real-time benchmark, the algorithm achieves 41.13 FPS while running on a robot computer with Intel i3-5010U CPU@ 2.10 GHz."

# Featured image thumbnail (optional)
#image_preview = "static/img/ftl.png"

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
url_pdf = "http://section.iaesonline.com/index.php/IJEEI/article/view/1960"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#[[url_custom]]
#name = "Journal"
#url = "https://link.springer.com/article/10.1007/s10584-014-1174-4"

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true
  
# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "ftl.png"
#caption = "My caption :smile:"

+++
A Fast and Accurate Object Detection Algorithm on Humanoid Marathon Robot.  

In *Indonesian Journal of Electrical Engineering and Informatics (IJEEI)*, 2020. 