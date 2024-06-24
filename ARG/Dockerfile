ARG version
FROM almalinux:${version:-8}
#RUN cat/etc/*release
ARG course=docker
ARG LEARNER=vikram
ARG Duration=20hrs
ENV Duration=${Duration}
RUN echo "Course is: ${course},LEARNER is : ${LEARNER},Duration is : ${Duration}"
CMD [ "sleep","60" ]
