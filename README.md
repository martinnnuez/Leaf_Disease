# Leaf Diseases Caused by Fungi and Bacteria Classification

## [Leaf Disease Prediction](https://huggingface.co/spaces/martinnnuez/LeafDisease)

Fungi are the most common parasites causing plant disease. Most are microscopic (very small and can only be seen with the aid of a microscope) plants that feed on living green plants or on dead organic material. When they attack living plants, a disease results. Fungi usually produce spores which, when carried to a plant, can begin an infection. These spores may be carried from plant to plant by wind, water, insects, and equipment. In order for fungus spores to begin new infections, adequate moisture and the right air temperature are required. A plant wound is sometimes also needed as an entry for the fungus. Fungus diseases are common during wet, humid seasons.

Bacteria are single-celled microscopic organisms. Some attack living plants and cause plant disease. Bacteria can be carried from plant to plant by wind, rain splash, insects and machinery.

These diseases occur primarily on leaves, but some may also occur on stems and/or fruit. Leaf diseases are the most common diseases of most plants. They are usually controlled with fungicides, bactericides and resistant varieties. Although leaf diseases are described under several different symptom types, keep in mind that differences are not always clear-cut and there are many names for leaf diseases other than those given, a situation which can be confusing.

#### 1- Leaf Spots
Leaf spots (other names: anthracnose, scab, leaf blotch, shot hole) are usually rather definite spots of varying sizes, shapes and colors. There is nearly always a distinctive margin. Sometimes the spot, which may be caused by bacteria or fungi, is surrounded by a yellow halo. If caused by a fungus, there is nearly always fungus growth of some type in the spot, particularly in damp weather. This fungus growth may be tiny pimple-like structures, often black in color, or a moldy growth of spores. It is often necessary to use a hand lens or a microscope to see these structures. If the spots are numerous or close together, diseased areas may join together to form irregular areas called "blotches." The common names of leaf spot diseases may be general, such as bacterial leaf spot; descriptive, such as frog-eye leaf spot; or named after the fungus, such as Septoria leaf spot.

#### 2- Leaf Blights
Leaf blights are generally larger diseased areas than leaf spots and more irregularly shaped. Sometimes the "blighting" appearance of leaves is the result of the coalescence of numerous small spots. Usually the common name includes the word "blight" such as Southern corn leaf blight or early blight.

#### 3- Rusts
Rusts often produce spots similar to leaf spots, but the spots are called "pustules." Rust pustules are bright yellow, orange-red, reddish-brown or black in color. The pustules are usually raised above the leaf surface, and, when rubbed with a white cloth, a colored deposit the same color as the pustule can usually be seen on the cloth. In severe cases, the leaf withers and dies rapidly. Some types of rust also occur on stems. Rusts are common on grains and grasses.

#### 4- Powdery Mildew
Powdery mildew is a superficial, white to light grayish, powdery to mealy growth on leaves, but may also occur on stems and flowers. Affected leaves usually turn yellow, wither and die rapidly. The problem is common on cucurbit-type vegetables and on small grains.

#### 5- Downy Mildew
Downy mildew symptoms are pale yellow green to yellow areas on the upper leaf surface; light gray to purplish moldy growth on the under surface of the leaf. Blue mold of tobacco is a downy mildew disease. Deformed plant growth ("crazy top") may result from downy mildew as in the case of sorghum downy mildew of corn or grain sorghum.

## Objective:
Build a model able to differentiate the different types of plant diseases. This will facilitate their identification for later treatment.

**Deploy Model as a Web Service on Hugging Face** 
* The model is deployed on Hugging Face Spaces
* Model and artifacts are available for use in the following Hugging Face Space: [Leaf Disease Prediction](https://huggingface.co/spaces/martinnnuez/LeafDisease)

**Model Architecture: ResNet18**
We utilized the powerful ResNet18 architecture for image classification tasks. ResNet18 is known for its depth, which helps capture intricate patterns and features in the leaf images, making it a suitable choice for this classification problem.

**Data Augmentation and Transfer Learning**
To enhance model performance, data augmentation techniques were employed to augment the training dataset. Additionally, transfer learning was applied using pre-trained weights on ImageNet, which significantly accelerated the model training process and improved generalization.

**Results and Performance**
After training the ResNet18 model on the dataset, it achieved an impressive accuracy of over 95% on the test set. This indicates that the model can effectively differentiate between various types of leaf diseases caused by fungi and bacteria.

**Conclusion**
This project demonstrates the applicability of artificial intelligence in solving problems related to the detection of leaf diseases, a field of vital importance in agriculture. The utilization of the ResNet18 architecture, data augmentation, and transfer learning has yielded outstanding results. With this model, accurate and rapid identification of leaf diseases can be achieved, enabling timely treatment and effective management strategies to protect crop health. Good job, ResNet18!
