FROM 02_install_dependency

# VOLUME /workspace
RUN git clone https://github.com/CodeRecipeJYP/tensorboard
WORKDIR /tensorboard

ADD https://trello-attachments.s3.amazonaws.com/58d8e46f3932af08817b04fd/59dd8196c14ca71a19dfca96/a65389e7d21e0cb66d253afb912f1302/ftp_account.py download/

CMD python3 styletransfer_app.py