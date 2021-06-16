# Final Project Machine Learning : Kernel Methods (PCA , LDA , Kmeans)
Abstract :Standard PCA only allows linear dimensionality reduction. However, if the data has more complicated structures which cannot be well represented in a linear subspace, standard PCA will not be very helpful. kernel PCA allows us to generalize standard PCA to nonlinear dimensionality reduction.
Similarly,In order to make LDA applicable to nonlinearly structured data, kernel-based methods have been applied. The main idea of kernel-based methods is to map the input data to a feature space by a nonlinear mapping where inner products in the feature space can be computed by a kernel function without knowing the nonlinear mapping explicitly.
Similarly in case of K means ,a major drawback is that it cannot separate clusters that are non-linearly separable in input space. To resolve this issue, kernel k-means is used where, before clustering, points are mapped to a higher-dimensional feature space using nonlinear function, and then kernel k-means partitions the points by linear separators in the new space.
We will study how Kernel PCA , Kernel LDA and Kernel K-means can be used in cases where data cannot be represented in linear subspace and show optimal results in terms of dimensionality reduction and clustering.
In the repository , I have implemented Kernalised methods of PCA , LDA , K-means and have done comaprision with respective standard methods.

1. PCA Vs Kernel PCA :
   Dataset used -Iris Data set , Breast Cancer Data set , Circle Data set 
   For PCA I have used Standard PCA method from sclearn 
   
   Four Types of Kernel functions are used :
   Linear Kernel , Polynomial Kernel , Gaussian Kernel , laplacian Kernel .
   
   Comaprison of PCA vs KPCA (On Iris Data set):
   
   ![PCA on Iris](https://github.com/mishpri0209/MachineLearning_FinalProject_KernelMethods/blob/main/Observations/KPCA_iris/PCA_iris_plt.JPG)
   
   ![PCA on Iris](https://github.com/mishpri0209/MachineLearning_FinalProject_KernelMethods/blob/main/Observations/KPCA_iris/KPCA_iris_gaussian_plt.JPG)

   For checking the classification accuracy and finding confusion matrix we are using SVC classifier after PCA components have been found :
   
   ![AccuracyScore](https://github.com/mishpri0209/MachineLearning_FinalProject_KernelMethods/blob/main/Observations/KPCA_iris/accuracy_Score.JPG)
   
 2. Kernel LDA :
    Data set used : Breast Cancer Data set 
    Number of classes obtained after Kernel LDA =1     
     ![LDA on BCD](https://github.com/mishpri0209/MachineLearning_FinalProject_KernelMethods/blob/main/Observations/KLDA_breast/LDA_Class.JPG)
     Plot of Kernel LDA obtained :
     ![LDA on BCD](https://github.com/mishpri0209/MachineLearning_FinalProject_KernelMethods/blob/main/Observations/KLDA_breast/gaussian.JPG)
    
 4. Kmeans VS Kernel Kmeans 
    Data set used : Wine data set , Iris data set , Swiss Roll Data set , Circle Data set .
    Original Wine Data set :
    ![Wine Data](https://github.com/mishpri0209/MachineLearning_FinalProject_KernelMethods/blob/main/Observations/kmeans/wine_Data.JPG)
    
    Comparision of Kmeans and Kernel Kmeans on Wine Data set :
    Kmeans of Wine data set :
    ![Kmeans_wine](https://github.com/mishpri0209/MachineLearning_FinalProject_KernelMethods/blob/main/Observations/kmeans/wine_kmenas.JPG)
   
   ![Poly_kmeans_Wine](https://github.com/mishpri0209/MachineLearning_FinalProject_KernelMethods/blob/main/Observations/kmeans/wine_poly.JPG)
    
