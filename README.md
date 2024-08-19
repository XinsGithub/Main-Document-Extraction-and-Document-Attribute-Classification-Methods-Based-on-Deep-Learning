Introduction:
The Internet has a huge amount of information and is growing at an exponential rate. 
Document information is particularly important for people's work and life. 
However, it is difficult to obtain meaningful data for people from massive document information, and document classification is a prerequisite for extracting information from massive documents, so document classification is particularly important. 
In numerous studies, it has been found that layout cutting is an efficient technique based on object detection. 
In this text classification task, using layout segmentation facilitates dividing a complete article into smaller sections and applying them to Faster R-CNN.

Methods:
This project mainly studies the techniques for classifying articles based on their main content. 
On the basis of sufficient layout analysis techniques, the image is divided into small regions.
We use the Faster R-CNN algorithm to extract and classify features for each region, and then integrate the features of multiple regions within an article to form a document's features, achieving the goal of classification and backbone extraction.

Usage:
