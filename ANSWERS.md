# Q0: Why is this error being thrown?

No Pokemon model yet

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *

random Pokemon are seeded in, all Pokemon have no trainer

# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.

Sends Pokemon being shown (its ID) into params to the capture method of the Pokemon controller

# Question 3: What would you name your own Pokemon?

HYPECLOUT

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?

used redirect_to trainer_path, with a parameter pokemon.trainer_id.  This redirects to the pokemon's trainer's profile after damaging

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.

the line takes errors from attempting to create an invalid pokemon and prints them out as a sentence



# Give us feedback on the project and decal below!

# Extra credit: Link your Heroku deployed app
