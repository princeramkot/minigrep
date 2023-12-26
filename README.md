This mini project is a clone of grep command but with limited feature;
you can search any text in given file.

    cargo run -- searchme file.txt
    
    above command will print all the lines container "searchme" word. 

    it works for case insenstive as well for that you have to set a enviorment variable IGNORE_CASE =1. 

    in linux you case run :
    IGNORE_CASE =1 run cargo run -- searchme file.txt