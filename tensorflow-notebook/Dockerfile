# Copyright (c) Jupyter Development Team.
# Distributed under the terms of the Modified BSD License.
FROM jupyter/tensorflow-notebook

LABEL maintainer="Jizhi.ai"

# Install NBgitpuller
RUN pip install nbgitpuller && \
    conda install --quiet --yes \
    -c conda-forge ipywidgets beakerx && \
    fix-permissions $CONDA_DIR && \
    fix-permissions /home/$NB_USER
