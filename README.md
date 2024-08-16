# $M^3EL$: A Multi-task Multi-topic Dataset for Multi-modal Entity Linking

## Overview

$M^3EL$ is a high-quality human-annotated MEL dataset. It includes 79,625 instances, covering 9 diverse multi-modal tasks, and 5 different topics. 


## Dataset 

### Get the Data

- The annotated data: [here](https://drive.google.com/file/d/129olsROPDyK8Ziz3x99B-LHCXyZpUaG9/view?usp=sharing)


### Data Format

- The annotated data (mention level)
```
{
    'Qid': 'Q18151305', 
    'name': 'Kansas Saloon Smashers', 
    'description': '1901 film by Edwin Stanton Porter', 
    'sentence': 'Kansas Saloon Smashers is a 1901 comedy short film produced and distributed by Edison Studios. Directed by Edwin S. Porter, it is a satire of American activist Carrie Nation. The film portrays Nation and her followers entering and destroying a saloon. After the bartender retaliates by spraying Nation with water, policemen order them out; the identities of the actors are not known. Inspiration for the film was provided by an editorial cartoon which appeared in the New York Evening Journal.\n', 
    'image': [
                'KansasSaloonSmashers1901.jpg', 
                'https://commons.wikimedia.org/wiki/Special:FilePath/KansasSaloonSmashers1901.jpg', 
                '/M3EL/movies_candidates_images/Kansas Saloon Smashers-Q18151305/Q18151305.jpg'], 
    'candidates': [
                    {'Qid': 'Q18151305', 
                    'name': 'Kansas Saloon Smashers', 
                    'description': '1901 film by Edwin Stanton Porter', 
                    'image': [
                                'KansasSaloonSmashers1901.jpg', 
                                'https://commons.wikimedia.org/wiki/Special:FilePath/KansasSaloonSmashers1901.jpg', 
                                '/M3EL/movies_candidates_images/Kansas Saloon Smashers-Q18151305/Q18151305.jpg']}, 
                    {'Qid': 'Q1558', 
                    'name': 'Kansas', 
                    'description': 'state of the United States of America', 
                    'image': [
                                'Kansas in United States.png', 
                                'https://upload.wikimedia.org/wikipedia/commons/thumb/a/a6/Kansas_in_United_States.svg/220px-Kansas_in_United_States.svg.png', 
                                '/M3EL/movies_candidates_images/Kansas Saloon Smashers-Q18151305/Q1558.png']}, 
                    {'Qid': 'Q204328', 
                    'name': 'Kansas', 
                    'description': 'American rock band', 
                    'image': [
                                'Kansas Full 2.JPG', 
                                'https://commons.wikimedia.org/wiki/Special:FilePath/Kansas%20Full%202.JPG', 
                                '/M3EL/movies_candidates_images/Kansas Saloon Smashers-Q18151305/Q204328.JPG']}
                    ]
}
```
