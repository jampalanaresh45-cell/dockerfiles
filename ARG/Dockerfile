ARG VERSION
FROM almalinux:${VERSION:-9}
ARG course="Devops" \
    Trainer="sivakumar" \
    Joinee="Naresh" \
    Duration="10HRS"
ENV Joinee=${Joinee}
RUN echo "NewJoinee ${Joinee}, trainer: ${Trainer}, version ${VERSION}"
CMD ["sleep", "1000"]