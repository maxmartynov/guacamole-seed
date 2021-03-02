FROM accetto/ubuntu-vnc-xfce-g3

USER root
RUN apt-get update -qq && apt-get install -qq -y blender
RUN echo ls ~
COPY ./Blender.desktop /Blender.desktop
RUN chmod +x /Blender.desktop
RUN mv /Blender.desktop ~/Desktop/Blender.desktop

USER headless
