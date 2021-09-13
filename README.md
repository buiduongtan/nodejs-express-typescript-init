Follow intruction from <https://www.freecodecamp.org/news/how-to-enable-es6-and-beyond-syntax-with-node-and-express-68d3e11fe1ab/>

Add new ssh key for external project
add a ~/.ssh/config file with the following contents:

Host github.com
  IdentityFile ~/.ssh/private-key (Not public key, public key is used in github setting)
  IdentitiesOnly yes
