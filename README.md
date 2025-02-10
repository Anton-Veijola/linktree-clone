# Linktree clone

gems:
devise (user auth)
optional: tailwind_devise (auth tailwind styles)

gem bundling:
bundle add devise tailwind_devise

gem installing: 
rails g devise:install
rails g tailwind_devise:views

models:
user
link
