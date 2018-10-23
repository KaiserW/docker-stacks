# Copyright (c) Jupyter Development Team.
# Distributed under the terms of the Modified BSD License.
FROM ccr.ccs.tencentyun.com/amalthea/tf-notebook:latest

LABEL maintainer="Jizhi.ai"

# Install NBgitpuller
RUN pip install openpyxl && \
    fix-permissions $CONDA_DIR && \
    fix-permissions /home/$NB_USER
