FROM node:22.19.0

# set working dir for the app it can be any name
WORKDIR /intresting_fact_country

COPY package*.json .

# Install dependencies
RUN npm install

# copy all the files and dir to working dir
COPY . .

EXPOSE 5173

# RUN executes commands while building the image
# CMD executes commands when the container starts
CMD ["npm", "run", "dev"]