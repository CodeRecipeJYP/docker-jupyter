
docker build -t 00_install_python 00_install_python/
docker build -t 01_install_jupyter 01_install_jupyter/
docker build -t 02_install_dependency 02_install_dependency/
docker build -t 03_run_jupyter 03_run_jupyter/

docker run -it -p 8888:8888 03_run_jupyter