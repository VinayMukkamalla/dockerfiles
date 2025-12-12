ARG VERSION
FROM almalinux:${VERSION:-9}
ARG TOOL="Docker" \
    INSTRUCTION="ARG" \
    USE="ARGUMENT and scope only IMAGE BUILD level"

ENV TOOL=${TOOL}
RUN echo "TOOL: ${TOOL}, INSTRUCTION: ${INSTRUCTION}, version: ${VERSION}"

CMD ["sleep", "500"]
