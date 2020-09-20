--- mining Project ---

 - code hash: 6d3de634753e24ae0f06d6c9f517428c690fe61821110f0959ce875af6bfda2b - 

 - contract update permissions burn: https://bloks.io/account/minedfstoken#keys -

 - How to Build -
   - cd to 'build' directory
   - run the command 'cmake ..'
   - run the command 'make'

 - After build -
   - The built smart contract is under the 'mining' directory in the 'build' directory
   - You can then do a 'set contract' action with 'cleos' and point in to the './build/mining' directory

 - Additions to CMake should be done to the CMakeLists.txt in the './src' directory and not in the top level CMakeLists.txt