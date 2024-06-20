ARG version
FROM almalinux:${version}
RUN cat /etc/*release
ARG TRAINER=Sivakumar
ARG Duration=120HRS
ENV Duration=${Duration}
RUN echo "Course is: ${COURSE}, Trainer is: ${TRAINER}, Duration is: ${Duration}"
CMD [ "sleep", "100" ]