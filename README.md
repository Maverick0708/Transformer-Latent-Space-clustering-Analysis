### The idea Behind this Project is to perform analysis on latent space created by a transformer. Database used for this purpose is DIT scientific papers data that contains information about papers published by professionals working at DIT. Bert algorithm is used to create the latent space, since it is a encoder only transformer. After that, eucledian distance is used to calculate the distance between the papers published by different authors to find the authors who might be working in the same areas but are not coauthors. Then K-means is applied on the latent space to group similar points in latent space together and study the result. Below is the inspiration for the project
https://jas.bayern/index.php/bjas/article/view/135


Below are the results 

The algorithm makes recommendatio based on the latent space generated by Bert. These authors might be working in the same areas but are not co authors

![result](https://github.com/user-attachments/assets/b851596d-82cc-4e18-ac57-e37fc24dc5a1)

After performing clustering on Latent space, key words are extracted from the latent space to see what key words pop out from the clusters. As is it visible, clusters produce keywords from the same topic. This might be useful in identifying papers and authors which focus in similar areas and topics

![Author1](https://github.com/user-attachments/assets/31855a22-4085-4afc-a6f3-b83962194455)

![Author2](https://github.com/user-attachments/assets/eb448836-1579-4b37-801b-0202e99e9307)

![author3](https://github.com/user-attachments/assets/e53db246-fe38-422d-9813-043c4ff4d370)

![author4](https://github.com/user-attachments/assets/f3215192-a901-445d-8ac2-bdf146f7cb65)

![author5](https://github.com/user-attachments/assets/cbff66f7-e02d-4aa0-9748-b898001a2e1e)





