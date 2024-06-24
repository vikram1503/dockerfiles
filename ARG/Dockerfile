ARG version
FROM almalinux:${version:-8}
#RUN cat/etc/*release
ARG ${course:-docker}
ARG ${LEARNER:-vikram}
RUN echo "Course is: ${course},LEARNER is : ${LEARNER}"
CMD [ "sleep","60" ]
