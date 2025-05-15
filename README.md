# OSLOthema-mijnThema

These are the source files for the OSLO track 'Schuldbeheer'.  
Examples are found at [./resources/Datavoorbeelden](./resources/Datavoorbeelden)  

**_Editors:_**
- first read [deze richtlijnen](https://github.com/Informatievlaanderen/OSLO-toolchain/blob/master/doc-user/README.md) .
- Use [TagsAndNotes.xlsm](https://github.com/Informatievlaanderen/OSLO-allerleiTooltjes/tree/master/EA-Excel/TagsAndNotes) 
  to edit tags in Excel. The files `*.xlsm` are included in the repo as git-ignored.


## Administrative information

### Tags
To refer to the available git tags to create a publication point from, see the "Releases" tab of this repo.


### Branches
The organisation and meaning of the git branches are documented in this table.


| Branch              | Purpose                         | Active (y/n) |
|---------------------|---------------------------------|--------------|
| main                | publication data model          | y            |
| standaardenregister | publication standaardenregister | y            |


## Publishing

To publish in the test environment, update [https://github.com/Informatievlaanderen/data.vlaanderen.be2/blob/test/config/test/schuldbeheer.publication.json](https://github.com/Informatievlaanderen/data.vlaanderen.be2/blob/test/config/test/schuldbeheer.publication.json)

To publish in the production environment, update [https://github.com/Informatievlaanderen/data.vlaanderen.be2/blob/production/config/production/schuldbeheer.publication.json](https://github.com/Informatievlaanderen/data.vlaanderen.be2/blob/production/config/production/schuldbeheer.publication.json)

To publication progress and potential reported errors can be followed [here](https://app.circleci.com/pipelines/github/Informatievlaanderen/data.vlaanderen.be2) 

To view error related to toolchain4: [https://github.com/Informatievlaanderen/data.vlaanderen.be2-generated/tree/production/report4](https://github.com/Informatievlaanderen/data.vlaanderen.be2-generated/tree/production/report4)
