# Face Verification  
This project uses two different model  
### MTCNN model:  
First it uses MTCNN model from facenet module to detect faces in the image  
### INCEPTIONNETV1 model:  
It passes the cropped image of face through the resnet model  
We get embeddings in the shape of (1,512)  
The faces to be verified is present in faces folder  
### Cosine Similarity  
Cosine similarity is used to compare both the embeddings of the image  
The output is the name with highest cosine similarity
