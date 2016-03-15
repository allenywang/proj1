# Q0: Why is this error being thrown?

The pokemon model doesn't exist.

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *


They're appearing because the seeds.rb generated them. They all have null as their pokemon_trainer id. 

# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.

It's making a button called "Throw a Pokeball!" that patches a request which calls the capture method and passes in the ID of the current pokemon. 

# Question 3: What would you name your own Pokemon?

Tong

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?

I passed it to a trainer's path with the trainer's id specified. 

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.

It redirects it back to the page if the name is the same or if the name was used. It will get all the errors associated with the validation and show on the redirected form.

# Give us feedback on the project and decal below!

It was a cool project. I plan on doing the ec if I have time.

# Extra credit: Link your Heroku deployed app
