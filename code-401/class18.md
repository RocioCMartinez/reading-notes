# Many To Many Relationships/Security

## [Many to many relationships](https://www.baeldung.com/hibernate-many-to-many)

Name a few examples of real world ManyToMany relationships.

A real world example of ManyToMany relationships would be my previous job, biomed techs and work orders. Every tech has a profile to track their work and hours. Every tech is given work orders to place hours and work notes into. If there is an emergency or leave time a work order can be transfered to someone else. Multiple techs can be placed on a work order/multiple work orders depending on the work they did for that job.

Explain the significance of a join table for ManyToMany relationships.

The association is having a bidirectional relationship between two classes. Making transferring information easier.

What are the values held within a join table?

The join table is specified on the owning side. It is used to define the join/link table. Holds targeted information from both tables.

## [Security: a humorous overview](http://scholar.harvard.edu/files/mickens/files/thisworldofours.pdf)

According to the author of the article, will you ever be truly secure from ALL possible security threats?

> *" Thinking about security is like thinking about where to ride your motorcycle: the safe places are no fun, and the fun places are not safe. I shall ride wherever my spirit takes me, and I shall find my Gigantic Martian Insect Party, and I will, uh, probably be rent asunder by huge cryptozoological mandibles, but I will die like Thomas Jefferson: free, defiant, and without a security label."*

According to the author although we are aware of security threats we cannot let them limit us as we will never be truly secure from ALL possibilities.
