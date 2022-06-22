# The product of this Dockerfile has been pushed to:
# lfponcen/b_repo_space:0.1.0

ARG base_image="lfponcen/a_repo_space:0.1.0"
FROM "$base_image"

ARG DEBIAN_FRONTEND=noninteractive

RUN sed 's/A/B/' /opt/string_file > /opt/string_fileb; \
    rm /opt/string_file
CMD cat /opt/string_fileb; \
    echo "\nFor more information go to: \nhttps://github.com/luisfponce/iblodr"
