# Project Requirements for v0.0.1 Release

1. Data Objects
  1.1 Person
    1.1.1 Description
      1.1.1.1 Defines required and optional information related to a person of interest to the system
    1.1.2 Examples
      1.1.2.1 A tenant, property manager, user, administratior
    1.1.3 Required Fields
      1.1.3.1 ID ("id", auto assigned, primary key)
      1.1.3.2 First Name ("firstName, 50 Characters)
      1.1.3.3 Last Name ("lastName", 75 Characters)
    1.1.4 Optional Fields
      1.1.4.1 Middle Name ("middleName", 50 Characters)  
      1.1.4.2 Personal Identification Number ("pin", 4 digits)
        1.1.4.2.1 Description
          1.1.4.2.1.2 Validates identity, allows access to limited services, possibly by phone
      1.1.4.3 Hash ("hash", SHA-2)
        1.1.4.3.1 Description
	  1.1.4.3.1.1 Password that allows access to full services.

