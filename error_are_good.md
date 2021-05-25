Traceback (most recent call last):
        4: from /Users/zsuzsannaver/.rvm/rubies/ruby-3.0.0/bin/irb:23:in `<main>'
        3: from /Users/zsuzsannaver/.rvm/rubies/ruby-3.0.0/bin/irb:23:in `load'
        2: from /Users/zsuzsannaver/.rvm/rubies/ruby-3.0.0/lib/ruby/gems/3.0.0/gems/irb-1.3.0/exe/irb:11:in `<top (required)>'
        1: from (irb):1:in `<main>'
NameError (uninitialized constant DockingStation)
3.0.0 :002 >  

Write down the type of error
- Name Error(NameError is raised when you reference a constant or a variable which isn't defined in the current context.)

Write down the file path where the error happened
- /Users/zsuzsannaver/.rvm/rubies/ruby-3.0.0/bin/irb:23:in `<main>'
- /Users/zsuzsannaver/.rvm/rubies/ruby-3.0.0/bin/irb:23:in `load'
- /Users/zsuzsannaver/.rvm/rubies/ruby-3.0.0/bin/irb:23:in `<main>'

Write down the line number of the error
- 1

Use the Ruby Documentation to find out what the error means
- https://ruby-doc.org/core-2.5.0/NameError.html 

Suggest one way of solving the error.
- Define constant in VsCode using Class method --> Save --> Open Terminal --> Open irb.Use require to open the file