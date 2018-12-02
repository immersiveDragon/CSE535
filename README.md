# Numerical Computation 
This is a final project not just a research reading and summary, which means you need to actually implement the algorithm you selected to process a certain dataset (search and choose by yourselves) to see the performance and demonstrate your results. You also can see that there is a "result & discussion" criterion in the evaluation sheet. So you have to present your own results of implementation. There are four important components you have to figure out.

1. Algorithm. You have to understand completely about the algorithm you choose. Try to search online for tutorials, papers, videos to help understanding. This is a necessary part for any research project. 

2. Dataset. You have to implement your chosen algorithm on a dataset to demonstrate how your implementation works, and how you complete that specific application/project. You can search and choose the dataset by yourselves, but  the dataset should be appropriate to your topic. For example, if you choose facial recognition as your project, you can choose the face datasets such as YALE, FACET, etc. (a lot online). But if you do text mining, you have to search the dataset of texts. 

3. Implementation of your algorithm. In order to implement the algorithm you chose, you need to understand how the algorithm works (list as component 1) and then convert it to codes. To verify your implementation, you need to apply it to a dataset. After choosing a dataset, you have to know how the dataset is organized, it is organized as a 2 dimensional matrix or 3 dimensional one, what is the physical meaning of each dimension. Lab 4 actually provides such practice to understand the dimensions of a dataset. During your implementation, you may have to do reshape of matrix (from 2 dimensions to 3, or from 3 dimensions to 2) since the algorithms have specific dimension requirement on data matrix (depends on algorithms, figure that out by understanding the algortihm).

4. Recognition/mining/separation. The last thing to do is recognition/mining/separation. Here let me use face recognition with NMF as an example. There will be two phases in recognition: training and testing. For the dataset you chose, you need to label all face images (i.g. give a number or name to each category, all images from the same person should be labeled as the same category). The purpose of training phase is to find the common basis of face, this is training phase (learning). Lab 4 actually is the training phase. In order to do recognition, we need another testing phase, which is to use the learned basis (result of training phase) to recognize testing data. Testing data can be part of training data (the dataset you choose). In testing phase, just project the testing data to learned basis, then you can get the coefficient vectors for all testing faces. Since the training data is labeled, by comparing the coefficient vectors of testing data and the coefficient vectors of training data, the testing data can be recognized and classified to a certain label or name. If the recognized label/name is the same to its true label of this image, then it is a correct recognition, otherwise it is incorrect. By doing statistics of all correct recognitions, you can get the recognition accuracy/rate.

Hope it helps. 

Dr. Sun

To leave more time on the project, I will schedule all the project presentations on next Tuesday (Dec. 4th) from 8:00 - 10:00am. We have 10 groups, so every group only has 12 minutes. In order to finish by 10am (there will be another exam starts at 10), every group is required to send your PPT to me by 10pm on Dec. 3rd. I will put all PPTs in one folder in order for your fastest access on the presentation date. 

Best,

Dr. Sun

Youtube:
https://www.youtube.com/watch?v=ZTxXGZwe2gw
