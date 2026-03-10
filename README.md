# Plant-Species-Image-Classification

 EXPORTED TEACHABLE MACHINE MODEL FILES: https://drive.google.com/drive/folders/1c8YZKYGyVrofW0jjtWe-7e1bfIgg9Qb2?usp=sharing

 DATA SET SCREENSHOT
<img width="1885" height="1011" alt="image_dataset" src="https://github.com/user-attachments/assets/3fc92477-b445-4e88-ac1d-be31229b02d7" />

### A. Project Overview

This project focuses on building an image classification model using Google Teachable Machine to identify different types of plants based on their images. The main goal is to train a machine learning model that can recognize and distinguish various plant species by analyzing their visual features.

To train the model, several categories of plants were created, such as Baby’s Necklace, Calico Kitten, Crassula Corymbulosa, Crassula Pyramidalis, Crassula Alstonii, and Crassula Dejecta. Each category contains around **250 image samples**, which were generated and collected to help the model learn the different shapes, colors, and patterns of each plant. Using many images helps improve the model’s accuracy because it allows the system to see the plants from different angles and conditions.

During the training process, settings like **epochs, batch size, and learning rate** were adjusted to help the model learn more effectively. After the training is completed, the model can test new images using a webcam or uploaded pictures and predict which plant category the image belongs to.

Overall, this project demonstrates how machine learning can be used to create a simple **plant identification system**, showing how artificial intelligence can assist in recognizing plant species for learning, research, and digital plant documentation. 🌱

### B. Plant Species Section
<img width="570" height="570" alt="image" src="https://github.com/user-attachments/assets/75dc678f-1491-4efa-8549-ab581729a80f" />

Baby’s Necklace (Crassula rupestris)

Baby’s Necklace is a small succulent plant known for its unique appearance that resembles a string of tiny beads or a necklace. Its leaves grow in stacked pairs around the stem, forming a compact, decorative pattern. The leaves are usually green but can develop red or pink edges when exposed to bright sunlight. Because of its thick, fleshy leaves, the plant is able to store water, allowing it to survive in dry environments.

This plant belongs to the succulent family and grows slowly, forming short stems that can spread slightly as the plant matures. Due to its attractive shape and color, Baby’s Necklace is commonly grown as an ornamental plant in pots, gardens, and succulent collections.

### C. Model Training Details
<img width="327" height="670" alt="Screenshot 2026-03-11 023228" src="https://github.com/user-attachments/assets/699517b4-6917-45e1-bde8-38cf8d934a5d" />
Number of images per class: 250

### D. Model Evaluation
<img width="350" height="603" alt="Screenshot 2026-03-11 023320" src="https://github.com/user-attachments/assets/04ec3687-4b2c-499d-8fec-fdebecfa7a3c" />

### E. Model Testing
<img width="239" height="1054" alt="sample1" src="https://github.com/user-attachments/assets/cc14df97-15f7-41d1-aabb-2ade5197c726" />
<img width="208" height="1012" alt="sample2" src="https://github.com/user-attachments/assets/b1f06e0c-e309-4e36-92d8-ad482d9a4296" />
<img width="202" height="1000" alt="sample3" src="https://github.com/user-attachments/assets/ddff3165-682e-4bba-a728-0838de298b1b" />
<img width="203" height="1021" alt="sample4" src="https://github.com/user-attachments/assets/043ec8b3-8f15-4494-8358-ca31e1dd9748" />
<img width="206" height="1023" alt="sample5" src="https://github.com/user-attachments/assets/7aa14fc0-ad9c-4dd6-ab95-3d52d81adaf9" />
<img width="212" height="1020" alt="sample6" src="https://github.com/user-attachments/assets/abddb7de-6178-491b-b021-26fb658bc07a" />
<img width="206" height="1003" alt="sample7" src="https://github.com/user-attachments/assets/b2ecb16b-a55b-4c0f-9c35-dd05f73464f0" />
<img width="198" height="1046" alt="sample8" src="https://github.com/user-attachments/assets/641d142d-723c-471b-92c4-098dae2b9736" />
<img width="196" height="1015" alt="sample9" src="https://github.com/user-attachments/assets/5299ddc3-1bcd-4083-9034-562162596dde" />
<img width="196" height="1008" alt="sample10" src="https://github.com/user-attachments/assets/b4d6828e-beb2-48a1-a4f6-90382def7745" />

### REFLECTION QUESTIONS:
1. How did the number of images per class affect your model’s accuracy?
   Having 250 images per class improved the model’s accuracy because it allowed the model to learn more variations of each plant.
2. Which plant species were most commonly misclassified and why?
   Some Crassula species were misclassified because they look very similar in shape, color, and leaf structure.
3. How did changing the epochs, batch size, or learning rate affect the training results?
   Increasing epochs improved learning, batch size affected training speed, and the learning rate controlled how fast the model adjusted.
4. What challenges did you encounter during dataset collection and labeling?
   Collecting enough clear images and labeling plants correctly was challenging because some species look very similar.
5. If you were to improve your model, what specific changes would you make and why?
    The model could be improved by adding more diverse images and using additional data augmentation techniques.

