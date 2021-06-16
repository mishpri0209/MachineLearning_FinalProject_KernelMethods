# MachineLearning_FinalProject_KernelMethods
Final Project ML-Kernel Methods - PCA , LDA , Kmeans

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
    
