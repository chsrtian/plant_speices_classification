# Plant Species Image Classification Using Google Teachable Machine

## A. Project Overview

This project presents a **Supervised Learning multi-class image classification model** designed to identify and classify **20 distinct plant species** from leaf and plant imagery. The model was developed using **Google Teachable Machine**, a web-based tool that enables the creation of machine learning models through an accessible, no-code interface.

The primary objective of this system is to automate the identification of plant species based on visual input. Given a plant image, the trained model predicts the corresponding species class with an associated confidence score. This classification system has practical applications in botanical research, biodiversity monitoring, agricultural diagnostics, and educational settings where rapid and reliable plant identification is required.

The dataset comprises a total of **5,508 images** distributed across 20 plant species classes. Each class contains between 250 and 375 labeled images, ensuring sufficient representation for model training and evaluation. The model was trained, evaluated, and tested entirely within the Google Teachable Machine platform, and subsequently exported for deployment and further analysis.

---

## B. Plant Species

The following section documents each of the 20 plant species classes used in this classification model. For every species, a representative image, the common and scientific names, and a brief academic description are provided.

---

### 1. Barberries

![Barberries](assets/plants/barberries.jpg)

- **Common Name:** Barberries
- **Scientific Name:** *Berberis vulgaris*
- **Description:** Barberries are deciduous or evergreen shrubs belonging to the family Berberidaceae. They are characterized by their thorny branches, oblong leaves, and clusters of small yellow flowers that develop into elongated red berries. Barberries are widely distributed across temperate and subtropical regions and are often cultivated for ornamental, culinary, and medicinal purposes.

---

### 2. Magnolia

![Magnolia](assets/plants/magnolia.jpg)

- **Common Name:** Magnolia
- **Scientific Name:** *Magnolia grandiflora*
- **Description:** Magnolia is a genus of flowering plants in the family Magnoliaceae, recognized for their large, fragrant blossoms and broad, glossy leaves. These trees and shrubs are among the earliest known flowering plants, with fossil records dating back over 95 million years. Magnolias are commonly planted as ornamental trees in parks and gardens due to their aesthetic appeal and resilience.

---

### 3. Rubus

![Rubus](assets/plants/rubus.jpg)

- **Common Name:** Rubus (Bramble)
- **Scientific Name:** *Rubus fruticosus*
- **Description:** Rubus is a large and diverse genus within the family Rosaceae, encompassing species commonly known as brambles, blackberries, and raspberries. These perennial plants are typically characterized by their thorny or prickly stems, compound leaves, and aggregate fruit. Rubus species are found across a wide range of habitats and are valued both ecologically and commercially for their edible fruit.

---

### 4. Forsythia

![Forsythia](assets/plants/forsythia.jpg)

- **Common Name:** Forsythia
- **Scientific Name:** *Forsythia suspensa*
- **Description:** Forsythia is a genus of deciduous shrubs in the family Oleaceae, native to Eastern Asia and Southeastern Europe. They are among the first plants to bloom in early spring, producing bright yellow flowers along their arching branches before the emergence of leaves. Forsythia is widely used in landscape design and has a history of use in traditional medicine.

---

### 5. Weigela

![Weigela](assets/plants/weigela.jpg)

- **Common Name:** Weigela
- **Scientific Name:** *Weigela florida*
- **Description:** Weigela is a genus of deciduous shrubs in the family Caprifoliaceae, native to East Asia. The plant is best known for its profusion of funnel-shaped flowers, which range in color from white and pink to deep red. Weigela thrives in well-drained soil and full sunlight, making it a popular choice for ornamental gardening and pollinator-friendly landscapes.

---

### 6. Vaccinium

![Vaccinium](assets/plants/vaccinium.jpg)

- **Common Name:** Vaccinium (Blueberry / Cranberry)
- **Scientific Name:** *Vaccinium* spp.
- **Description:** Vaccinium is a genus of shrubs in the heath family Ericaceae, which includes blueberries, cranberries, bilberries, and huckleberries. These plants are typically found in acidic, nutrient-poor soils and produce small, round berries rich in antioxidants. Vaccinium species hold significant economic importance in agriculture and are extensively studied for their nutritional and health-promoting properties.

---

### 7. Hibiscus Syriacus

![Hibiscus Syriacus](assets/plants/hibiscus_syriacus.jpg)

- **Common Name:** Rose of Sharon
- **Scientific Name:** *Hibiscus syriacus*
- **Description:** Hibiscus syriacus, commonly known as Rose of Sharon, is a deciduous flowering shrub in the family Malvaceae. It is native to East Asia and is widely cultivated in temperate regions for its large, showy flowers that bloom in late summer. The plant is valued for its hardiness, drought tolerance, and its role as a late-season nectar source for pollinators.

---

### 8. Fuchsia

![Fuchsia](assets/plants/fuchsia.jpg)

- **Common Name:** Fuchsia
- **Scientific Name:** *Fuchsia magellanica*
- **Description:** Fuchsia is a genus of flowering plants in the family Onagraceae, comprising over 100 species of shrubs and small trees. They are distinguished by their pendulous, tubular flowers with vivid combinations of red, pink, purple, and white. Fuchsia species are predominantly native to Central and South America and are widely grown as ornamental plants in gardens and hanging baskets.

---

### 9. Genista

![Genista](assets/plants/genista.jpg)

- **Common Name:** Genista (Broom)
- **Scientific Name:** *Genista tinctoria*
- **Description:** Genista is a genus of leguminous shrubs in the family Fabaceae, commonly referred to as brooms. These plants produce dense clusters of bright yellow, pea-like flowers and are adapted to dry, nutrient-poor soils. Genista species play an important ecological role in nitrogen fixation and soil stabilization, and several species have historical significance as sources of natural dyes.

---

### 10. Aronia Melanocarpa

![Aronia Melanocarpa](assets/plants/aronia_melanocarpa.jpg)

- **Common Name:** Black Chokeberry
- **Scientific Name:** *Aronia melanocarpa*
- **Description:** Aronia melanocarpa, commonly known as black chokeberry, is a deciduous shrub in the family Rosaceae native to eastern North America. It produces clusters of small white flowers followed by dark purple-black berries that are notably high in anthocyanins and antioxidants. The plant has gained attention in recent years as a functional food crop and is also utilized in landscaping for its attractive fall foliage.

---

### 11. Itea

![Itea](assets/plants/itea.jpg)

- **Common Name:** Itea (Sweetspire)
- **Scientific Name:** *Itea virginica*
- **Description:** Itea is a genus of shrubs and small trees in the family Iteaceae. The most commonly cultivated species, Itea virginica (Virginia sweetspire), is native to the eastern United States and is recognized for its fragrant, drooping racemes of white flowers and its vibrant red-purple autumn foliage. Itea species are valued in landscape architecture for their adaptability to wet soils and shaded environments.

---

### 12. Actinidia

![Actinidia](assets/plants/actinidia.jpg)

- **Common Name:** Actinidia (Kiwifruit vine)
- **Scientific Name:** *Actinidia deliciosa*
- **Description:** Actinidia is a genus of woody, climbing vines in the family Actinidiaceae, most widely known for Actinidia deliciosa, the source of the common kiwifruit. The plants are native to East Asia and are characterized by their large, heart-shaped leaves and small, fragrant flowers. Actinidia species are of significant commercial value in the global fruit industry and are also studied for their phytochemical properties.

---

### 13. Pistacia

![Pistacia](assets/plants/pistacia.jpg)

- **Common Name:** Pistacia (Pistachio)
- **Scientific Name:** *Pistacia vera*
- **Description:** Pistacia is a genus of trees and shrubs in the family Anacardiaceae, native to Central Asia and the Mediterranean region. The genus includes Pistacia vera, the commercially important pistachio nut tree, as well as several species used for resin production and as rootstocks. Pistacia species are drought-tolerant and adapted to arid and semi-arid climates, making them ecologically and economically significant in their native range.

---

### 14. Abelia

![Abelia](assets/plants/abelia.jpg)

- **Common Name:** Abelia
- **Scientific Name:** *Abelia x grandiflora*
- **Description:** Abelia is a genus of flowering shrubs in the family Linnaeaceae, widely cultivated as ornamental plants in temperate and subtropical gardens. The most commonly grown species, Abelia x grandiflora, produces clusters of small, tubular, fragrant flowers that bloom from late spring through autumn. Abelia is prized for its extended flowering season, semi-evergreen foliage, and its ability to attract butterflies and hummingbirds.

---

### 15. Hedera

![Hedera](assets/plants/hedera.jpg)

- **Common Name:** Hedera (Ivy)
- **Scientific Name:** *Hedera helix*
- **Description:** Hedera is a genus of evergreen climbing or ground-creeping woody plants in the family Araliaceae. Hedera helix, commonly known as English ivy, is the most widely recognized species and is notable for its distinctive lobed leaves and its ability to adhere to vertical surfaces using aerial rootlets. While widely used in landscaping and as ground cover, Hedera species can become invasive in certain ecosystems and require careful management.

---

### 16. Calluna

![Calluna](assets/plants/calluna.jpg)

- **Common Name:** Calluna (Heather)
- **Scientific Name:** *Calluna vulgaris*
- **Description:** Calluna vulgaris, commonly known as heather or ling, is the sole species in the genus Calluna within the family Ericaceae. It is an evergreen, low-growing shrub native to Europe, Asia Minor, and North Africa, typically found in acidic heathlands, moorlands, and bogs. Calluna is ecologically important as a dominant species in heathland habitats and is also cultivated commercially for its ornamental value and its role in honey production.

---

### 17. Ephedra

![Ephedra](assets/plants/ephedra.jpg)

- **Common Name:** Ephedra (Joint Fir)
- **Scientific Name:** *Ephedra sinica*
- **Description:** Ephedra is a genus of gymnosperm shrubs in the family Ephedraceae, distributed across arid and semi-arid regions worldwide. The plants are characterized by their jointed, photosynthetic stems, scale-like leaves, and cone-like reproductive structures. Ephedra has a long history of use in traditional medicine, particularly in East Asia, where extracts from Ephedra sinica (ma huang) have been used for their bronchodilatory and stimulant properties.

---

### 18. Lapageria

![Lapageria](assets/plants/lapageria.jpg)

- **Common Name:** Lapageria (Chilean Bellflower)
- **Scientific Name:** *Lapageria rosea*
- **Description:** Lapageria rosea is the sole species in the genus Lapageria, belonging to the family Philesiaceae. It is the national flower of Chile and is a climbing plant renowned for its large, waxy, bell-shaped flowers that are typically deep pink to crimson in color. Lapageria is native to the temperate rainforests of southern Chile and Argentina and is cultivated as a prized ornamental in suitably mild and humid climates.

---

### 19. Pieris

![Pieris](assets/plants/pieris.jpg)

- **Common Name:** Pieris (Andromeda)
- **Scientific Name:** *Pieris japonica*
- **Description:** Pieris is a genus of evergreen shrubs in the family Ericaceae, native to eastern and southern Asia and eastern North America. Pieris japonica is the most commonly cultivated species, admired for its cascading clusters of bell-shaped white or pink flowers and its colorful new foliage, which emerges in shades of red and bronze. The genus thrives in acidic, well-drained soils and is a staple in woodland and shade garden plantings.

---

### 20. Callistemon

![Callistemon](assets/plants/callistemon.jpg)

- **Common Name:** Callistemon (Bottlebrush)
- **Scientific Name:** *Callistemon citrinus*
- **Description:** Callistemon is a genus of shrubs and small trees in the family Myrtaceae, native to Australia. The genus derives its common name, bottlebrush, from its distinctive cylindrical flower spikes composed of numerous stamens, typically vivid red in color. Callistemon species are drought-tolerant, attract nectar-feeding birds and insects, and are widely planted in warm-climate regions as ornamental and street trees.

---

## C. Model Training Details

The classification model was trained using **Google Teachable Machine**, a browser-based machine learning platform developed by Google. The training process involved uploading labeled image datasets for each of the 20 plant species classes and configuring the model's hyperparameters prior to training.

### Training Hyperparameters

| Parameter       | Value         |
|-----------------|---------------|
| Epochs          | *[To be specified]* |
| Batch Size      | *[To be specified]* |
| Learning Rate   | *[To be specified]* |

### Dataset Distribution

The dataset used for training consists of a total of **5,508 images** distributed across 20 classes. The table below presents the number of images per class.

| No. | Plant Species         | Number of Images |
|-----|-----------------------|------------------|
| 1   | Barberries            | 256              |
| 2   | Magnolia              | 250              |
| 3   | Rubus                 | 275              |
| 4   | Forsythia             | 277              |
| 5   | Weigela               | 309              |
| 6   | Vaccinium             | 358              |
| 7   | Hibiscus Syriacus     | 375              |
| 8   | Fuchsia               | 259              |
| 9   | Genista               | 251              |
| 10  | Aronia Melanocarpa    | 284              |
| 11  | Itea                  | 257              |
| 12  | Actinidia             | 250              |
| 13  | Pistacia              | 302              |
| 14  | Abelia                | 250              |
| 15  | Hedera                | 263              |
| 16  | Calluna               | 266              |
| 17  | Ephedra               | 250              |
| 18  | Lapageria             | 250              |
| 19  | Pieris                | 287              |
| 20  | Callistemon           | 291              |
|     | **Total**             | **5,508**        |

---

## D. Model Evaluation

The trained model was evaluated using standard classification metrics to assess its performance across all 20 plant species classes. The following evaluation visualizations provide insight into the model's predictive accuracy and error distribution.

### Confusion Matrix

![Confusion Matrix](assets/evaluation/confusion_matrix.png)

The confusion matrix provides a detailed breakdown of the model's predictions versus the actual labels for each class. Each cell in the matrix represents the number of instances where the model predicted a specific class for a given true class. Diagonal values indicate correct predictions, while off-diagonal values represent misclassifications. This visualization is essential for identifying which classes the model confuses most frequently, thereby guiding potential improvements in data collection or model tuning.

### Accuracy Per Class

![Accuracy Per Class](assets/evaluation/accuracy_per_class.png)

The accuracy per class chart illustrates the classification accuracy achieved for each individual plant species. This metric reveals how consistently the model identifies each class and highlights species that may require additional training samples or image quality improvements. Variations in per-class accuracy may be attributed to factors such as visual similarity between species, inconsistent image quality, or imbalanced class representation in the training dataset.

### Overall Model Accuracy

![Overall Model Accuracy](assets/evaluation/overall_accuracy.png)

The overall model accuracy represents the proportion of correct predictions out of the total number of predictions made across all classes. This metric provides a high-level summary of the model's general performance. While overall accuracy is a useful aggregate measure, it should be interpreted alongside per-class accuracy and the confusion matrix to obtain a comprehensive understanding of model behavior, particularly in multi-class classification tasks where class imbalance may exist.

---

## E. Model Testing

The following section documents 10 test cases conducted to validate the model's real-world prediction capability. Each test case includes the input image provided to the model and a screenshot of the model's prediction output, including the predicted class and associated confidence percentage.

---

### Test Case 1 – Barberries

**Input Image:**

![Test 1 Input](assets/testing/test1_input.png)

**Model Prediction:**

![Test 1 Prediction](assets/testing/test1_prediction.png)

---

### Test Case 2 – Magnolia

**Input Image:**

![Test 2 Input](assets/testing/test2_input.png)

**Model Prediction:**

![Test 2 Prediction](assets/testing/test2_prediction.png)

---

### Test Case 3 – Rubus

**Input Image:**

![Test 3 Input](assets/testing/test3_input.png)

**Model Prediction:**

![Test 3 Prediction](assets/testing/test3_prediction.png)

---

### Test Case 4 – Forsythia

**Input Image:**

![Test 4 Input](assets/testing/test4_input.png)

**Model Prediction:**

![Test 4 Prediction](assets/testing/test4_prediction.png)

---

### Test Case 5 – Weigela

**Input Image:**

![Test 5 Input](assets/testing/test5_input.png)

**Model Prediction:**

![Test 5 Prediction](assets/testing/test5_prediction.png)

---

### Test Case 6 – Vaccinium

**Input Image:**

![Test 6 Input](assets/testing/test6_input.png)

**Model Prediction:**

![Test 6 Prediction](assets/testing/test6_prediction.png)

---

### Test Case 7 – Hibiscus Syriacus

**Input Image:**

![Test 7 Input](assets/testing/test7_input.png)

**Model Prediction:**

![Test 7 Prediction](assets/testing/test7_prediction.png)

---

### Test Case 8 – Fuchsia

**Input Image:**

![Test 8 Input](assets/testing/test8_input.png)

**Model Prediction:**

![Test 8 Prediction](assets/testing/test8_prediction.png)

---

### Test Case 9 – Genista

**Input Image:**

![Test 9 Input](assets/testing/test9_input.png)

**Model Prediction:**

![Test 9 Prediction](assets/testing/test9_prediction.png)

---

### Test Case 10 – Aronia Melanocarpa

**Input Image:**

![Test 10 Input](assets/testing/test10_input.png)

**Model Prediction:**

![Test 10 Prediction](assets/testing/test10_prediction.png)

---

## F. Repository Contents

The following is a summary of the files and directories contained within this repository.

| File / Directory                  | Description                                                              |
|-----------------------------------|--------------------------------------------------------------------------|
| `README.md`                       | Project documentation and overview (this file)                           |
| `model/`                          | Exported Teachable Machine model files (model.json, weights, metadata)   |
| `assets/plants/`                  | Representative images for each of the 20 plant species classes           |
| `assets/evaluation/`             | Model evaluation visualizations (confusion matrix, accuracy charts)      |
| `assets/testing/`                | Test case input images and prediction output screenshots                 |
| `screenshots/`                    | Additional screenshots of the training process and dataset configuration |

---

*This project was developed as part of a university coursework requirement. The classification model was built and trained using [Google Teachable Machine](https://teachablemachine.withgoogle.com/).*
