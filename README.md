# model-zoo
a website with curated open-source machine learning models supplemented with brief explanations/learning materials

## Pages

### Author portal
There are two main parts in the author portal (apart from the personal profile page).  
1. model card editor - here the author can edit a model card. these can be live, or draft model cards. the author can view version history and view the diff with old versions. Some sort of approval mechanism will be placed in here.  
2. model card pipeline - here the author can see an overview of all of the cards that they have authored/edited. they can see the stage that the model cards are in: published, in review, or draft.  

### Reader portal
This is a part of the website that everyone can access (without signing up). You have 3 main tabs in the reader portal.  
1. Explore: provides a feed of previews of model cards that have been updated recently / popular.
2. Search: a simple search bar that lets you search for model cards, returning previews of the most relevant cards
3. Model card viewer: where you view individual model cards in full

### User portal
These pages(/features) are only available to users that are signed up.
1. Starred: as a user you can star models and view your stars in a single page
2. Follow: you can follow authors. when authors publish things you can view these in a feed (similar to the explore tab)




## Data Schema

### Models
#### Links
- Link to paper
- Link to implementation
- Link to examples of uses

#### Information
- title
- description
- example of use cases of model
- model input/output (examples and schema)
- model latency information
- model memory information
- example code of implementing the model
- model hyperparameters
- model train time range
- model test time range
- recommendation of when to use

#### Other information
- date added and last updated
- history
- authors of model card

#### Authors
- name
- id
- auth id
- github link
- profile photo
- ...



