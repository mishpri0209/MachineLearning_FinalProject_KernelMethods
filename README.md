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
