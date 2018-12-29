# buzz_swarming
Contains basic swarm behaviors coded in Buzz programming language

#### Compiling the Buzz File: ####
bzzc <file_name_with_extension>

#### To run the argos file: ####
argos3 -c <argos_file_name_with_extension>

#### To make changes to the number of bots: ####
1. Buzz File: A constant NO_OF_ROBOTS is defined at the top
2. Argos File: Change the "quantity" attribute of the "entity" tag within the "distribute" tag (within the "arena" tag)

Make sure the number of bots in both the files are equal.

#### NOTE: If the path to your Buzz libraries is different, please make the corresponding changes in the include statement ####


#### For more details, please go through the StartUp_Guide Document ####
