# Stage-1 & spacify a name 'builder'
FROM  node:latest 

# Create a directory  and go to directory 
WORKDIR /app

# Copy the package.json file to my current directory for install necessary dependence  
COPY package.json .

# Install the dependence
RUN npm install

COPY . .


CMD ["npm", "start"]
EXPOSE 3000