#================================================================================
#
#    hcdiag/samples/makefile
#
#  © Copyright IBM Corporation 2015,2016. All Rights Reserved
#
#    This program is licensed under the terms of the Eclipse Public License
#    v1.0 as published by the Eclipse Foundation and available at
#    http://www.eclipse.org/legal/epl-v10.html
#
#    U.S. Government Users Restricted Rights:  Use, duplication or disclosure
#    restricted by GSA ADP Schedule Contract with IBM Corp.
#
#================================================================================

gpu-health : gpu-health.cu
	 nvcc -gencode arch=compute_70,code=sm_70 -O3   --compiler-options "-O3 -fopenmp" gpu-health.cu -o gpu-health -lcublas
clean :
	rm -f gpu-health
