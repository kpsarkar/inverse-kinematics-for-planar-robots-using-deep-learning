![License: Non-Commercial](https://img.shields.io/badge/License-Non--Commercial-red.svg)
![License: Commercial](https://img.shields.io/badge/License-Commercial-blue.svg)

# Inverse-kinematics-for-planar-robots-using-deep-learning
The project showcases how Deep Learning can be used to Train and Test a Inverse-Kinematic Model that can predict the Joint Angles of a Planar Robot given the end effector positions.
The project starts by demonstrating how to carry out work space analysis of a robot.
The project then teaches how to create a Data Set for training a Inverse-Kinematic Prediction Model.
The project then fianlly shows how training, testing and evaluation of the model is to be carried out

## The Code
First- Run the python file "Code for Work Space Analysis of 2R Manipulator.py" for to visualise the work space of a 2R Robot, for which we will be training the model.

Second- Run the python file "Code Formulation of dataset.py" to create the necessary dataset corresponding to the same work space. A copy of the output dataset created in this set has been already uploaded as "mydataset2.csv"

Third- Run the python file "Code for ANN Model Training for Inverse Kinematic Solutoion.py", ensure to edit the file path of the dataset in the code before running.

## Note
The Model can be further optimised to reduce the loss and give better accuracy.

## 📜 License

This project is **dual‑licensed**:

| Use case                       | License file                         |
|--------------------------------|--------------------------------------|
| 🔒 Free, non‑commercial, no modifications | `Non-Commercial_LICENSE.txt`         |
| 💼 Commercial use (with rights to modify & redistribute) | `LICENSE.txt`            |

- **Non‑Commercial** users may use and redistribute the unmodified code at no cost, under the terms in [Non‑Commercial_LICENSE](https://github.com/kpsarkar/inverse-kinematics-for-planar-robots-using-deep-learning/blob/main/Non-Commercial_LICENSE).  
- **Commercial** users wishing to integrate, modify, or redistribute this code in a product or service **must** obtain a commercial license—see [LICENSE.txt](https://github.com/kpsarkar/inverse-kinematics-for-planar-robots-using-deep-learning/blob/main/LICENSE) or email kumarprasenjeetsarkar@gmail.com.

