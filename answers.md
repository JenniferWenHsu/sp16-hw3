1. What is the difference between new and create for a model?
	Answer: "create" can initialize all the attributes of the instance all at once, while "new" only initializes the instance. 

2. What command combined with new will emulate the same behavior as create?
	Answer: 
		Example of creating a new entry for the Cats database: 
			cat = Cat.create name="Cookie"

			is equivalent to 

			cat = Cat.new
			cat.name = "cookie"

		if "new" is used to create a new entry, then each attribute of the class should be initialized seaprately 

3. What is the column that exists on every table but we did NOT define?
	Answer: timestamps

4. What single line of ruby code can insert a cat with the name "hat" in the database?
	Answer: cat = Cat.create name:"hat"

5. What was the most confusing part over the last few weeks?
	Answer: Nothing. The instructor did a great job lecturing. 

6. How did you like this homework in comparison with the others?
	Answer: I like how this homework provides the big picture in the front and walkthroughs afterwards. It gives me a chance to practice how to complete tasks without detailed walkthroughs.