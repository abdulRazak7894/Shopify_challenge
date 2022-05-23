# How to run it replit ?

We need to update the replit node version to 14 as minimum version.

For updating node in replit we can run following command in the shell:
npm init -y && npm i --save-dev node@16 && npm config set prefix=$(pwd)/node_modules/node && export PATH=$(pwd)/node_modules/node/bin:\$PATH

After that install the node packages and run the project with npm run dev

Or

We can configure docker in replit environment and then run project using doocker compose.

# Commands

1. npm init -y && npm i --save-dev node@16 && npm config set prefix=$(pwd)/node_modules/node && export PATH=$(pwd)/node_modules/node/bin:\$PATH
2. npm install
3. npm run dev

# Run the following commands to run the application
