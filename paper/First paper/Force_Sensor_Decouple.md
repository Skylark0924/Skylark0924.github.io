## Decouple

### [A Robust Static Decoupling Algorithm for 3-Axis Force Sensors Based on Coupling Error Model and $\epsilon$-SVR](.\reference\sensors-12-14537.pdf)

> Instead of regarding the whole system as a black box in conventional algorithm, the coupling error model is designed by the principle of coupling errors, in which the nonlinear relationships between forces and coupling errors in each dimension are calculated separately. Six separate **Support Vector Regressions (SVRs)** are employed for their ability to perform adaptive, nonlinear data ﬁtting. 

#### Linear  Static Decoupling

1.  **Least Square Method (LSM)**: This algorithm is based on the assumption that relationships between input forces and output voltages in all dimensions are linear.
2. **Shape from motion**: which the motion of the force vector and the calibration matrix are simultaneously extracted by singular value decomposition from raw sensor signals. 
3. **NN for linear static decouple**:  to increase the accuracy of decoupling.

#### Nonlinear Static Decoupling

1.  **NN with back propagation (BP)**: to realize the nonlinear Multiple Input Multiple Output (MIMO) mapping of a multi-axis force sensor.
2. **Radial basis function (RBF) NN** : Engineering applications show that decoupling algorithms with a standard NN model can sometimes reduce coupling error signiﬁcantly , but sometimes generate worse results than without decoupling due to overﬁtting. [径向基函数神经网络在多维力传感器标定中的应用](./reference/径向基函数神经网络在多维力传感器标定中的应用_俞阿龙.pdf)
3. **Support Vector Machine (SVM)**:  SVM starts from solving problems of classiﬁcation. With the introduction of Vapnik’s $\epsilon​$ -insensitive loss function, it also extends to be a regression prediction tool that uses machine learning theory to maximize predictive accuracy while not subject to local minimal and overﬁtting.
4. **Support Vector Regression(SVR)**: The proposed coupling error model consists of six SVRs and three linear ﬁtting functions, which is more conformable to calibration data structure. 





### [Decoupling Strategy of Multi-dimensional Force Sensor Based on LS-SVM and $\alpha$th-order Inverse System Method](.\reference\untitled.pdf)

1. 最小二乘支持向量机
2. As one kind of Support Vector Machine, LS-SVM algorithm’s loss function is quadratic term of error.





## Incremental Learning

### Paper

1. Kuncheva提出了对增量学习的普遍接受的定义([Learn++: An incremental learning algorithm for supervised neural networks](./reference/10.1.1.16.1297.pdf))

   - 可以学习新的信息中的有用信息

   - 不需要访问已经用于训练分类器的原始数据

   - 对已经学习的知识具有记忆功能(避免灾难性遗忘)

   - 在面对新数据中包含的新类别时，可以有效地进行处理

     ![1555587160280](1555587160280.png)

2. 将增量学习应用到不同领域

   - [Incremental learning for robust visual tracking](./reference/Incremental_learning_for_robust_visual_t.pdf)
   - [Incremental learning with support vector machines](./reference/10.1.1.95.8001.pdf)