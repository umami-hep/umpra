FROM python:3.8-slim

# Copy the current version of the repo in the image
COPY . /umpra_repo
# Install and remove the folder afterwards
RUN pip install /umpra_repo && rm -rf /umpra_repo
RUN pip install h5py==3.7.0