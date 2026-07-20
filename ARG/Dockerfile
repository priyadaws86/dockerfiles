ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="Docker" \
    TRAINER="Siva" \
    DURATION="10HRS"
ENV COURSE=${COURSE}
RUN echo "Trainer ${TRAINER}, Course ${COURSE}, Version: ${VERSION}"
CMD ["sleep", "1000"]

