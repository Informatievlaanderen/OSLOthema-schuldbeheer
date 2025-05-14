# Notes regarding the design decisions of this data model

- https://spec.edmcouncil.org/fibo/ontology was considered but not used because it didn't match enough with the targeted use cases
- The participants of the working group insisted on the inclusion of concepts representing the balance (*Saldo*) (balance) or the fact if a loan or debt was paid back entirely in due time (*wanbetaling: false*), although this information can be derived from other data in the model. 
- The participants of the working group insisted on this inclusion of concepts regarding the solvability of a person. As it is not feasible to model this exhaustively, an extensible indicator of solvability (Solvabiliteitsindicator) was introduced. Four subclasses were defined, in response to the direct needs formulated by the working group. Other local needs can be modelled using the superclass Solvabiliteitsindicator, or by introducing more subclasses. 
