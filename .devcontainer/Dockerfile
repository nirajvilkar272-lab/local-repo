FROM ros:humble

RUN apt-get update && apt-get install -y \
    python3-colcon-common-extensions \
    python3-rosdep \
    git \
    nano \
    vim \
    && rm -rf /var/lib/apt/lists/*

RUN rosdep init || true
