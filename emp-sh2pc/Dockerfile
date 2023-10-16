FROM python:bookworm
RUN apt-get update \
  && apt-get install -y wget
RUN wget https://raw.githubusercontent.com/emp-toolkit/emp-readme/master/scripts/install.py
RUN apt-get install -y cmake 
RUN python install.py --deps --tool --ot --sh2pc