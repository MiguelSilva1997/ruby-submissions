* **Evaluator:** Victoria
* **Repo:** https://github.com/tylermarshal/black_thursday
* **Notes**

* Really well done breaking out modules & implementing appropriate enums & Ruby methods
* Make sure not to use {} with multi-line blocks
* Try to aim for 100-line classes max (think about Math modules, other appropriate classes)
* Make sure to test every method

## Evaluation Rubric

The project will be assessed with the following guidelines:

### 1. Ruby Syntax & Style

Expectations: 

- [x] Applies appropriate attribute encapsulation  
- [x] Developer creates instance and local variables appropriately
- [x] Naming follows convention (is idiomatic)
- [ ] Ruby methods used are logical and readable  
- [x] Developer implements best-choice enumerable methods
- [ ] Code is indented properly
- [x] Code does not exceed 80 characters per line

* 3: Meets expectations

### 2. Breaking Logic into Components

Expectations: 

- [x] Code is effectively broken into methods & classes 
- [x] Developer writes methods less than 6 lines 
- [ ] No more than 3 methods break the principle of SRP 

* 3: Meets expectations

### 3. Test-Driven Development

Expectations: 

- [ ] Each method is tested  
- [x] Functionality is accurately covered
- [x] Tests implement Ruby syntax & style   
- [x] Balances unit and integration tests 
- [x] Evidence of edge cases testing 
- [x] Test Coverage metrics are present (SimpleCov)
- [x] A test RakeTask is implemented

* 2: Below expectations

### 4. Functionality

Expectations: 

- [x] Application meets all requirements (all relevant tests pass the spec harness)

* 3: Meets expectations

### 5. Version Control

- [x] Developer commits at a pace of at least 1 commit per hour
- [x] Developer implements branching and PRs
- [x] The final submitted version is merged into master

* 4: Above expectations

### 6. Code Sanitation

- [ ] The output from `rake sanitation:all` shows five or fewer complaints

* 4: Above expectations
