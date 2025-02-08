FROM nvidia/cuda:12.3.2-cudnn9-runtime-ubuntu22.04
WORKDIR /root
RUN apt-get update -y && apt-get install -y python3-pip
COPY infer.py jfk.flac ./
RUN pip3 install unhallucinated-faster-whisper
CMD ["python3", "infer.py"]
