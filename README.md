# To_OZ_Using_Command-Line

## Requirements
Work through the following prompts:

NOTE: When it asks you to create a file (not directories), make them .txt file-types!

### Setup
1. Create directory House/
`mkdir House`
2. Add files: Dorothy and Toto to House/
`cd House`
`touch Dorothy.txt Toto.txt`

3. Create directory Oz/
`mkdir Oz`

4. Add files for the 4 Witches to Oz/...
`cd Oz`
`touch Good_Witch_of_the_North.txt Wicked_Witch_of_the_East.txt  Good_Witch_of_the_South.txt  Wicked_Witch_of_the_West.txt `
  - Good_Witch_of_the_North
  - Wicked_Witch_of_the_East
  - Good_Witch_of_the_South
  - Wicked_Witch_of_the_West



### Ding! Dong! The Witch is Dead
1. Delete: Wicked_Witch_of_the_East
`rm Wicked_Witch_of_the_West.txt`
2. Move Dorothy from House/ to Oz/
`mv House/Dorothy.txt Oz`

### Follow the Yellow Brick Road
In the directory Oz/...
1. Add file for Scarecrow
`touch Scarecrow.txt`
2. Add file for Tin_Man
`touch Tin_Man.txt`
3. Add file for Cowardly_Lion
`touch Cowardly_Lion.txt`
4. Create directory Emerald_City/
`mkdir Emerald_City/`
5. Move 'the gang' to Emerald_City/
`mv Scarecrow.txt Tin_Man.txt Cowardly_Lion.txt Emerald_city`
### You Must Kill the Witch

1. Add Flying_Monkeys to Oz/
`cd Oz`
`touch Flying_Monkeys.txt`

2. Remove Wicked_Witch_of_the_West
`rm Wicked_Witch_of_the_West.txt `
3. Give the gifts*
  - Give Scarecrow a "diploma"
  `echo "diploma" > Scarecrow.txt`
  - Give Tin_Man a "heart shaped watch"
  `echo "heart shaped watch"  > Tin_Man`
  - Give Cowardly_Lion a "medal"
`echo "medal"  > Cowardly_Lion`
*To give gifts, echo the gift name into the appropriate file. Hint: google "how to redirect output of echo to a file"


