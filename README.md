

<br>
docker build -t 00_install_python 00_install_python/
<br>
docker build -t 01_install_jupyter 01_install_jupyter/
<br>
docker build -t 02_install_dependency 02_install_dependency/
<br>
docker build -t 03_run_jupyter 03_run_jupyter/
docker build --no-cache -t 03_2_run_tensorflow 03_2_run_tensorflow/
<br>
<br>
docker run -it -p 8888:8888 03_run_jupyter
docker run -it 03_2_run_tensorflow
