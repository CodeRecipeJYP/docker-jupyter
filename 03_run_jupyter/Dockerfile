FROM 02_install_dependency

VOLUME /notebooks
WORKDIR /notebooks

EXPOSE 8888

CMD ["jupyter", "notebook", "--ip=0.0.0.0", "--no-browser", "--allow-root"]
