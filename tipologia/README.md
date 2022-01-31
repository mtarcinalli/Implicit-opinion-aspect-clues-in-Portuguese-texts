# Typology of Implicit Aspects Clues (IACs)

The file containing the typology of IACs is in csv format and has the following information:

- domain: domain of the aspect
- aspect: the aspect
- implicit aspect clue: iac related to aspect
- category: IAC category
- qty: number of times the IAC appears in the dataset
- subcategory: IAC subcategory

The categories and subcategories are related to the type of knowledge needed to idenfify the relationship between the IAC and the aspect, and are presented below:

- Event (Action/Process/State): the identification occurs through the identification of actions, processes, or states related to the aspect:
    - Verb: the IAC is identified by a verb. Ex: verb "to pay" and aspect "price";
    - Non-verbal form: the IAC is identified by a term related to a verb. Ex.: the word "payment" and aspect "payment";
- Feature: the identification is given by terms related to the aspect or part of it:
    - Attribute: related to some characteristics of the aspect. Ex: "material" and aspect "design";
    - Equivalence: the IAC has a related meaning in relation to the aspect. Ex:  "hygiene" and the aspect "cleanliness";
    - Is-a: the IAC is an item related to the aspect. Ex: "breakfast" and the aspect "food";
    - Part-of: the IAC is part of the aspect. Ex: "bathroom" and the aspect "facilities";
- Qualification: the IAC is related to a quality or sentiment about the aspect:
    - Adjective: the IAC is identified by an adjective. Ex: "beautiful" and the aspect "design";
    - Equivalence: the IAC is in an "equivalence" relation to an adjective. Example: "plain hotel" and the aspect "facilities";
    - Nominal form: the IAC major term is an adjective converted to another word class. Ex: "beauty" and the aspect "design";
- Contextual: to identify an IAC of this category, it is necessary to have knowledge about the product or service being analyzed, such as its operation, modes of use, or content:
    - Location: the IAC is related to the localization of the product. Ex: the IAC "in the center of the region" and the aspect "location";
    - Related: other contextual cases not related to location. Ex: "musty smell" and the aspect "cleanliness".

Below is a sample of the csv file:

<pre>
domain,aspect,implict aspect clue,category,qty,subcategory
camera,Design,bonita,Qualification,2,Adjective
camera,Design,elegante,Qualification,1,Adjective
camera,Design,linda,Qualification,1,Adjective
camera,Design,versátil,Qualification,2,Adjective
</pre>