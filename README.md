# Machine Learning Docker Environment

MLDS docker environment for machine learning with GPU support.

# How to use

Follow the steps and turn an empty instance to a ready-to-go deep learning environment in 30 mins.

* **0-prepare-host.sh**   
  install docker, nvidia driver, nvidia-docker in your host machine.
  
* **1-build-mldm.sh**  
  build my machine learning toolbelt container  
  here I choose **tensorflow gpu supported version** for deep learning, you may append whatever you like in Dockerfile!
  
* **2-start-mldm.sh**  
  start the container with some environment setup script, with ipython notebook in http://<your_machine>:8888