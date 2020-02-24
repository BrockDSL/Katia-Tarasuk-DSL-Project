![DSL Logo](dsl_logo.png)


# Katia's Project on Collection Builder
![Cat Photo Metadata](https://124135-361502-raikfcquaxqncofqfm.stackpathdns.com/asset/img/banners/kb/data-glossary/metadata.png)
 
## Introduction
Collection Builder is a lightweight digital tool that creates exhibits with metadata support through Github. It was created and is maintained by librarians from the University of Idaho to aid librarians and others in visualizing metadata and browsing through metadata rich collections.

It is very similar to Omeka S in that it creates exhibits surrounding metadata. However if one could say that Omeka S runs along a dimension of few objects with a great deal of metadata, then one could also say that Collection Builder runs along a separate dimension of more objects bound together by a csv file with metadata, and allows for visualization of connections between the objects.

Collection Builder Test for the Brock DSL: https://kat-a-t.github.io/Brock_DSL_CollectionBuilder/

### Project Process
1) Found a collection with multiple photographs and downloaded necessary contents (jpeg images and xml file containing information (metadata) about the collection) 

2) Applied information gained from the xml file to the metadata template provided for CB (https://docs.google.com/spreadsheets/d/14iWUEoAJ6T9WDqlPnIHRN7M8-YgmMV4_bjFPVuSZ0yk/edit?usp=sharing) 

    Note: Can automate process through coding 

3) Imported the CB repository 

    a) Find repository at https://github.com/CollectionBuilder/collectionbuilder-gh 

    b) Click on 'Clone or download' 

    c) Click 'Clone with HTTPS' copy to clipboard icon 

    d) Under the + sign on the top right corner of the screen, press 'Import repository' 

    e) Paste URL into 'Your old repository's clone URL' 

    f) Name, then begin import 

4) Uploaded the pictures to the Objects directory 

5) Uploaded the csv file of metadata to _data directory 

6) Went back to the root directory and found _config.yml file 

    a) Edited the file according to the specifications in the file 

7) Navigated to the _data directory from the root branch and opened theme.yml 

    a) Worked through file and edited according to specifications

    Note: be sure to edit the name beside the 'metadata' tag to the name of your csv file that contains your metadata 

8) Published digital collection through master branch 

9) Continued to edit theme/csv files until the website fit specifications 

## Conclusion
Collection Builder is a very easy-to-use and intuitive tool. It allows for visualization of the connections between objects within a collection, such as location and time period. Furthermore, all that it requires from the user is a free to creat Github account.
