# WheatClassification
This project uses **Mask R-CNN** for instance segmentation of wheat heads, trained on labeled datasets, to improve wheat monitoring and sorting.

The purpose of this project is to improve how industrial machines sort wheat by using **image segmentation models**. Conventionally, physical processes like *gravity separators* and *optical sorters* are used to remove unwanted materials like stones and dirt, but these methods can be slower and less precise. By applying **Mask R-CNN**, we can predict and separate out impurities faster and more accurately, preventing machine damage and improving the sorting process overall. 
This offers a better, more scalable solution compared to traditional methods.

## Process: 
1. Created a training dataset for wheat seeds with a mix of wheat, rice, and stones (kept sizes consistent with real-world scenarios).
2. Kept the training dataset straightforward but added noise like *soil and other materials* in the testing dataset to simulate real-world conditions.
3. Trained the Mask R-CNN model to distinguish between wheat, rice, and stones.
4. Achieved **99% accuracy with minimal loss**.
