import numpy as np
arr = np.genfromtxt('data.csv', delimiter=';', skip_header=0)
arr2 = np.eye(arr.shape[0])
multiplication = np.matmul(arr, arr2)
np.savetxt('data1.csv', multiplication, delimiter=',')
