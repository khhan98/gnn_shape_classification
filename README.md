# gnn_shape_classification
GNN-based shape classification from 3D point cloud processing

My ongoing personal project utilizing graph neural network to classify 3D objects from point cloud. Emerging AI applications like autonomous driving, augmented reality and robotics utilize 3D data. Representing 3D data as point cloud is popular as it takes account for sparsity of 3D objects. However, point cloud is different than pixel or voxel in that point cloud is continuous space. Thus, conventional convolution neural network models does not work. The project aims to apply graph neural network to 3d point cloud data for 3d object classification. 

I implemented point transformer according to the original paper. And train the model on the ShapeNet dataset with 16 classes. The trained model yielded ovrall accuracy 0.96 and average class-wide accuracy 0.92 on validation dataset.
