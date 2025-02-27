ARG version
FROM almalinux:${version:-9}
ENV course="Devops with AWS" \
    trainer="SivaKumar Reddy" \
    duration="120hrs"
# here username is a key , the value  will be overwritten the some_user with the provided value or else by default it will taken the someuser    
ARG USERNAME="Rajabhushanam yeguru"  
RUN echo "Hello user: ${USERNAME}, image version: ${version} " > /tmp/devops.txt
CMD ["sleep","100"]
