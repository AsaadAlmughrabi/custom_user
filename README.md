# custom_user
## to customize the authantication 
- don't make migration
- add AUTH_USER_MODEL = 'User.CustomUser' to use your user model not the model built it
- add cutom user in model and make model ihirit the AbstractUser and import it 
- create file form.py to add forms
- add class customcreationfrorm and extend userCreationform and import it
- add class meta and add your model after this add your fields you want 
- add clas userChangeForm to allow the user make changes 
- rigister the model in admin
- add your cutom class and update class in admin to make the admin page take the cutomization 