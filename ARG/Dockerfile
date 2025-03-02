FROM almalinux:9
ENV course="DevOps with AWS" \
    trainer="ayesha" \
    duration="120hrs"
    #here user1 is key,someuser is default value
    # ARG user1=someuser
    ARG  ${username:-some_user}
    RUN echo "Hello ${username}" > /tmp/devops.txt
    CMD ["sleep", "100"]