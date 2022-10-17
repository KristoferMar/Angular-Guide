# Angular-Guide
Angular guide

### Lifecycle event sequence

#### ngOnChanges()
- Called before ngOnInit() and whenever one or more data-bound input properties change.
#### ngOnInit()
- Called once, after the first ngOnChanges(). ngOnInit() is still called even when ngOnChanges() is not. 
