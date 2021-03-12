# Generator JHipster (Polarising)

## Changes

- Generate sequence per table:
  - Added the possibility of creation sequences per table and modified Entity id Generator strategy, if BD was PostgreSQL. 
  
- Added LocalTime type to JDL entities
  - Created a new type of entity LocalTime and generate all the artifacts with that modification  

### The main change about sequence per table was in the file field.js on line:

```} else if (entityWithConfig.prodDatabaseType === 'postgresql') {```
