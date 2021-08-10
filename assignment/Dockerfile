FROM node:14
RUN apt-get update && apt-get install -y \
  nano \
  vim
# Set the working directory to /code
WORKDIR /code

# Bundle app source
COPY . /code
