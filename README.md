#Hotel Callisto
 
 Features complete:
  - SignUp
 

To update db:

 - delete app.db if its exists
 - in terminal: $flask shell
              >>>from app import db
              >>>db.create_all()
              >>>exit()
