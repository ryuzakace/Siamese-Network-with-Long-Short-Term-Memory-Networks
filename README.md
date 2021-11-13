# Siamese-Network-with-Long-Short-Term-Memory-Networks

## LSTM
![image](https://user-images.githubusercontent.com/25671784/141598815-7567bef1-279d-4ee3-83e0-21d1fcd6777b.png)

## Siamese architecture
![image](https://user-images.githubusercontent.com/25671784/141599452-efea498e-1252-429f-bc6b-6f3095be9781.png)

## Loss Function
Total Loss Function :<br> ![image](https://user-images.githubusercontent.com/25671784/141599570-2598ec89-3719-46c3-8e2e-c604aff068e4.png)

Let fW(x1) and fW(x2) be the projections of
x1 and x2 in the embedding space computed by
the network function fW. The energy of
the model EW to be the cosine similarity between
the embeddings of x1 and x2:<br>
![image](https://user-images.githubusercontent.com/25671784/141599616-0e3219a5-3da5-42e7-901f-5518b7f4d09e.png)

The instance loss function L(i)
W is a contrastive loss
function, composed of terms for the similar (y = 1)(L+) and the dissimilar (y = 0)(L-)<br>

![image](https://user-images.githubusercontent.com/25671784/141599685-2a8c770c-9ccc-4204-b677-dd8e0ac33524.png)

![image](https://user-images.githubusercontent.com/25671784/141599700-0149b3fd-b77a-4049-b174-cbbbcb76419b.png)


