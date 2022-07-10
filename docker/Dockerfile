FROM cyqian/orb-slam2:0
ENV DEBIAN_FRONTEND=noninteractive


# Overwrite the entry point to zsh
COPY ./ros_entrypoint.zsh /
ENTRYPOINT ["/ros_entrypoint.zsh"]
WORKDIR /home/SLAM
CMD ["zsh"]