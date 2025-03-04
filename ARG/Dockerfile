ARG version
FROM almalinux:${version:-9}
ENV course="DevOps with AWS" \
    trainer="ayesha" \
    duration="120hrs"
    #here user1 is key,someuser is default value
    # ARG user1=someuser
    ARG  USERNAME=ayesha
    RUN echo "Hello User: ${USERNAME}, image version: ${version}"  > /tmp/devops.txt
    CMD ["sleep", "100"]